# Function: <code>bus_set_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152b2f0)
Location: drivers/iommu/iommu.c:1005
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8152b2f0-ffffffff8152b3e6: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157e940)
Location: drivers/iommu/iommu.c:993
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8157e940-ffffffff8157ea35: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815aaf70)
Location: drivers/iommu/iommu.c:1144
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff815aaf70-ffffffff815ab065: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c0b90)
Location: drivers/iommu/iommu.c:1194
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff815c0b90-ffffffff815c0c83: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81627320)
Location: drivers/iommu/iommu.c:1195
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81627320-ffffffff81627413: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81661f10)
Location: drivers/iommu/iommu.c:1196
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81661f10-ffffffff81662003: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167f3d0)
Location: drivers/iommu/iommu.c:1263
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8167f3d0-ffffffff8167f4c3: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b7400)
Location: drivers/iommu/iommu.c:1480
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816b7400-ffffffff816b74c4: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d9fb0)
Location: drivers/iommu/iommu.c:1536
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816d9fb0-ffffffff816da074: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817901c0)
Location: drivers/iommu/iommu.c:1818
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_init_api
  - drivers/iommu/amd/iommu.c:amd_iommu_init_api
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff817901c0-ffffffff8179029e: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bc540)
Location: drivers/iommu/iommu.c:1848
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_init_api
  - drivers/iommu/amd/iommu.c:amd_iommu_init_api
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff817bc540-ffffffff817bc61e: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179f780)
Location: drivers/iommu/iommu.c:1869
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_init_api
  - drivers/iommu/amd/iommu.c:amd_iommu_init_api
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8179f780-ffffffff8179f85e: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81828770)
Location: drivers/iommu/iommu.c:1884
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_init_api
  - drivers/iommu/amd/iommu.c:amd_iommu_init_api
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffffffff81828770-ffffffff8182884e: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff819686c0)
Location: drivers/iommu/iommu.c:1821
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_init_api
  - drivers/iommu/amd/iommu.c:amd_iommu_init_api
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffffffff819686c0-ffffffff819687bb: bus_set_iommu (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c5260)
Location: drivers/iommu/iommu.c:1536
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_remove
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
**Symbols:**

```
ffff8000108c5260-ffff8000108c5354: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bd268)
Location: drivers/iommu/iommu.c:1536
Inline: False
Direct callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_init
  - drivers/iommu/omap-iommu.c:omap_iommu_init
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/iommu/exynos-iommu.c:exynos_iommu_init
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_remove
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
```
**Symbols:**

```
c09bd268-c09bd340: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096c950)
Location: drivers/iommu/iommu.c:1536
Inline: False
```
**Symbols:**

```
c00000000096c950-c00000000096caa0: bus_set_iommu (STB_GLOBAL)
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
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169fa00)
Location: drivers/iommu/iommu.c:1536
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8169fa00-ffffffff8169fac4: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167d3f0)
Location: drivers/iommu/iommu.c:1536
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8167d3f0-ffffffff8167d4b4: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cdc70)
Location: drivers/iommu/iommu.c:1536
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816cdc70-ffffffff816cdd34: bus_set_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bus_set_iommu(struct bus_type *bus, const struct iommu_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e81b0)
Location: drivers/iommu/iommu.c:1536
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/amd_iommu.c:amd_iommu_init_api
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff816e81b0-ffffffff816e8274: bus_set_iommu (STB_GLOBAL)
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
