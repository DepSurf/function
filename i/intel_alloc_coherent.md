# Function: <code>intel_alloc_coherent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *intel_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, struct dma_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8153afb0)
Location: drivers/iommu/intel-iommu.c:3631
Inline: False
```
**Symbols:**

```
ffffffff8153afb0-ffffffff8153b0cb: intel_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *intel_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158fa80)
Location: drivers/iommu/intel-iommu.c:3719
Inline: False
```
**Symbols:**

```
ffffffff8158fa80-ffffffff8158fb94: intel_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *intel_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bd2c0)
Location: drivers/iommu/intel-iommu.c:3810
Inline: False
```
**Symbols:**

```
ffffffff815bd2c0-ffffffff815bd3f2: intel_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *intel_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d2ef0)
Location: drivers/iommu/intel-iommu.c:3802
Inline: False
```
**Symbols:**

```
ffffffff815d2ef0-ffffffff815d3020: intel_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *intel_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81639bf0)
Location: drivers/iommu/intel-iommu.c:3707
Inline: False
```
**Symbols:**

```
ffffffff81639bf0-ffffffff81639d20: intel_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *intel_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81674d60)
Location: drivers/iommu/intel-iommu.c:3755
Inline: False
```
**Symbols:**

```
ffffffff81674d60-ffffffff81674e9d: intel_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *intel_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81693390)
Location: drivers/iommu/intel-iommu.c:3772
Inline: False
```
**Symbols:**

```
ffffffff81693390-ffffffff816934ad: intel_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *intel_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816cb7b0)
Location: drivers/iommu/intel-iommu.c:3630
Inline: True
```
**Symbols:**

```
ffffffff816cb7b0-ffffffff816cb8c8: intel_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *intel_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eeb50)
Location: drivers/iommu/intel-iommu.c:3644
Inline: True
```
**Symbols:**

```
ffffffff816eeb50-ffffffff816eec68: intel_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *intel_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a61a0)
Location: drivers/iommu/intel/iommu.c:3521
Inline: False
```
**Symbols:**

```
ffffffff817a61a0-ffffffff817a62b2: intel_alloc_coherent (STB_LOCAL)
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
void *intel_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b42e0)
Location: drivers/iommu/intel-iommu.c:3644
Inline: False
```
**Symbols:**

```
ffffffff816b42e0-ffffffff816b4459: intel_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *intel_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81691f80)
Location: drivers/iommu/intel-iommu.c:3644
Inline: True
```
**Symbols:**

```
ffffffff81691f80-ffffffff81692098: intel_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *intel_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e2810)
Location: drivers/iommu/intel-iommu.c:3644
Inline: True
```
**Symbols:**

```
ffffffff816e2810-ffffffff816e2928: intel_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *intel_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_handle, gfp_t flags, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fce70)
Location: drivers/iommu/intel-iommu.c:3644
Inline: True
```
**Symbols:**

```
ffffffff816fce70-ffffffff816fcf88: intel_alloc_coherent (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct dma_attrs *attrs</code> ➡️ <code>long unsigned int attrs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
