# Function: <code>iommu_dma_init_domain</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81792ac6)
Location: drivers/iommu/dma-iommu.c:302
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int iommu_dma_init_domain(struct iommu_domain *domain, dma_addr_t base, u64 size, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:329
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
```
**Symbols:**

```
ffffffff817bed30-ffffffff817beec8: iommu_dma_init_domain (STB_LOCAL)
ffffffff81c0d6e6-ffffffff81c0d723: iommu_dma_init_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int iommu_dma_init_domain(struct iommu_domain *domain, dma_addr_t base, u64 size, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:332
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
```
**Symbols:**

```
ffffffff817a1b60-ffffffff817a1cc9: iommu_dma_init_domain (STB_LOCAL)
ffffffff81bffa4f-ffffffff81bffa8c: iommu_dma_init_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iommu_dma_init_domain(struct iommu_domain *domain, dma_addr_t base, dma_addr_t limit, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:356
Inline: False
```
**Symbols:**

```
ffffffff8182b600-ffffffff8182b77b: iommu_dma_init_domain (STB_LOCAL)
ffffffff81d01e5f-ffffffff81d01f56: iommu_dma_init_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iommu_dma_init_domain(struct iommu_domain *domain, dma_addr_t base, dma_addr_t limit, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:533
Inline: False
```
**Symbols:**

```
ffffffff8196c6c0-ffffffff8196c847: iommu_dma_init_domain (STB_LOCAL)
ffffffff81eca38f-ffffffff81eca463: iommu_dma_init_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int iommu_dma_init_domain(struct iommu_domain *domain, dma_addr_t base, dma_addr_t limit, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:537
Inline: False
```
**Symbols:**

```
ffffffff81ad6d40-ffffffff81ad6ecb: iommu_dma_init_domain (STB_LOCAL)
ffffffff82098030-ffffffff820980e0: iommu_dma_init_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int iommu_dma_init_domain(struct iommu_domain *domain, dma_addr_t base, dma_addr_t limit, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:569
Inline: False
```
**Symbols:**

```
ffffffff81b25510-ffffffff81b256b4: iommu_dma_init_domain (STB_LOCAL)
ffffffff8211901f-ffffffff821190cf: iommu_dma_init_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iommu_dma_init_domain(struct iommu_domain *domain, dma_addr_t base, dma_addr_t limit, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:672
Inline: False
```
**Symbols:**

```
ffffffff81b7c200-ffffffff81b7c3fb: iommu_dma_init_domain (STB_LOCAL)
ffffffff821f6ffb-ffffffff821f70ab: iommu_dma_init_domain.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108ca6ac)
Location: drivers/iommu/dma-iommu.c:301
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>dma_addr_t limit</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 size</code>
</li>
</ul>
</details>
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
