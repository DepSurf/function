# Function: <code>iommu_device_register</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c11c0)
Location: drivers/iommu/iommu.c:91
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff815c11c0-ffffffff815c1208: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81627960)
Location: drivers/iommu/iommu.c:91
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81627960-ffffffff816279a8: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81662530)
Location: drivers/iommu/iommu.c:91
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81662530-ffffffff81662578: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81680560)
Location: drivers/iommu/iommu.c:98
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81680560-ffffffff816805a8: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b7d30)
Location: drivers/iommu/iommu.c:83
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816b7d30-ffffffff816b7d78: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816daa90)
Location: drivers/iommu/iommu.c:137
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816daa90-ffffffff816daad8: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178e1e0)
Location: drivers/iommu/iommu.c:153
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8178e1e0-ffffffff8178e22b: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b9f50)
Location: drivers/iommu/iommu.c:155
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff817b9f50-ffffffff817b9f9b: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu, const struct iommu_ops *ops, struct device *hwdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179cef0)
Location: drivers/iommu/iommu.c:153
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8179cef0-ffffffff8179cf7f: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu, const struct iommu_ops *ops, struct device *hwdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81825bc0)
Location: drivers/iommu/iommu.c:165
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffffffff81825bc0-ffffffff81825c4f: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu, const struct iommu_ops *ops, struct device *hwdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff819647a0)
Location: drivers/iommu/iommu.c:167
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffffffff819647a0-ffffffff81964841: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu, const struct iommu_ops *ops, struct device *hwdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad2410)
Location: drivers/iommu/iommu.c:213
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffffffff81ad2410-ffffffff81ad253a: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu, const struct iommu_ops *ops, struct device *hwdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b20bc0)
Location: drivers/iommu/iommu.c:245
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffffffff81b20bc0-ffffffff81b20cea: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu, const struct iommu_ops *ops, struct device *hwdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b77810)
Location: drivers/iommu/iommu.c:252
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffffffff81b77810-ffffffff81b77919: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c68a0)
Location: drivers/iommu/iommu.c:137
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffff8000108c68a0-ffff8000108c6948: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bd950)
Location: drivers/iommu/iommu.c:137
Inline: False
Direct callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_probe
  - drivers/iommu/omap-iommu.c:omap_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/tegra-gart.c:tegra_gart_probe
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
```
**Symbols:**

```
c09bd950-c09bd9b4: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096d310)
Location: drivers/iommu/iommu.c:137
Inline: False
```
**Symbols:**

```
c00000000096d310-c00000000096d3f0: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a04e0)
Location: drivers/iommu/iommu.c:137
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816a04e0-ffffffff816a0528: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167ded0)
Location: drivers/iommu/iommu.c:137
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8167ded0-ffffffff8167df18: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816ce750)
Location: drivers/iommu/iommu.c:137
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816ce750-ffffffff816ce798: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_device_register(struct iommu_device *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e8cc0)
Location: drivers/iommu/iommu.c:137
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816e8cc0-ffffffff816e8d06: iommu_device_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct iommu_ops *ops</code>
</li>
<li>
<b>Param added. </b>
<code>struct device *hwdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
