# Function: <code>iova_reserve_iommu_regions</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817925f0)
Location: drivers/iommu/dma-iommu.c:238
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
```
**Symbols:**

```
ffffffff817925f0-ffffffff8179278d: iova_reserve_iommu_regions.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817beb90)
Location: drivers/iommu/dma-iommu.c:260
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff817beb90-ffffffff817bed2d: iova_reserve_iommu_regions.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:266
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff817a18e0-ffffffff817a1b53: iova_reserve_iommu_regions.isra.0 (STB_LOCAL)
ffffffff81bffa2c-ffffffff81bffa4f: iova_reserve_iommu_regions.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:266
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff8182a5a0-ffffffff8182a76e: iova_reserve_iommu_regions.isra.0 (STB_LOCAL)
ffffffff81d01d2d-ffffffff81d01daa: iova_reserve_iommu_regions.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:473
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff8196a9b0-ffffffff8196ab8a: iova_reserve_iommu_regions.isra.0 (STB_LOCAL)
ffffffff81eca1eb-ffffffff81eca258: iova_reserve_iommu_regions.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:477
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff81ad5040-ffffffff81ad521a: iova_reserve_iommu_regions.isra.0 (STB_LOCAL)
ffffffff82097ebd-ffffffff82097f2a: iova_reserve_iommu_regions.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:480
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff81b237f0-ffffffff81b239ca: iova_reserve_iommu_regions.isra.0 (STB_LOCAL)
ffffffff82118ecd-ffffffff82118f3a: iova_reserve_iommu_regions.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:561
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init_domain
```
**Symbols:**

```
ffffffff81b7a570-ffffffff81b7a77d: iova_reserve_iommu_regions.isra.0 (STB_LOCAL)
ffffffff821f6e71-ffffffff821f6ede: iova_reserve_iommu_regions.isra.0.cold (STB_LOCAL)
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
In drivers/iommu/dma-iommu.c (ffff8000108ca75c)
Location: drivers/iommu/dma-iommu.c:237
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
