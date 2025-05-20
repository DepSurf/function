# Function: <code>iommu_is_dma_domain</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181a71e)
Location: include/linux/iommu.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:domain_get_iommu
```
```
In drivers/iommu/iommu.c (ffffffff81827925)
Location: include/linux/iommu.h:99
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182b7a5)
Location: include/linux/iommu.h:99
Inline: True
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
In drivers/iommu/intel/iommu.c (ffffffff8195ae2a)
Location: include/linux/iommu.h:100
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:domain_get_iommu
```
```
In drivers/iommu/iommu.c (ffffffff819672f1)
Location: include/linux/iommu.h:100
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196c875)
Location: include/linux/iommu.h:100
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
In drivers/iommu/iommu.c (ffffffff81aceaa2)
Location: include/linux/iommu.h:116
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad6f01)
Location: include/linux/iommu.h:116
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
In drivers/iommu/iommu.c (ffffffff81b1ff15)
Location: include/linux/iommu.h:116
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b256f1)
Location: include/linux/iommu.h:116
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
In drivers/iommu/iommu.c (ffffffff81b76530)
Location: include/linux/iommu.h:133
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
  - drivers/iommu/iommu.c:iommu_create_device_direct_mappings
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7c431)
Location: include/linux/iommu.h:133
Inline: True
```
</details>
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
