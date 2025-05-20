# Function: <code>iommu_put_dma_cookie</code>

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
void iommu_put_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81791880)
Location: drivers/iommu/dma-iommu.c:131
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
```
**Symbols:**

```
ffffffff81791880-ffffffff8179192e: iommu_put_dma_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_put_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817bda70)
Location: drivers/iommu/dma-iommu.c:153
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff817bda70-ffffffff817bdb1e: iommu_put_dma_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_put_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a0cb0)
Location: drivers/iommu/dma-iommu.c:157
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_free
  - drivers/iommu/intel/iommu.c:domain_exit
```
**Symbols:**

```
ffffffff817a0cb0-ffffffff817a0d5e: iommu_put_dma_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_put_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81829cb0)
Location: drivers/iommu/dma-iommu.c:157
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_group_release
```
**Symbols:**

```
ffffffff81829cb0-ffffffff81829d5e: iommu_put_dma_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iommu_put_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8196c950)
Location: drivers/iommu/dma-iommu.c:353
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_change_dev_def_domain
  - drivers/iommu/iommu.c:iommu_group_release
  - drivers/iommu/iommu.c:iommu_group_release
```
**Symbols:**

```
ffffffff8196c950-ffffffff8196cafd: iommu_put_dma_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_put_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad7050)
Location: drivers/iommu/dma-iommu.c:357
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_domain_free
```
**Symbols:**

```
ffffffff81ad7050-ffffffff81ad71f9: iommu_put_dma_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_put_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b25840)
Location: drivers/iommu/dma-iommu.c:358
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_domain_free
```
**Symbols:**

```
ffffffff81b25840-ffffffff81b259e9: iommu_put_dma_cookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_put_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b7c5b0)
Location: drivers/iommu/dma-iommu.c:439
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_domain_free
```
**Symbols:**

```
ffffffff81b7c5b0-ffffffff81b7c780: iommu_put_dma_cookie (STB_GLOBAL)
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
void iommu_put_dma_cookie(struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c8b88)
Location: drivers/iommu/dma-iommu.c:130
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_domain_free
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/qcom_iommu.c:qcom_iommu_domain_free
  - drivers/iommu/virtio-iommu.c:viommu_domain_free
```
**Symbols:**

```
ffff8000108c8b88-ffff8000108c8c38: iommu_put_dma_cookie (STB_GLOBAL)
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
Location: include/linux/dma-iommu.h:62
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (0)
Location: include/linux/dma-iommu.h:62
Inline: True
```
```
In drivers/iommu/exynos-iommu.c (0)
Location: include/linux/dma-iommu.h:62
Inline: True
```
```
In drivers/iommu/qcom_iommu.c (0)
Location: include/linux/dma-iommu.h:62
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
