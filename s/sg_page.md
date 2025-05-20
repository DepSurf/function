# Function: <code>sg_page</code>

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
In arch/x86/kernel/pci-nommu.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81067e62)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In crypto/scatterwalk.c (ffffffff8139ebf1)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
```
```
In crypto/ablkcipher.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In crypto/eseqiv.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In crypto/shash.c (ffffffff813a3cb7)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/shash.c:shash_compat_digest
```
```
In lib/scatterlist.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In lib/swiotlb.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In lib/mpi/mpicoder.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81516a0a)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff815740eb)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/ata/libata-sff.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8160d4ff)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/scatterlist.h:120
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
In arch/x86/kernel/pci-nommu.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066d6d)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81067bb1)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In crypto/scatterwalk.c (ffffffff813db9b1)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff813dce9f)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff813dd5f1)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/ahash.c (ffffffff813dec23)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff813dff73)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In lib/scatterlist.c (ffffffff814414cd)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In lib/swiotlb.c (ffffffff8145a98b)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_sg_attrs
```
```
In drivers/virtio/virtio_ring.c (ffffffff8150f144)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81525bca)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
```
```
In drivers/char/virtio_console.c (ffffffff81569670)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8157df59)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff81584a8b)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158c470)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff815cb13a)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff81606205)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff8162b82e)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff816385df)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/spi/spi.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8166d0aa)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff8167121c)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8167cd09)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
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
In arch/x86/kernel/pci-nommu.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a9bd)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106b801)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In crypto/scatterwalk.c (ffffffff813f3044)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff813f476d)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff813f4ec1)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff813f6403)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff813f71b3)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff813f8503)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In lib/scatterlist.c (ffffffff8145e6ed)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In lib/swiotlb.c (ffffffff81479161)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_sg_attrs
```
```
In drivers/virtio/virtio_ring.c (ffffffff8153b2a4)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815520cf)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
```
```
In drivers/char/virtio_console.c (ffffffff81595db0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff815aa4f6)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff815b1b79)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
```
```
In drivers/iommu/intel-iommu.c (ffffffff815b9ba8)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff815f7d7b)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff8163571b)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff8165c9ce)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff81669657)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/spi/spi.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8169ada7)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff8169eecc)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff816aaa84)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
```
```
In lib/dma-noop.c (0)
Location: include/linux/scatterlist.h:120
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
In arch/x86/kernel/pci-nommu.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069d05)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106ab7f)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In crypto/scatterwalk.c (ffffffff813ff3ab)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff81400ab1)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814011fd)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff81402827)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81403583)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff81404a20)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In crypto/scompress.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In lib/scatterlist.c (ffffffff814638fa)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In lib/swiotlb.c (ffffffff81482591)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81566b1f)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff815a9bb0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff815c0186)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c780b)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
```
```
In drivers/iommu/intel-iommu.c (ffffffff815cfb13)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff8160bb2a)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164a8d9)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/scsi_lib_dma.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff816712d9)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff8167ddc9)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/spi/spi.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff816b0167)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff816b4008)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff816bfa84)
Location: include/linux/scatterlist.h:120
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
```
```
In lib/dma-virt.c (0)
Location: include/linux/scatterlist.h:120
Inline: True
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
In arch/x86/kernel/pci-nommu.c (0)
Location: include/linux/scatterlist.h:127
Inline: True
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106e5b5)
Location: include/linux/scatterlist.h:127
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106f47f)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In crypto/scatterwalk.c (ffffffff81427958)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814290b1)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff8142980d)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8142ae97)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8142bcb3)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff8142d334)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In crypto/scompress.c (0)
Location: include/linux/scatterlist.h:127
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/scatterlist.h:127
Inline: True
```
```
In lib/scatterlist.c (ffffffff8148f8a6)
Location: include/linux/scatterlist.h:127
Inline: True
```
```
In lib/swiotlb.c (ffffffff814be4a4)
Location: include/linux/scatterlist.h:127
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:127
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815caccf)
Location: include/linux/scatterlist.h:127
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff816104d4)
Location: include/linux/scatterlist.h:127
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81626846)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162e4db)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
```
```
In drivers/iommu/intel-iommu.c (ffffffff8163689f)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
```
In drivers/base/devcoredump.c (0)
Location: include/linux/scatterlist.h:127
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff816743e0)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b3c49)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff816da8b9)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff816e75c2)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff8171b6d3)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff8171f838)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8172b434)
Location: include/linux/scatterlist.h:127
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
```
```
In lib/dma-virt.c (0)
Location: include/linux/scatterlist.h:127
Inline: True
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810712db)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff810720bf)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/direct.c (ffffffff8110d0fc)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In kernel/dma/virt.c (ffffffff8110d248)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff8110e2ed)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In kernel/bpf/sockmap.c (ffffffff811cfbac)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
  - kernel/bpf/sockmap.c:free_sg
  - kernel/bpf/sockmap.c:free_bytes_sg
  - kernel/bpf/sockmap.c:bpf_tcp_push
```
```
In crypto/scatterwalk.c (ffffffff8145a7b8)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff8145be5d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff8145c7dc)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8145dbc5)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8145e9a3)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff8145ffa0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In crypto/xts.c (0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In lib/scatterlist.c (ffffffff814c4098)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81603522)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81649f9a)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81661466)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:default_iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff8166925b)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff81671e3e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
```
In drivers/base/devcoredump.c (ffffffff816a9055)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff816b058b)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff816efcee)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81716d80)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff81723cf7)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff8175a4ec)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff8175f4bb)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8176a4ef)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/sock.c (ffffffff818773df)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc_sg
```
```
In net/core/filter.c (ffffffff818b3a94)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810772d3)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff81078080)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/direct.c (ffffffff8111891d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
```
```
In kernel/dma/virt.c (ffffffff81118f18)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff81478328)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff8147975d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff81479e4c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8147b465)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8147c313)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff8147da30)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff814d8798)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161e602)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff816681da)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8167fd16)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff81687abc)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff8169076e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
```
In drivers/base/devcoredump.c (ffffffff816c9c35)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff816d0758)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/scsi/scsi_lib.c (ffffffff8171354e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff817393c0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff81746617)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff8177ea3d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff81783a9b)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8178ea7f)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff818d95e1)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff818e5ccd)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff8197709a)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107ad14)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107bcb8)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/direct.c (ffffffff81122d4d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In kernel/dma/virt.c (ffffffff81123910)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff814a616b)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814a73fd)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814a7ce4)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814a96d6)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814aa603)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff814abccb)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff815046d8)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81651756)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8169dc6a)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff816b7136)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bf23f)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c8925)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
```
In drivers/base/devcoredump.c (ffffffff817051e2)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff8170b79d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174ee31)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff817753f5)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff817822eb)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff817bcfc9)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff817c1dae)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817cb74e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff8192b6f7)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff819355e7)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e0bc1)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107be04)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107cda8)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/direct.c (ffffffff8112f18d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In kernel/dma/virt.c (ffffffff8112f8a0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff814c0dfb)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814c206d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814c2944)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814c43c6)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814c52c3)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff814c69ab)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff81522668)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81673d16)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff816c09da)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff816d9ce6)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e25df)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ee141)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
```
In drivers/base/devcoredump.c (ffffffff81729472)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff8172fa9d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff8177300e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81799365)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff817a5f9b)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff817eda06)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff817f272e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817fc3ae)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff8195da2a)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff819683a7)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a17bf1)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810832a1)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce
```
```
In kernel/dma/direct.c (ffffffff8113de70)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In kernel/dma/virt.c (ffffffff8113e660)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_sg
```
```
In mm/page_reporting.c (ffffffff8130cea5)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff81521847)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81523320)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff815241f3)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff81525c74)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff81586669)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170b60c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817246f6)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8177445a)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/iommu/iommu.c (ffffffff817902da)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a5e0a)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:bounce_map_sg
  - drivers/iommu/intel/iommu.c:__domain_mapping
```
```
In drivers/iommu/intel/trace.c (ffffffff817a8d55)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_dma_map_sg
  - drivers/iommu/intel/trace.c:trace_event_raw_event_dma_map_sg
```
```
In drivers/base/devcoredump.c (ffffffff817e5ca2)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff817eec67)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff81834c9e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff8186a27e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff818bcf77)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff818c20ab)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff818cde1e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81a2c9cb)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81a3bde1)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0846c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b224c2)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81084a91)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce
```
```
In kernel/dma/direct.c (ffffffff8113941f)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In mm/page_reporting.c (ffffffff81318dfa)
Location: include/linux/scatterlist.h:118
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff8153e6b7)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81540270)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81541073)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff81542ba4)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff815a323b)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table_from_pages
```
```
In drivers/virtio/virtio_ring.c (ffffffff81728463)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81741446)
Location: include/linux/scatterlist.h:118
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8178f1ba)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/iommu/intel/trace.c (ffffffff817b4c75)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_dma_map_sg
  - drivers/iommu/intel/trace.c:trace_event_raw_event_dma_map_sg
```
```
In drivers/iommu/iommu.c (ffffffff817bb7b2)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff817bf0b4)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg_swiotlb
```
```
In drivers/base/devcoredump.c (ffffffff817fa932)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff81803567)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8183b4ef)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/dma-buf/heaps/system_heap.c:system_heap_do_vmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
  - drivers/dma-buf/heaps/system_heap.c:dup_sg_table
```
```
In drivers/scsi/scsi_lib.c (ffffffff81845d6e)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff8187908e)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff818c9c12)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff818ce39b)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff818d8e16)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81a2df7b)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81a3fec5)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b169cc)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b30ec2)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81085943)
Location: include/linux/scatterlist.h:118
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff81138b38)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/mapping.c:dma_free_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff8113a50f)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In mm/page_reporting.c (ffffffff8131efea)
Location: include/linux/scatterlist.h:118
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff81546d67)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81548767)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff815496e3)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff8154b245)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff815aa5fb)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:__sg_alloc_table_from_pages
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170a909)
Location: include/linux/scatterlist.h:118
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81724df6)
Location: include/linux/scatterlist.h:118
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81771faa)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/iommu/iommu.c (ffffffff8179deb2)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a22e0)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
```
In drivers/base/devcoredump.c (ffffffff817df642)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff817e7d2d)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff8181e6fa)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182900e)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff8185b8ce)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff818acc82)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff818b166e)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff818bbfa5)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81a14c4e)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81a4e768)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b046ec)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81b1ebf0)
Location: include/linux/scatterlist.h:118
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81094af9)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In kernel/dma/mapping.c (ffffffff8115ba48)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/mapping.c:dma_free_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff8115d4fd)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In mm/page_reporting.c (ffffffff8136c3ba)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff815a7547)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff815a8f47)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff815a9ec3)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff815aba25)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff8161388b)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
```
```
In drivers/virtio/virtio_ring.c (ffffffff817866d8)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a3c5c)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff817f7d4a)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/iommu/iommu.c (ffffffff81826ff2)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182b3d2)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
```
In drivers/base/devcoredump.c (ffffffff8186b072)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff81873c50)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff818a8bdc)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b49ee)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff818eb340)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff81941cdb)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff819468be)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81950775)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81ac86db)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81b05119)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc6a51)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81be385e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810a6db8)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In kernel/dma/mapping.c (ffffffff81185578)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/mapping.c:dma_free_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff811873d0)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In mm/page_reporting.c (ffffffff813ea6bb)
Location: include/linux/scatterlist.h:141
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff8164e646)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81650533)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff816513e3)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff81653335)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff816e0155)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
```
```
In drivers/virtio/virtio_ring.c (ffffffff818bd797)
Location: include/linux/scatterlist.h:141
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818ddfad)
Location: include/linux/scatterlist.h:141
Inline: True
```
```
In drivers/xen/grant-dma-ops.c (0)
Location: include/linux/scatterlist.h:141
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81936abc)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/iommu/iommu.c (ffffffff81966b98)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196baaf)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
```
In drivers/base/devcoredump.c (ffffffff819b3d85)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff819bb688)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff819f2b02)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
```
```
In drivers/scsi/scsi_lib.c (ffffffff819ff991)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff81a3bca0)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff81a9b2f2)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff81a9f38a)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81aa8f73)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81c44c50)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81c8d3ff)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5c1e2)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81d7b2a8)
Location: include/linux/scatterlist.h:141
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810c0028)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In kernel/dma/mapping.c (ffffffff811c0dd8)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/mapping.c:dma_free_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff811c2f0c)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In mm/page_reporting.c (ffffffff8147284b)
Location: include/linux/scatterlist.h:144
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff81707a96)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81709cd3)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8170ac83)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff8170d055)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff817d0395)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
```
```
In drivers/pci/p2pdma.c (ffffffff8191d34c)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a0c6b7)
Location: include/linux/scatterlist.h:144
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a3149d)
Location: include/linux/scatterlist.h:144
Inline: True
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a3533f)
Location: include/linux/scatterlist.h:144
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81a9695c)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/iommu/iommu.c (ffffffff81ad031a)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad5f6c)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
```
In drivers/base/devcoredump.c (ffffffff81b28aa5)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff81b30bd8)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81b7091b)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7dfe9)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff81bc10f0)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff81c20141)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff81c2480a)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81c30223)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81dff20d)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81e45a3f)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f2635d)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81f48317)
Location: include/linux/scatterlist.h:144
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810c3705)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In kernel/dma/mapping.c (ffffffff811d38c8)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/mapping.c:dma_free_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff811d5a4c)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In mm/page_reporting.c (ffffffff814a6fbb)
Location: include/linux/scatterlist.h:168
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff81741206)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff817438e3)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8174544a)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff817469ad)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff8180efe5)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
```
```
In drivers/pci/p2pdma.c (ffffffff8196090c)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a553b7)
Location: include/linux/scatterlist.h:168
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a7acad)
Location: include/linux/scatterlist.h:168
Inline: True
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a7ed4f)
Location: include/linux/scatterlist.h:168
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81ae216c)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/iommu/iommu.c (ffffffff81b1fc95)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b246ec)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
```
In drivers/base/devcoredump.c (ffffffff81b78c55)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff81b84298)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81bc4103)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd1dc9)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff81c18bd0)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff81c870c1)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff81c8b962)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81c9746e)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81e70cdd)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81ea104f)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f85f5b)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81fa7e6e)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810cbb45)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In kernel/dma/mapping.c (ffffffff811e8568)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_vmap_noncontiguous
  - kernel/dma/mapping.c:dma_free_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff811ea9cc)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In mm/page_reporting.c (ffffffff814d7fbb)
