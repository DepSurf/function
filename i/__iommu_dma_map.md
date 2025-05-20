# Function: <code>__iommu_dma_map</code>

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
dma_addr_t __iommu_dma_map(struct device *dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81791ca0)
Location: drivers/iommu/dma-iommu.c:478
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff81791ca0-ffffffff81791d74: __iommu_dma_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
dma_addr_t __iommu_dma_map(struct device *dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817bde20)
Location: drivers/iommu/dma-iommu.c:530
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
```
**Symbols:**

```
ffffffff817bde20-ffffffff817bdef6: __iommu_dma_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
dma_addr_t __iommu_dma_map(struct device *dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a1010)
Location: drivers/iommu/dma-iommu.c:513
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
```
**Symbols:**

```
ffffffff817a1010-ffffffff817a1100: __iommu_dma_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
dma_addr_t __iommu_dma_map(struct device *dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8182acb0)
Location: drivers/iommu/dma-iommu.c:530
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
```
**Symbols:**

```
ffffffff8182acb0-ffffffff8182ad9d: __iommu_dma_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
dma_addr_t __iommu_dma_map(struct device *dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8196b450)
Location: drivers/iommu/dma-iommu.c:686
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff8196b450-ffffffff8196b531: __iommu_dma_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
dma_addr_t __iommu_dma_map(struct device *dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad59e0)
Location: drivers/iommu/dma-iommu.c:697
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff81ad59e0-ffffffff81ad5ac1: __iommu_dma_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
dma_addr_t __iommu_dma_map(struct device *dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b24160)
Location: drivers/iommu/dma-iommu.c:730
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff81b24160-ffffffff81b2424a: __iommu_dma_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
dma_addr_t __iommu_dma_map(struct device *dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b7ad60)
Location: drivers/iommu/dma-iommu.c:849
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffffffff81b7ad60-ffffffff81b7ae4a: __iommu_dma_map (STB_LOCAL)
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
dma_addr_t __iommu_dma_map(struct device *dev, phys_addr_t phys, size_t size, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c97d0)
Location: drivers/iommu/dma-iommu.c:463
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_map_resource
  - drivers/iommu/dma-iommu.c:iommu_dma_map_page
```
**Symbols:**

```
ffff8000108c97d0-ffff8000108c98c4: __iommu_dma_map (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
