# Function: <code>sg_phys</code>

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
In arch/x86/kernel/pci-nommu.c (ffffffff81036e26)
Location: include/linux/scatterlist.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066fdd)
Location: include/linux/scatterlist.h:224
Inline: True
```
```
In lib/swiotlb.c (ffffffff81412a71)
Location: include/linux/scatterlist.h:224
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_sg_attrs
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/scatterlist.h:224
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff814d4b76)
Location: include/linux/scatterlist.h:224
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/scatterlist.h:224
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
In arch/x86/kernel/pci-nommu.c (ffffffff81036026)
Location: include/linux/scatterlist.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066d6d)
Location: include/linux/scatterlist.h:224
Inline: True
```
```
In lib/swiotlb.c (ffffffff8145a951)
Location: include/linux/scatterlist.h:224
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_sg_attrs
```
```
In drivers/virtio/virtio_ring.c (ffffffff8150f144)
Location: include/linux/scatterlist.h:224
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81525bca)
Location: include/linux/scatterlist.h:224
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
```
```
In drivers/iommu/amd_iommu.c (ffffffff81584a8b)
Location: include/linux/scatterlist.h:224
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
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
In arch/x86/kernel/pci-nommu.c (ffffffff81035d5d)
Location: include/linux/scatterlist.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a9bd)
Location: include/linux/scatterlist.h:224
Inline: True
```
```
In lib/swiotlb.c (ffffffff81479161)
Location: include/linux/scatterlist.h:224
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_sg_attrs
```
```
In drivers/virtio/virtio_ring.c (ffffffff8153b2a4)
Location: include/linux/scatterlist.h:224
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815520cf)
Location: include/linux/scatterlist.h:224
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_map_sg_attrs
```
```
In drivers/iommu/amd_iommu.c (ffffffff815b1b79)
Location: include/linux/scatterlist.h:224
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
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
In arch/x86/kernel/pci-nommu.c (ffffffff81033d18)
Location: include/linux/scatterlist.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069d05)
Location: include/linux/scatterlist.h:224
Inline: True
```
```
In lib/swiotlb.c (ffffffff81482591)
Location: include/linux/scatterlist.h:224
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8154eb3e)
Location: include/linux/scatterlist.h:224
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81566b1f)
Location: include/linux/scatterlist.h:224
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c780b)
Location: include/linux/scatterlist.h:224
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
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
In arch/x86/kernel/pci-nommu.c (ffffffff81036058)
Location: include/linux/scatterlist.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/pci-nommu.c:nommu_map_sg
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106e5b5)
Location: include/linux/scatterlist.h:231
Inline: True
```
```
In lib/swiotlb.c (ffffffff814be4a4)
Location: include/linux/scatterlist.h:231
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff815b22ee)
Location: include/linux/scatterlist.h:231
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff815caccf)
Location: include/linux/scatterlist.h:231
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162e4db)
Location: include/linux/scatterlist.h:231
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff8163689f)
Location: include/linux/scatterlist.h:231
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
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
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8110d111)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff8110e2ed)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff815ea74e)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81603522)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/iommu/amd_iommu.c (ffffffff8166925b)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff81671e3e)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
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
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8111861a)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
```
```
In drivers/virtio/virtio_ring.c (ffffffff81605396)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff8161e602)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8167fd16)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff81687abc)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff8169076e)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
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
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff81638539)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff816b7136)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bf23f)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c8925)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
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
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8165a329)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff816d9ce6)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e25df)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff816eb8e5)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
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
Location: include/linux/scatterlist.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170b5ae)
Location: include/linux/scatterlist.h:236
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
```
```
In drivers/iommu/iommu.c (ffffffff817902da)
Location: include/linux/scatterlist.h:236
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/scatterlist.h:236
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a2a58)
Location: include/linux/scatterlist.h:236
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:__domain_mapping
```
```
In drivers/iommu/intel/trace.c (ffffffff817a8d55)
Location: include/linux/scatterlist.h:236
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_dma_map_sg
  - drivers/iommu/intel/trace.c:trace_event_raw_event_dma_map_sg
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
Location: include/linux/scatterlist.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce
```
```
In drivers/virtio/virtio_ring.c (ffffffff8172840c)
Location: include/linux/scatterlist.h:235
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
```
```
In drivers/iommu/intel/trace.c (ffffffff817b4c75)
Location: include/linux/scatterlist.h:235
Inline: True
Inline callers:
  - drivers/iommu/intel/trace.c:perf_trace_dma_map_sg
  - drivers/iommu/intel/trace.c:trace_event_raw_event_dma_map_sg
