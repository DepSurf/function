# Function: <code>iommu_fwspec_free</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815a9f20)
Location: drivers/iommu/iommu.c:1846
Inline: False
```
**Symbols:**

```
ffffffff815a9f20-ffffffff815a9f5d: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815bfba0)
Location: drivers/iommu/iommu.c:1913
Inline: False
```
**Symbols:**

```
ffffffff815bfba0-ffffffff815bfbdd: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81625f60)
Location: drivers/iommu/iommu.c:1936
Inline: False
```
**Symbols:**

```
ffffffff81625f60-ffffffff81625f9d: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81660e00)
Location: drivers/iommu/iommu.c:1942
Inline: False
```
**Symbols:**

```
ffffffff81660e00-ffffffff81660e3d: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167f4d0)
Location: drivers/iommu/iommu.c:1999
Inline: False
```
**Symbols:**

```
ffffffff8167f4d0-ffffffff8167f50d: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b6810)
Location: drivers/iommu/iommu.c:2234
Inline: False
```
**Symbols:**

```
ffffffff816b6810-ffffffff816b684d: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816d9510)
Location: drivers/iommu/iommu.c:2312
Inline: False
```
**Symbols:**

```
ffffffff816d9510-ffffffff816d954d: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178f3e8)
Location: drivers/iommu/iommu.c:2615
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
```
**Symbols:**

```
ffffffff8178d940-ffffffff8178d98b: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817bc098)
Location: drivers/iommu/iommu.c:2838
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
```
**Symbols:**

```
ffffffff817b96b0-ffffffff817b96fb: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179f258)
Location: drivers/iommu/iommu.c:2822
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
```
**Symbols:**

```
ffffffff8179c8c0-ffffffff8179c90b: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81824970)
Location: drivers/iommu/iommu.c:2907
Inline: False
```
**Symbols:**

```
ffffffff81824970-ffffffff818249bb: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81964900)
Location: drivers/iommu/iommu.c:2684
Inline: False
```
**Symbols:**

```
ffffffff81964900-ffffffff8196495b: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81acd9d0)
Location: drivers/iommu/iommu.c:2746
Inline: False
```
**Symbols:**

```
ffffffff81acd9d0-ffffffff81acda2b: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1c420)
Location: drivers/iommu/iommu.c:2752
Inline: False
```
**Symbols:**

```
ffffffff81b1c420-ffffffff81b1c47b: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b727a0)
Location: drivers/iommu/iommu.c:3028
Inline: False
```
**Symbols:**

```
ffffffff81b727a0-ffffffff81b727fb: iommu_fwspec_free (STB_GLOBAL)
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
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c4d30)
Location: drivers/iommu/iommu.c:2312
Inline: False
Direct callers:
  - drivers/iommu/of_iommu.c:of_iommu_configure
  - drivers/iommu/arm-smmu.c:arm_smmu_remove_device
  - drivers/iommu/arm-smmu.c:arm_smmu_add_device
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_remove_device
  - drivers/iommu/qcom_iommu.c:qcom_iommu_remove_device
```
**Symbols:**

```
ffff8000108c4d30-ffff8000108c4d70: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bc108)
Location: drivers/iommu/iommu.c:2312
Inline: False
Direct callers:
  - drivers/iommu/of_iommu.c:of_iommu_configure
  - drivers/iommu/tegra-smmu.c:tegra_smmu_add_device
  - drivers/iommu/qcom_iommu.c:qcom_iommu_remove_device
```
**Symbols:**

```
c09bc108-c09bc148: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096aca0)
Location: drivers/iommu/iommu.c:2312
Inline: False
Direct callers:
  - drivers/iommu/of_iommu.c:of_iommu_configure
```
**Symbols:**

```
c00000000096aca0-c00000000096ad0c: iommu_fwspec_free (STB_GLOBAL)
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
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8169ef60)
Location: drivers/iommu/iommu.c:2312
Inline: False
```
**Symbols:**

```
ffffffff8169ef60-ffffffff8169ef9d: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167c950)
Location: drivers/iommu/iommu.c:2312
Inline: False
```
**Symbols:**

```
ffffffff8167c950-ffffffff8167c98d: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cd1d0)
Location: drivers/iommu/iommu.c:2312
Inline: False
```
**Symbols:**

```
ffffffff816cd1d0-ffffffff816cd20d: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iommu_fwspec_free(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e76b0)
Location: drivers/iommu/iommu.c:2312
Inline: False
```
**Symbols:**

```
ffffffff816e76b0-ffffffff816e76ed: iommu_fwspec_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
