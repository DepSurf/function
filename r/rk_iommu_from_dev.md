# Function: <code>rk_iommu_from_dev</code>

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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/rockchip-iommu.c (ffff8000108d7bfc)
Location: drivers/iommu/rockchip-iommu.c:837
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_device_group
  - drivers/iommu/rockchip-iommu.c:rk_iommu_remove_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_add_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_attach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/rockchip-iommu.c (c09c56d0)
Location: drivers/iommu/rockchip-iommu.c:837
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_device_group
  - drivers/iommu/rockchip-iommu.c:rk_iommu_remove_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_add_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_attach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device
```
</details>
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
