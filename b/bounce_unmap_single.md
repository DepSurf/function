# Function: <code>bounce_unmap_single</code>

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
void bounce_unmap_single(struct device *dev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816edc60)
Location: drivers/iommu/intel-iommu.c:3905
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
  - drivers/iommu/intel-iommu.c:bounce_unmap_resource
```
**Symbols:**

```
ffffffff816edc60-ffffffff816edd6d: bounce_unmap_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bounce_unmap_single(struct device *dev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a40e0)
Location: drivers/iommu/intel/iommu.c:3779
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:bounce_map_sg
```
**Symbols:**

```
ffffffff817a40e0-ffffffff817a4215: bounce_unmap_single (STB_LOCAL)
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
void bounce_unmap_single(struct device *dev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b33d0)
Location: drivers/iommu/intel-iommu.c:3905
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
  - drivers/iommu/intel-iommu.c:bounce_unmap_resource
```
**Symbols:**

```
ffffffff816b33d0-ffffffff816b34dd: bounce_unmap_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bounce_unmap_single(struct device *dev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81691090)
Location: drivers/iommu/intel-iommu.c:3905
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
  - drivers/iommu/intel-iommu.c:bounce_unmap_resource
```
**Symbols:**

```
ffffffff81691090-ffffffff8169119d: bounce_unmap_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bounce_unmap_single(struct device *dev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e1920)
Location: drivers/iommu/intel-iommu.c:3905
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
  - drivers/iommu/intel-iommu.c:bounce_unmap_resource
```
**Symbols:**

```
ffffffff816e1920-ffffffff816e1a2d: bounce_unmap_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bounce_unmap_single(struct device *dev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fbf30)
Location: drivers/iommu/intel-iommu.c:3905
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_unmap_sg
  - drivers/iommu/intel-iommu.c:bounce_unmap_resource
```
**Symbols:**

```
ffffffff816fbf30-ffffffff816fc045: bounce_unmap_single (STB_LOCAL)
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
