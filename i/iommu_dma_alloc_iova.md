# Function: <code>iommu_dma_alloc_iova</code>

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
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain *domain, size_t size, u64 dma_limit, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81791bb0)
Location: drivers/iommu/dma-iommu.c:400
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_msi_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffffffff81791bb0-ffffffff81791c9c: iommu_dma_alloc_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain *domain, size_t size, u64 dma_limit, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817bdd30)
Location: drivers/iommu/dma-iommu.c:431
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_get_msi_page
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffffffff817bdd30-ffffffff817bde1c: iommu_dma_alloc_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain *domain, size_t size, u64 dma_limit, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a0f10)
Location: drivers/iommu/dma-iommu.c:417
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffffffff817a0f10-ffffffff817a1005: iommu_dma_alloc_iova (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain *domain, size_t size, u64 dma_limit, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:433
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffffffff81829f70-ffffffff8182a0e0: iommu_dma_alloc_iova (STB_LOCAL)
ffffffff81d01b63-ffffffff81d01c6d: iommu_dma_alloc_iova.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain *domain, size_t size, u64 dma_limit, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:614
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffffffff8196a4c0-ffffffff8196a636: iommu_dma_alloc_iova (STB_LOCAL)
ffffffff81eca03a-ffffffff81eca11b: iommu_dma_alloc_iova.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain *domain, size_t size, u64 dma_limit, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:625
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffffffff81ad4510-ffffffff81ad4686: iommu_dma_alloc_iova (STB_LOCAL)
ffffffff82097d35-ffffffff82097e16: iommu_dma_alloc_iova.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain *domain, size_t size, u64 dma_limit, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:658
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffffffff81b22ce0-ffffffff81b22e56: iommu_dma_alloc_iova (STB_LOCAL)
ffffffff82118d45-ffffffff82118e26: iommu_dma_alloc_iova.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain *domain, size_t size, u64 dma_limit, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:763
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffffffff81b79d00-ffffffff81b79e86: iommu_dma_alloc_iova (STB_LOCAL)
ffffffff821f6c91-ffffffff821f6d5a: iommu_dma_alloc_iova.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c9698)
Location: drivers/iommu/dma-iommu.c:384
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffff8000108c9698-ffff8000108c97d0: iommu_dma_alloc_iova.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
