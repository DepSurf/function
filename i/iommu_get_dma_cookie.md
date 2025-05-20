# Function: <code>iommu_get_dma_cookie</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_get_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81792900)
Location: drivers/iommu/dma-iommu.c:79
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff81792900-ffffffff8179296b: iommu_get_dma_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_get_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817bf160)
Location: drivers/iommu/dma-iommu.c:101
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff817bf160-ffffffff817bf1cb: iommu_get_dma_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_get_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a1d50)
Location: drivers/iommu/dma-iommu.c:105
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc
```
**Symbols:**

```
ffffffff817a1d50-ffffffff817a1dbb: iommu_get_dma_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_get_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8182a2d0)
Location: drivers/iommu/dma-iommu.c:105
Inline: False
```
**Symbols:**

```
ffffffff8182a2d0-ffffffff8182a33b: iommu_get_dma_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_get_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8196c8d0)
Location: drivers/iommu/dma-iommu.c:304
Inline: False
```
**Symbols:**

```
ffffffff8196c8d0-ffffffff8196c94d: iommu_get_dma_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_get_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad6fa0)
Location: drivers/iommu/dma-iommu.c:307
Inline: False
```
**Symbols:**

```
ffffffff81ad6fa0-ffffffff81ad7037: iommu_get_dma_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_get_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b25790)
Location: drivers/iommu/dma-iommu.c:308
Inline: False
```
**Symbols:**

```
ffffffff81b25790-ffffffff81b25827: iommu_get_dma_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_get_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b7c4d0)
Location: drivers/iommu/dma-iommu.c:389
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:__iommu_domain_alloc
```
**Symbols:**

```
ffffffff81b7c4d0-ffffffff81b7c59a: iommu_get_dma_cookie (STB_GLOBAL)
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
int iommu_get_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c8ad0)
Location: drivers/iommu/dma-iommu.c:78
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_domain_alloc
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_domain_alloc
  - drivers/iommu/qcom_iommu.c:qcom_iommu_domain_alloc
  - drivers/iommu/virtio-iommu.c:viommu_domain_alloc
```
**Symbols:**

```
ffff8000108c8ad0-ffff8000108c8b18: iommu_get_dma_cookie (STB_GLOBAL)
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
In drivers/iommu/ipmmu-vmsa.c (0)
Location: include/linux/dma-iommu.h:52
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (0)
Location: include/linux/dma-iommu.h:52
Inline: True
```
```
In drivers/iommu/exynos-iommu.c (0)
Location: include/linux/dma-iommu.h:52
Inline: True
```
```
In drivers/iommu/qcom_iommu.c (0)
Location: include/linux/dma-iommu.h:52
Inline: True
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
<b>Regular</b>
<ul>
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
</ul>
