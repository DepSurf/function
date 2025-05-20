# Function: <code>iommu_device_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iommu_device_unlink(struct device *dev, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff8152cc90)
Location: drivers/iommu/iommu-sysfs.c:127
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
```
**Symbols:**

```
ffffffff8152cc90-ffffffff8152cce7: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iommu_device_unlink(struct device *dev, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff815800b0)
Location: drivers/iommu/iommu-sysfs.c:127
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
```
**Symbols:**

```
ffffffff815800b0-ffffffff81580107: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_device_unlink(struct device *dev, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff815acc40)
Location: drivers/iommu/iommu-sysfs.c:127
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
```
**Symbols:**

```
ffffffff815acc40-ffffffff815acc97: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff815c2880)
Location: drivers/iommu/iommu-sysfs.c:126
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
```
**Symbols:**

```
ffffffff815c2880-ffffffff815c28dc: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81629060)
Location: drivers/iommu/iommu-sysfs.c:126
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
```
**Symbols:**

```
ffffffff81629060-ffffffff816290bc: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81663d70)
Location: drivers/iommu/iommu-sysfs.c:126
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
```
**Symbols:**

```
ffffffff81663d70-ffffffff81663dc9: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81682360)
Location: drivers/iommu/iommu-sysfs.c:126
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
```
**Symbols:**

```
ffffffff81682360-ffffffff816823b9: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff816b9aa0)
Location: drivers/iommu/iommu-sysfs.c:123
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
```
**Symbols:**

```
ffffffff816b9aa0-ffffffff816b9af5: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff816dc890)
Location: drivers/iommu/iommu-sysfs.c:123
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816dc890-ffffffff816dc8e5: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff817916a0)
Location: drivers/iommu/iommu-sysfs.c:127
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_release_device
```
**Symbols:**

```
ffffffff817916a0-ffffffff817916f5: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff817bd8d0)
Location: drivers/iommu/iommu-sysfs.c:127
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_release_device
```
**Symbols:**

```
ffffffff817bd8d0-ffffffff817bd925: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff817a0b10)
Location: drivers/iommu/iommu-sysfs.c:127
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_release_device
```
**Symbols:**

```
ffffffff817a0b10-ffffffff817a0b65: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81829b10)
Location: drivers/iommu/iommu-sysfs.c:127
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_release_device
```
**Symbols:**

```
ffffffff81829b10-ffffffff81829b65: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81969dc0)
Location: drivers/iommu/iommu-sysfs.c:127
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_release_device
```
**Symbols:**

```
ffffffff81969dc0-ffffffff81969e29: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81ad3e00)
Location: drivers/iommu/iommu-sysfs.c:127
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_release_device
```
**Symbols:**

```
ffffffff81ad3e00-ffffffff81ad3e69: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81b225d0)
Location: drivers/iommu/iommu-sysfs.c:127
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_release_device
```
**Symbols:**

```
ffffffff81b225d0-ffffffff81b22639: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff81b792c0)
Location: drivers/iommu/iommu-sysfs.c:123
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_deinit_device
  - drivers/iommu/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff81b792c0-ffffffff81b7930d: iommu_device_unlink (STB_GLOBAL)
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
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffff8000108c89e0)
Location: drivers/iommu/iommu-sysfs.c:123
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_remove_device
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_remove_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_remove_device
  - drivers/iommu/qcom_iommu.c:qcom_iommu_remove_device
  - drivers/iommu/virtio-iommu.c:viommu_remove_device
  - drivers/iommu/virtio-iommu.c:viommu_add_device
```
**Symbols:**

```
ffff8000108c89e0-ffff8000108c8a44: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (c09bf90c)
Location: drivers/iommu/iommu-sysfs.c:123
Inline: False
Direct callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_remove_device
  - drivers/iommu/omap-iommu.c:omap_iommu_remove_device
  - drivers/iommu/omap-iommu.c:_omap_iommu_add_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_remove_device
  - drivers/iommu/tegra-gart.c:gart_iommu_remove_device
  - drivers/iommu/tegra-smmu.c:tegra_smmu_remove_device
  - drivers/iommu/qcom_iommu.c:qcom_iommu_remove_device
```
**Symbols:**

```
c09bf90c-c09bf964: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (c0000000009701c0)
Location: drivers/iommu/iommu-sysfs.c:123
Inline: False
```
**Symbols:**

```
c0000000009701c0-c000000000970258: iommu_device_unlink (STB_GLOBAL)
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
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff816a22e0)
Location: drivers/iommu/iommu-sysfs.c:123
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816a22e0-ffffffff816a2335: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff8167fcd0)
Location: drivers/iommu/iommu-sysfs.c:123
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff8167fcd0-ffffffff8167fd25: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff816d0550)
Location: drivers/iommu/iommu-sysfs.c:123
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816d0550-ffffffff816d05a5: iommu_device_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iommu_device_unlink(struct iommu_device *iommu, struct device *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu-sysfs.c (ffffffff816eaae0)
Location: drivers/iommu/iommu-sysfs.c:123
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816eaae0-ffffffff816eab35: iommu_device_unlink (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iommu_device *iommu</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
</ul>
</details>
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
