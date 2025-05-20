# Function: <code>iommu_request_dma_domain_for_dev</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iommu_request_dma_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b87b0)
Location: drivers/iommu/iommu.c:2194
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816b87b0-ffffffff816b87c5: iommu_request_dma_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_request_dma_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816db5d0)
Location: drivers/iommu/iommu.c:2250
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816db5d0-ffffffff816db5e5: iommu_request_dma_domain_for_dev (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int iommu_request_dma_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c75d8)
Location: drivers/iommu/iommu.c:2250
Inline: False
```
**Symbols:**

```
ffff8000108c75d8-ffff8000108c7608: iommu_request_dma_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_request_dma_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09be56c)
Location: drivers/iommu/iommu.c:2250
Inline: False
```
**Symbols:**

```
c09be56c-c09be58c: iommu_request_dma_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_request_dma_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096e580)
Location: drivers/iommu/iommu.c:2250
Inline: False
```
**Symbols:**

```
c00000000096e580-c00000000096e598: iommu_request_dma_domain_for_dev (STB_GLOBAL)
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
int iommu_request_dma_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a1020)
Location: drivers/iommu/iommu.c:2250
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816a1020-ffffffff816a1035: iommu_request_dma_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_request_dma_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167ea10)
Location: drivers/iommu/iommu.c:2250
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff8167ea10-ffffffff8167ea25: iommu_request_dma_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_request_dma_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cf290)
Location: drivers/iommu/iommu.c:2250
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816cf290-ffffffff816cf2a5: iommu_request_dma_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_request_dma_domain_for_dev(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e9800)
Location: drivers/iommu/iommu.c:2250
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
**Symbols:**

```
ffffffff816e9800-ffffffff816e9815: iommu_request_dma_domain_for_dev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
