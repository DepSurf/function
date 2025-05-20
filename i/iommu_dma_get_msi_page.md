# Function: <code>iommu_dma_get_msi_page</code>

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
struct iommu_dma_msi_page *iommu_dma_get_msi_page(struct device *dev, phys_addr_t msi_addr, struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817927a0)
Location: drivers/iommu/dma-iommu.c:1165
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
```
**Symbols:**

```
ffffffff817927a0-ffffffff81792900: iommu_dma_get_msi_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct iommu_dma_msi_page *iommu_dma_get_msi_page(struct device *dev, phys_addr_t msi_addr, struct iommu_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817beed0)
Location: drivers/iommu/dma-iommu.c:1343
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
```
**Symbols:**

```
ffffffff817beed0-ffffffff817bf032: iommu_dma_get_msi_page (STB_LOCAL)
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
In drivers/iommu/dma-iommu.c (ffffffff817a259b)
Location: drivers/iommu/dma-iommu.c:1337
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
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
In drivers/iommu/dma-iommu.c (ffffffff8182b88b)
Location: drivers/iommu/dma-iommu.c:1355
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
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
In drivers/iommu/dma-iommu.c (ffffffff8196cb4c)
Location: drivers/iommu/dma-iommu.c:1512
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
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
In drivers/iommu/dma-iommu.c (ffffffff81ad725c)
Location: drivers/iommu/dma-iommu.c:1596
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
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
In drivers/iommu/dma-iommu.c (ffffffff81b25a4b)
Location: drivers/iommu/dma-iommu.c:1640
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b7c7db)
Location: drivers/iommu/dma-iommu.c:1761
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
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
In drivers/iommu/dma-iommu.c (ffff8000108caa88)
Location: drivers/iommu/dma-iommu.c:1138
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
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
</ul>
