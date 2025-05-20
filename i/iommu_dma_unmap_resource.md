# Function: <code>iommu_dma_unmap_resource</code>

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
void iommu_dma_unmap_resource(struct device *dev, dma_addr_t handle, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:941
Inline: False
```
**Symbols:**

```
ffffffff81792790-ffffffff817927a0: iommu_dma_unmap_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_dma_unmap_resource(struct device *dev, dma_addr_t handle, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817bdcc0)
Location: drivers/iommu/dma-iommu.c:1085
Inline: False
```
**Symbols:**

```
ffffffff817bdcc0-ffffffff817bdcd0: iommu_dma_unmap_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_dma_unmap_resource(struct device *dev, dma_addr_t handle, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a0f00)
Location: drivers/iommu/dma-iommu.c:1105
Inline: False
```
**Symbols:**

```
ffffffff817a0f00-ffffffff817a0f10: iommu_dma_unmap_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_dma_unmap_resource(struct device *dev, dma_addr_t handle, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8182aa70)
Location: drivers/iommu/dma-iommu.c:1122
Inline: False
```
**Symbols:**

```
ffffffff8182aa70-ffffffff8182aa80: iommu_dma_unmap_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iommu_dma_unmap_resource(struct device *dev, dma_addr_t handle, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8196b1c0)
Location: drivers/iommu/dma-iommu.c:1281
Inline: False
```
**Symbols:**

```
ffffffff8196b1c0-ffffffff8196b1da: iommu_dma_unmap_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_dma_unmap_resource(struct device *dev, dma_addr_t handle, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad56c0)
Location: drivers/iommu/dma-iommu.c:1358
Inline: False
```
**Symbols:**

```
ffffffff81ad56c0-ffffffff81ad56da: iommu_dma_unmap_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_dma_unmap_resource(struct device *dev, dma_addr_t handle, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b23e70)
Location: drivers/iommu/dma-iommu.c:1402
Inline: False
```
**Symbols:**

```
ffffffff81b23e70-ffffffff81b23e8a: iommu_dma_unmap_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_dma_unmap_resource(struct device *dev, dma_addr_t handle, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b7aa30)
Location: drivers/iommu/dma-iommu.c:1523
Inline: False
```
**Symbols:**

```
ffffffff81b7aa30-ffffffff81b7aa4a: iommu_dma_unmap_resource (STB_LOCAL)
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
void iommu_dma_unmap_resource(struct device *dev, dma_addr_t handle, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c8e80)
Location: drivers/iommu/dma-iommu.c:916
Inline: False
```
**Symbols:**

```
ffff8000108c8e80-ffff8000108c8ec4: iommu_dma_unmap_resource (STB_LOCAL)
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
