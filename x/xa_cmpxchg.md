# Function: <code>xa_cmpxchg</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac1f32)
Location: include/linux/xarray.h:688
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/iommu/iommu.c (ffffffff81acf34d)
Location: include/linux/xarray.h:688
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
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
In drivers/iommu/intel/iommu.c (ffffffff81b0ebcb)
Location: include/linux/xarray.h:688
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/iommu/iommu.c (ffffffff81b1dfdd)
Location: include/linux/xarray.h:688
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
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
In drivers/iommu/intel/iommu.c (ffffffff81b66579)
Location: include/linux/xarray.h:688
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
```
In drivers/iommu/iommu.c (ffffffff81b73f8a)
Location: include/linux/xarray.h:688
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_attach_device_pasid
```
```
In net/netlink/genetlink.c (ffffffff81f8fdb0)
Location: include/linux/xarray.h:688
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_sk_priv_get
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
