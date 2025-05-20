# Function: <code>iommu_group_get_for_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152b900)
Location: drivers/iommu/iommu.c:826
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff8152b900-ffffffff8152b9fc: iommu_group_get_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157ed30)
Location: drivers/iommu/iommu.c:813
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff8157ed30-ffffffff8157ee42: iommu_group_get_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815ab760)
Location: drivers/iommu/iommu.c:964
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff815ab760-ffffffff815ab872: iommu_group_get_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c13b0)
Location: drivers/iommu/iommu.c:998
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff815c13b0-ffffffff815c1549: iommu_group_get_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81627b50)
Location: drivers/iommu/iommu.c:1000
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff81627b50-ffffffff81627cec: iommu_group_get_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81662730)
Location: drivers/iommu/iommu.c:1001
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff81662730-ffffffff816628c2: iommu_group_get_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81680900)
Location: drivers/iommu/iommu.c:1079
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_request_dm_for_dev
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff81680900-ffffffff81680b10: iommu_group_get_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1297
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816b8a46-ffffffff816b8a84: iommu_group_get_for_dev.cold (STB_LOCAL)
ffffffff816b8170-ffffffff816b835a: iommu_group_get_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1353
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816db841-ffffffff816db87f: iommu_group_get_for_dev.cold (STB_LOCAL)
ffffffff816daed0-ffffffff816db0b7: iommu_group_get_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178f145)
Location: drivers/iommu/iommu.c:1514
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
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
In drivers/iommu/iommu.c (ffffffff817bb345)
Location: drivers/iommu/iommu.c:1548
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
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
In drivers/iommu/iommu.c (ffffffff8179e775)
Location: drivers/iommu/iommu.c:1569
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
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
In drivers/iommu/iommu.c (ffffffff81826615)
Location: drivers/iommu/iommu.c:1584
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
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
In drivers/iommu/iommu.c (ffffffff81966ea8)
Location: drivers/iommu/iommu.c:1558
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad1af7)
Location: drivers/iommu/iommu.c:1679
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1f5f4)
Location: drivers/iommu/iommu.c:1677
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:__iommu_probe_device
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c6e18)
Location: drivers/iommu/iommu.c:1353
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_add_device
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_add_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_add_device
  - drivers/iommu/qcom_iommu.c:qcom_iommu_add_device
  - drivers/iommu/virtio-iommu.c:viommu_add_device
```
**Symbols:**

```
ffff8000108c6e18-ffff8000108c7008: iommu_group_get_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bddf0)
Location: drivers/iommu/iommu.c:1353
Inline: False
Direct callers:
  - drivers/iommu/omap-iommu.c:_omap_iommu_add_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_add_device
  - drivers/iommu/tegra-gart.c:gart_iommu_add_device
  - drivers/iommu/tegra-smmu.c:tegra_smmu_add_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_add_device
  - drivers/iommu/qcom_iommu.c:qcom_iommu_add_device
```
**Symbols:**

```
c09bddf0-c09be010: iommu_group_get_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096e0c0)
Location: drivers/iommu/iommu.c:1353
Inline: False
```
**Symbols:**

```
c00000000096e0c0-c00000000096e3c8: iommu_group_get_for_dev (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1353
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816a1291-ffffffff816a12cf: iommu_group_get_for_dev.cold (STB_LOCAL)
ffffffff816a0920-ffffffff816a0b07: iommu_group_get_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1353
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff8167ec81-ffffffff8167ecbf: iommu_group_get_for_dev.cold (STB_LOCAL)
ffffffff8167e310-ffffffff8167e4f7: iommu_group_get_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1353
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816cf501-ffffffff816cf53f: iommu_group_get_for_dev.cold (STB_LOCAL)
ffffffff816ceb90-ffffffff816ced77: iommu_group_get_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct iommu_group *iommu_group_get_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1353
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816e9a88-ffffffff816e9ac6: iommu_group_get_for_dev.cold (STB_LOCAL)
ffffffff816e9100-ffffffff816e92e7: iommu_group_get_for_dev (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
