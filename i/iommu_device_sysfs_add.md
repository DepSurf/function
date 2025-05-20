# Function: <code>iommu_device_sysfs_add</code>

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
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff815c2660)
Location: drivers/iommu/iommu-sysfs.c:57
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff815c2660-ffffffff815c2774: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81628e40)
Location: drivers/iommu/iommu-sysfs.c:57
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81628e40-ffffffff81628f54: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81663b70)
Location: drivers/iommu/iommu-sysfs.c:57
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81663b70-ffffffff81663c7d: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81682160)
Location: drivers/iommu/iommu-sysfs.c:57
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81682160-ffffffff8168226d: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff816b98b0)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816b98b0-ffffffff816b99b7: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff816dc6a0)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816dc6a0-ffffffff816dc7a7: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81791700)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81791700-ffffffff81791807: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff817bd930)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff817bd930-ffffffff817bda37: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff817a0b70)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff817a0b70-ffffffff817a0c77: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81829b70)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffffffff81829b70-ffffffff81829c77: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81969e30)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffffffff81969e30-ffffffff81969f63: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81ad3e80)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffffffff81ad3e80-ffffffff81ad3fb3: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81b22650)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffffffff81b22650-ffffffff81b22783: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81b79080)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/intel/dmar.c:alloc_iommu
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffffffff81b79080-ffffffff81b791e2: iommu_device_sysfs_add (STB_GLOBAL)
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
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffff8000108c8790)
Location: drivers/iommu/iommu-sysfs.c:54
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
ffff8000108c8790-ffff8000108c88b4: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (c09bf73c)
Location: drivers/iommu/iommu-sysfs.c:54
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
c09bf73c-c09bf834: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (c00000000096fec0)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
```
**Symbols:**

```
c00000000096fec0-c00000000096fff8: iommu_device_sysfs_add (STB_GLOBAL)
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
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff816a20f0)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816a20f0-ffffffff816a21f7: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff8167fae0)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8167fae0-ffffffff8167fbe7: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff816d0360)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816d0360-ffffffff816d0467: iommu_device_sysfs_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_device_sysfs_add(struct iommu_device *iommu, struct device *parent, const struct attribute_group **groups, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff816ea8f0)
Location: drivers/iommu/iommu-sysfs.c:54
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816ea8f0-ffffffff816ea9f7: iommu_device_sysfs_add (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
