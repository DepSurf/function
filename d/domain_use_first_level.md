# Function: <code>domain_use_first_level</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a35e7)
Location: drivers/iommu/intel/iommu.c:552
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:intel_alloc_iova
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:iommu_flush_iova
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b1bad)
Location: drivers/iommu/intel/iommu.c:542
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817948ae)
Location: drivers/iommu/intel/iommu.c:551
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181c7cf)
Location: drivers/iommu/intel/iommu.c:540
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195cdef)
Location: drivers/iommu/intel/iommu.c:420
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_enforce_cache_coherency
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
  - drivers/iommu/intel/iommu.c:__domain_mapping
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
```
</details>
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
In <code>arm64</code>: Absent ⚠️
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
