# Function: <code>iommu_device_set_ops</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff820f64e5)
Location: include/linux/iommu.h:256
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff815cc044)
Location: include/linux/iommu.h:256
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff820f8477)
Location: include/linux/iommu.h:256
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/amd_iommu_init.c (ffffffff826ffc3d)
Location: include/linux/iommu.h:265
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff81632e14)
Location: include/linux/iommu.h:265
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff82701b25)
Location: include/linux/iommu.h:265
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/amd_iommu_init.c (ffffffff8166cb4c)
Location: include/linux/iommu.h:265
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff8166e025)
Location: include/linux/iommu.h:265
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff8272b88e)
Location: include/linux/iommu.h:265
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/amd_iommu_init.c (ffffffff828e214c)
Location: include/linux/iommu.h:256
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff8168c455)
Location: include/linux/iommu.h:256
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e4179)
Location: include/linux/iommu.h:256
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/amd_iommu_init.c (ffffffff828fb726)
Location: include/linux/iommu.h:364
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816c3a91)
Location: include/linux/iommu.h:364
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
```
```
In drivers/iommu/intel-iommu.c (ffffffff828fe63e)
Location: include/linux/iommu.h:364
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/amd_iommu_init.c (ffffffff829045f0)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816e69e1)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
```
```
In drivers/iommu/intel-iommu.c (ffffffff8290769a)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
</details>
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
In drivers/iommu/arm-smmu.c (ffff8000108d259c)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d75e0)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d7f70)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108da9dc)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dc118)
Location: include/linux/iommu.h:379
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
In drivers/iommu/ipmmu-vmsa.c (c09c28b0)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_probe
```
```
In drivers/iommu/omap-iommu.c (c09c3adc)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_probe
```
```
In drivers/iommu/rockchip-iommu.c (c09c59f0)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/iommu/tegra-gart.c (c09c76ac)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/tegra-gart.c:tegra_gart_probe
```
```
In drivers/iommu/tegra-smmu.c (c09c8cd0)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
```
```
In drivers/iommu/exynos-iommu.c (c09ca3b0)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
```
```
In drivers/iommu/qcom_iommu.c (c09cbc44)
Location: include/linux/iommu.h:379
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828ebdd7)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816ac4c1)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
```
```
In drivers/iommu/intel-iommu.c (ffffffff828eee6b)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/amd_iommu_init.c (ffffffff828e3264)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff81689e21)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e630e)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/amd_iommu_init.c (ffffffff828ff913)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816da6a1)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
```
```
In drivers/iommu/intel-iommu.c (ffffffff829029bd)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
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
In drivers/iommu/amd_iommu_init.c (ffffffff82905652)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
```
In drivers/iommu/dmar.c (ffffffff816f4c51)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:alloc_iommu
```
```
In drivers/iommu/intel-iommu.c (ffffffff829086fc)
Location: include/linux/iommu.h:379
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
</details>
</li>
</ul>

## Differences