Location: include/linux/scatterlist.h:168
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff817820a6)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_ffwd
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81785c13)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8178773d)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
  - crypto/ahash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff81854c65)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free
  - lib/scatterlist.c:sgl_alloc_order
  - lib/scatterlist.c:sg_alloc_append_table_from_pages
```
```
In drivers/pci/p2pdma.c (ffffffff819aa02c)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:pci_p2pmem_free_sgl
```
```
In drivers/virtio/virtio_ring.c (ffffffff81aa5c88)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_map_one_sg
  - drivers/virtio/virtio_ring.c:vring_map_one_sg
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acce1d)
Location: include/linux/scatterlist.h:168
Inline: True
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81ad12bf)
Location: include/linux/scatterlist.h:168
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81b3555c)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:free_buf
```
```
In drivers/iommu/iommu.c (ffffffff81b75cf5)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7b35c)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
```
In drivers/base/devcoredump.c (ffffffff81bccb25)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd81c8)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_completion
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81c18932)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_dma_buf_release
  - drivers/dma-buf/heaps/system_heap.c:system_heap_vmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_mmap
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c26a39)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-sff.c (ffffffff81c6d920)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/gpu/drm/drm_cache.c (ffffffff81c813df)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_cache.c:drm_clflush_sg
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81cac290)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_prime.c:drm_prime_sg_to_page_array
```
```
In drivers/usb/core/hcd.c (ffffffff81d3bb21)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff81d40412)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff81d4bf4e)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff81f303b4)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81f6372f)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d53b)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff8207512e)
Location: include/linux/scatterlist.h:168
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
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
In kernel/dma/direct.c (ffff800010194b64)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In kernel/dma/virt.c (ffff800010195fcc)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In crypto/scatterwalk.c (ffff8000105bb08c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffff8000105bc960)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffff8000105bd178)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffff8000105bf054)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffff8000105bfeb0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffff8000105c1e0c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffff80001062c304)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffff80001083df98)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/char/virtio_console.c (ffff8000108b3818)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/iommu/iommu.c (ffff8000108c61c0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca148)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
```
In drivers/base/devcoredump.c (ffff80001091f1a4)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffff8000109267cc)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffff800010976604)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffff8000109a2a78)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffff8000109b22e0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffff800010a1c99c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffff800010a22978)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffff800010a2f860)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffff800010bfdafc)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffff800010c0e2b4)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd37dc)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In arch/arm/mm/dma-mapping.c (c031b66c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_sync_sg_for_device
  - arch/arm/mm/dma-mapping.c:arm_iommu_sync_sg_for_cpu
  - arch/arm/mm/dma-mapping.c:arm_iommu_unmap_sg
  - arch/arm/mm/dma-mapping.c:__map_sg_chunk
  - arch/arm/mm/dma-mapping.c:arm_dma_map_sg
```
```
In kernel/dma/direct.c (c03e198c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In kernel/dma/virt.c (c03e2850)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In crypto/scatterwalk.c (c0769378)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (c076a5f0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (c076af84)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c076c874)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (c076daa0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (c076f408)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (c07d2cc4)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/char/virtio_console.c (c09ad670)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/iommu/iommu.c (c09bca0c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/base/devcoredump.c (c0a0441c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/scsi/scsi_lib.c (c0a4afa4)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (c0a73c84)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (c0a81634)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (c0af595c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (c0af97a0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (c0b034d0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/mmc/host/sdhci.c (c0c28138)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_finish_data
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
```
```
In net/core/filter.c (c0d19da0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (c0d266b0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (c0ddd71c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In arch/powerpc/kernel/iommu.c (c00000000005236c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:ppc_iommu_map_sg
```
```
In kernel/dma/direct.c (c0000000001f4e50)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In kernel/dma/virt.c (c0000000001f6010)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_map_sg
```
```
In crypto/scatterwalk.c (c000000000741778)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (c000000000743404)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (c000000000744114)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c00000000074685c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (c000000000747db0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (c00000000074a450)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (c0000000007cecf4)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/char/virtio_console.c (c00000000094bc60)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/iommu/iommu.c (c00000000096b8d0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/base/devcoredump.c (c0000000009c4444)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/scsi/scsi_lib.c (c000000000a30e88)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (c000000000a686b4)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (c000000000a7ae64)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (c000000000ad7f28)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (c000000000add980)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (c000000000aebf7c)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (c000000000ce94c4)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (c000000000cf9b88)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (c000000000df2904)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In kernel/dma/direct.c (ffffffe000126a32)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In kernel/dma/virt.c (ffffffe000127a1a)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In crypto/scatterwalk.c (ffffffe000400bc0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffe0004021aa)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffe000402884)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffe000404294)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffe000404f0e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffe000406974)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffe00045c546)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffe000564f70)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffe00059e1c8)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005decb2)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffffffe000603150)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffe00060eee6)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffe000641698)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffe0006458e6)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffe00064fc84)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071a88a)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In net/core/filter.c (ffffffe00077d228)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffe00078ad20)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824776)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107ae04)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107bda8)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/direct.c (ffffffff8112776d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In kernel/dma/virt.c (ffffffff81128050)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff814b93db)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814ba64d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814baf24)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814bc9a6)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814bd8a3)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff814bef8b)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff8151ac48)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81639a06)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8168642a)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8169f736)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a802f)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b38b1)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
```
In drivers/base/devcoredump.c (ffffffff816ef252)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff816f5a0d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff817276fe)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/nvme/host/pci.c (ffffffff8175146b)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_map_data
```
```
In drivers/ata/libata-scsi.c (ffffffff8175e455)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff8176b05b)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff817a5de6)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff817aab0e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817b478e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff818fd9fa)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81908377)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7281)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a534)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106b4d8)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/direct.c (ffffffff8111a1cd)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In kernel/dma/virt.c (ffffffff8111a8e0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff814a9dfb)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814ab06d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814ab944)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814ad3c6)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814ae2c3)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff814af9ab)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff8150af38)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81664384)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8167d126)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff81685a1f)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff81691571)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
```
In drivers/scsi/scsi_lib.c (ffffffff81700b29)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/scsi/storvsc_drv.c (ffffffff81714122)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
```
```
In drivers/nvme/host/pci.c (ffffffff8173130b)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_map_data
```
```
In drivers/ata/libata-scsi.c (ffffffff8173e2f5)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff8174aebb)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff81798316)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff8179c50e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817a61be)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff818b782a)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff818c2187)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974071)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107adb4)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107bd58)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/direct.c (ffffffff8112565d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In kernel/dma/virt.c (ffffffff81125d70)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff814b546b)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814b66dd)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814b6fb4)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814b8a36)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814b9933)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff814bb01b)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff81516cd8)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81667b56)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff816b4ad4)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff816cd9a6)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d629f)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e1e01)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
```
In drivers/base/devcoredump.c (ffffffff8171c932)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff81722f5d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff817664ce)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff8178e1e5)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff8179ae1b)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff817e2886)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff817e75ae)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff817f122e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff8194ea2a)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff819593a7)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a21d01)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107ceb4)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff8107de58)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_map_sg
```
```
In kernel/dma/direct.c (ffffffff81131c9d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
```
In kernel/dma/virt.c (ffffffff811323b0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In crypto/scatterwalk.c (ffffffff814cdeeb)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814cf17d)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814cfa44)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814d14f6)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814d2393)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/ahash.c:hash_walk_new_entry
```
```
In crypto/shash.c (ffffffff814d3acf)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
```
```
In lib/scatterlist.c (ffffffff81530468)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_free_n_order
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81682116)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff816ced7a)
Location: include/linux/scatterlist.h:124
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff816e7ee6)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816f084f)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fc441)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
```
In drivers/base/devcoredump.c (ffffffff81737c92)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
```
In drivers/block/xen-blkfront.c (ffffffff8173e3a0)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/scsi/scsi_lib.c (ffffffff81781b7e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8035)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
```
In drivers/ata/libata-sff.c (ffffffff817b4c9b)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In drivers/usb/core/hcd.c (ffffffff817fd5d6)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
```
```
In drivers/usb/core/message.c (ffffffff818017fe)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_sg_init
```
```
In drivers/usb/core/devio.c (ffffffff8180b46e)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:snoop_urb_data
  - drivers/usb/core/devio.c:free_async
```
```
In net/core/filter.c (ffffffff819703fa)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff8197b4c7)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2d0ab)
Location: include/linux/scatterlist.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
</details>
</li>
</ul>

## Differences
