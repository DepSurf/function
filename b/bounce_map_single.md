# Function: <code>bounce_map_single</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
dma_addr_t bounce_map_single(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ede00)
Location: drivers/iommu/intel-iommu.c:3818
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:bounce_map_resource
```
**Symbols:**

```
ffffffff816ede00-ffffffff816ee090: bounce_map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
dma_addr_t bounce_map_single(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a5a60)
Location: drivers/iommu/intel/iommu.c:3688
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:bounce_map_sg
  - drivers/iommu/intel/iommu.c:bounce_map_resource
```
**Symbols:**

```
ffffffff817a5a60-ffffffff817a5d4e: bounce_map_single (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
dma_addr_t bounce_map_single(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b3570)
Location: drivers/iommu/intel-iommu.c:3818
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:bounce_map_resource
```
**Symbols:**

```
ffffffff816b3570-ffffffff816b3800: bounce_map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
dma_addr_t bounce_map_single(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81691230)
Location: drivers/iommu/intel-iommu.c:3818
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:bounce_map_resource
```
**Symbols:**

```
ffffffff81691230-ffffffff816914c0: bounce_map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
dma_addr_t bounce_map_single(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e1ac0)
Location: drivers/iommu/intel-iommu.c:3818
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:bounce_map_resource
```
**Symbols:**

```
ffffffff816e1ac0-ffffffff816e1d50: bounce_map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
dma_addr_t bounce_map_single(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fc0e0)
Location: drivers/iommu/intel-iommu.c:3818
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_map_sg
  - drivers/iommu/intel-iommu.c:bounce_map_resource
```
**Symbols:**

```
ffffffff816fc0e0-ffffffff816fc38c: bounce_map_single (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