```
```
In drivers/iommu/iommu.c (ffffffff817bb7b2)
Location: include/linux/scatterlist.h:235
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff817bf0b4)
Location: include/linux/scatterlist.h:235
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg_swiotlb
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
Location: include/linux/scatterlist.h:235
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170a909)
Location: include/linux/scatterlist.h:235
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8179deb2)
Location: include/linux/scatterlist.h:235
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a22e0)
Location: include/linux/scatterlist.h:235
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
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
Location: include/linux/scatterlist.h:241
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In drivers/virtio/virtio_ring.c (ffffffff817866d8)
Location: include/linux/scatterlist.h:241
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81826ff2)
Location: include/linux/scatterlist.h:241
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182b3d2)
Location: include/linux/scatterlist.h:241
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
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
Location: include/linux/scatterlist.h:258
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In drivers/virtio/virtio_ring.c (ffffffff818bd797)
Location: include/linux/scatterlist.h:258
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81966b98)
Location: include/linux/scatterlist.h:258
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/scatterlist.h:258
Inline: True
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
Location: include/linux/scatterlist.h:327
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In drivers/pci/p2pdma.c (ffffffff8191d3e2)
Location: include/linux/scatterlist.h:327
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a0c6b7)
Location: include/linux/scatterlist.h:327
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81ad031a)
Location: include/linux/scatterlist.h:327
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/scatterlist.h:327
Inline: True
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
Location: include/linux/scatterlist.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In drivers/pci/p2pdma.c (ffffffff819609a2)
Location: include/linux/scatterlist.h:387
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a553b7)
Location: include/linux/scatterlist.h:387
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81b1fc95)
Location: include/linux/scatterlist.h:387
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/scatterlist.h:387
Inline: True
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
Location: include/linux/scatterlist.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
```
In drivers/pci/p2pdma.c (ffffffff819aa0bc)
Location: include/linux/scatterlist.h:387
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
```
```
In drivers/virtio/virtio_ring.c (ffffffff81aa5c88)
Location: include/linux/scatterlist.h:387
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_map_one_sg
```
```
In drivers/iommu/iommu.c (ffffffff81b75cf5)
Location: include/linux/scatterlist.h:387
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/scatterlist.h:387
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
In drivers/virtio/virtio_ring.c (ffff800010821bd8)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/iommu/iommu.c (ffff8000108c61c0)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/dma-iommu.c (ffff8000108c9340)
Location: include/linux/scatterlist.h:222
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
In drivers/virtio/virtio_ring.c (c093ff3c)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/iommu/iommu.c (c09bca0c)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
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
In drivers/virtio/virtio_ring.c (c0000000008cb7c0)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/iommu/iommu.c (c00000000096b8d0)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe0005187ca)
Location: include/linux/scatterlist.h:222
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107ae04)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff816201c9)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8169f736)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a802f)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b1215)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
```
In drivers/nvme/host/pci.c (ffffffff8175146b)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_map_data
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
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff81614819)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8167d126)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff81685a1f)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168ed15)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
```
In drivers/nvme/host/pci.c (ffffffff8173130b)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_map_data
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
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8164e169)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff816cd9a6)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d629f)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff816df5a5)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
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
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff816687f9)
Location: include/linux/scatterlist.h:222
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff816e7ee6)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_map_sg
```
```
In drivers/iommu/amd_iommu.c (ffffffff816f084f)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:sg_num_pages
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f9bb5)
Location: include/linux/scatterlist.h:222
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__domain_mapping
```
</details>
</li>
</ul>

## Differences
