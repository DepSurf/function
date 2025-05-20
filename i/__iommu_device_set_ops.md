# Function: <code>__iommu_device_set_ops</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff82d1ac1a)
Location: include/linux/iommu.h:384
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179d2df)
Location: include/linux/iommu.h:384
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
```
In drivers/iommu/intel/iommu.c (ffffffff82d1e187)
Location: include/linux/iommu.h:384
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
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
In drivers/iommu/amd/init.c (ffffffff83008d77)
Location: include/linux/iommu.h:380
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
```
```
In drivers/iommu/intel/dmar.c (ffffffff817aaffe)
Location: include/linux/iommu.h:380
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
```
In drivers/iommu/intel/iommu.c (ffffffff8300be6c)
Location: include/linux/iommu.h:380
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
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
