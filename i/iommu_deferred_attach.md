# Function: <code>iommu_deferred_attach</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_deferred_attach(struct device *dev, struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179f860)
Location: drivers/iommu/iommu.c:2004
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffffffff8179f860-ffffffff8179f8ae: iommu_deferred_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_deferred_attach(struct device *dev, struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81828850)
Location: drivers/iommu/iommu.c:2025
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffffffff81828850-ffffffff8182889e: iommu_deferred_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_deferred_attach(struct device *dev, struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff819687c0)
Location: drivers/iommu/iommu.c:2003
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffffffff819687c0-ffffffff81968825: iommu_deferred_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_deferred_attach(struct device *dev, struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ad2550)
Location: drivers/iommu/iommu.c:2044
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffffffff81ad2550-ffffffff81ad2596: iommu_deferred_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_deferred_attach(struct device *dev, struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b20d00)
Location: drivers/iommu/iommu.c:2029
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffffffff81b20d00-ffffffff81b20d46: iommu_deferred_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_deferred_attach(struct device *dev, struct iommu_domain *domain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b77930)
Location: drivers/iommu/iommu.c:2294
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
  - drivers/iommu/dma-iommu.c:__iommu_dma_map
```
**Symbols:**

```
ffffffff81b77930-ffffffff81b77976: iommu_deferred_attach (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
