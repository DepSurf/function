# Function: <code>swiotlb_tbl_sync_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814122d0)
Location: lib/swiotlb.c:596
Inline: False
```
**Symbols:**

```
ffffffff814122d0-ffffffff8141235a: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff8145a010)
Location: lib/swiotlb.c:596
Inline: False
```
**Symbols:**

```
ffffffff8145a010-ffffffff8145a096: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814789f0)
Location: lib/swiotlb.c:638
Inline: False
```
**Symbols:**

```
ffffffff814789f0-ffffffff81478a76: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81481b00)
Location: lib/swiotlb.c:638
Inline: False
```
**Symbols:**

```
ffffffff81481b00-ffffffff81481b73: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814bd960)
Location: lib/swiotlb.c:680
Inline: False
```
**Symbols:**

```
ffffffff814bd960-ffffffff814bd9d3: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8110e5c0)
Location: kernel/dma/swiotlb.c:663
Inline: False
```
**Symbols:**

```
ffffffff8110e5c0-ffffffff8110e637: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81119ae0)
Location: kernel/dma/swiotlb.c:591
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
```
**Symbols:**

```
ffffffff81119ae0-ffffffff81119b57: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81124510)
Location: kernel/dma/swiotlb.c:620
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
```
**Symbols:**

```
ffffffff81124510-ffffffff81124587: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81130490)
Location: kernel/dma/swiotlb.c:627
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/iommu/intel-iommu.c:bounce_sync_single
```
**Symbols:**

```
ffffffff81130490-ffffffff81130507: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113f270)
Location: kernel/dma/swiotlb.c:628
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
  - drivers/iommu/intel/iommu.c:bounce_sync_single
```
**Symbols:**

```
ffffffff8113f270-ffffffff8113f2e7: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113a950)
Location: kernel/dma/swiotlb.c:643
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
```
**Symbols:**

```
ffffffff8113a950-ffffffff8113a9c7: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffff800010196d90)
Location: kernel/dma/swiotlb.c:627
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
```
**Symbols:**

```
ffff800010196d90-ffff800010196e58: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (c0000000001f72e0)
Location: kernel/dma/swiotlb.c:627
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
```
**Symbols:**

```
c0000000001f72e0-c0000000001f739c: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffe000128644)
Location: kernel/dma/swiotlb.c:627
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
```
**Symbols:**

```
ffffffe000128644-ffffffe000128708: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81128c40)
Location: kernel/dma/swiotlb.c:627
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/iommu/intel-iommu.c:bounce_sync_single
```
**Symbols:**

```
ffffffff81128c40-ffffffff81128cb7: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8111b4d0)
Location: kernel/dma/swiotlb.c:627
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_single
```
**Symbols:**

```
ffffffff8111b4d0-ffffffff8111b547: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81126960)
Location: kernel/dma/swiotlb.c:627
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/iommu/intel-iommu.c:bounce_sync_single
```
**Symbols:**

```
ffffffff81126960-ffffffff811269d7: swiotlb_tbl_sync_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void swiotlb_tbl_sync_single(struct device *hwdev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81132fa0)
Location: kernel/dma/swiotlb.c:627
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_single_for_cpu
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - kernel/dma/direct.c:dma_direct_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
  - drivers/iommu/intel-iommu.c:bounce_sync_single
```
**Symbols:**

```
ffffffff81132fa0-ffffffff81133017: swiotlb_tbl_sync_single (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
