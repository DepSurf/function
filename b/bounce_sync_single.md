# Function: <code>bounce_sync_single</code>

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
void bounce_sync_single(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ed920)
Location: drivers/iommu/intel-iommu.c:3802
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu
  - drivers/iommu/intel-iommu.c:bounce_sync_single_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_single_for_cpu
```
**Symbols:**

```
ffffffff816ed920-ffffffff816ed998: bounce_sync_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bounce_sync_single(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a2ff0)
Location: drivers/iommu/intel/iommu.c:3672
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:bounce_sync_sg_for_device
  - drivers/iommu/intel/iommu.c:bounce_sync_sg_for_cpu
  - drivers/iommu/intel/iommu.c:bounce_sync_single_for_device
  - drivers/iommu/intel/iommu.c:bounce_sync_single_for_cpu
```
**Symbols:**

```
ffffffff817a2ff0-ffffffff817a307c: bounce_sync_single (STB_LOCAL)
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
void bounce_sync_single(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b3090)
Location: drivers/iommu/intel-iommu.c:3802
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu
  - drivers/iommu/intel-iommu.c:bounce_sync_single_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_single_for_cpu
```
**Symbols:**

```
ffffffff816b3090-ffffffff816b3108: bounce_sync_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bounce_sync_single(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81690d50)
Location: drivers/iommu/intel-iommu.c:3802
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu
  - drivers/iommu/intel-iommu.c:bounce_sync_single_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_single_for_cpu
```
**Symbols:**

```
ffffffff81690d50-ffffffff81690dc8: bounce_sync_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bounce_sync_single(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e15e0)
Location: drivers/iommu/intel-iommu.c:3802
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu
  - drivers/iommu/intel-iommu.c:bounce_sync_single_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_single_for_cpu
```
**Symbols:**

```
ffffffff816e15e0-ffffffff816e1658: bounce_sync_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bounce_sync_single(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, enum dma_sync_target target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fbbf0)
Location: drivers/iommu/intel-iommu.c:3802
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_sg_for_cpu
  - drivers/iommu/intel-iommu.c:bounce_sync_single_for_device
  - drivers/iommu/intel-iommu.c:bounce_sync_single_for_cpu
```
**Symbols:**

```
ffffffff816fbbf0-ffffffff816fbc68: bounce_sync_single (STB_LOCAL)
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
