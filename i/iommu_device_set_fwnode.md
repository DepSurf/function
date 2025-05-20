# Function: <code>iommu_device_set_fwnode</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/arm-smmu.c (ffff8000108d25b4)
Location: include/linux/iommu.h:385
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d75f8)
Location: include/linux/iommu.h:385
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d7f84)
Location: include/linux/iommu.h:385
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/iommu/qcom_iommu.c (0)
Location: include/linux/iommu.h:385
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dc134)
Location: include/linux/iommu.h:385
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
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
In drivers/iommu/ipmmu-vmsa.c (c09c28c0)
Location: include/linux/iommu.h:385
Inline: True
Inline callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_probe
```
```
In drivers/iommu/rockchip-iommu.c (c09c5a08)
Location: include/linux/iommu.h:385
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/iommu/tegra-gart.c (c09c76c0)
Location: include/linux/iommu.h:385
Inline: True
Inline callers:
  - drivers/iommu/tegra-gart.c:tegra_gart_probe
```
```
In drivers/iommu/tegra-smmu.c (c09c8ce4)
Location: include/linux/iommu.h:385
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
```
```
In drivers/iommu/exynos-iommu.c (c09ca3c0)
Location: include/linux/iommu.h:385
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
```
```
In drivers/iommu/qcom_iommu.c (c09cbc58)
Location: include/linux/iommu.h:385
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
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
