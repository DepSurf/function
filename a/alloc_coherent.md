# Function: <code>alloc_coherent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, struct dma_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81531230)
Location: drivers/iommu/amd_iommu.c:2645
Inline: False
```
**Symbols:**

```
ffffffff81531230-ffffffff815313f5: alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81584d60)
Location: drivers/iommu/amd_iommu.c:2549
Inline: False
```
**Symbols:**

```
ffffffff81584d60-ffffffff81584ed0: alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b1e40)
Location: drivers/iommu/amd_iommu.c:2642
Inline: False
```
**Symbols:**

```
ffffffff815b1e40-ffffffff815b1fc4: alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c7ad0)
Location: drivers/iommu/amd_iommu.c:2803
Inline: False
```
**Symbols:**

```
ffffffff815c7ad0-ffffffff815c7c61: alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162e7a0)
Location: drivers/iommu/amd_iommu.c:2584
Inline: False
```
**Symbols:**

```
ffffffff8162e7a0-ffffffff8162e931: alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81669480)
Location: drivers/iommu/amd_iommu.c:2594
Inline: False
```
**Symbols:**

```
ffffffff81669480-ffffffff81669600: alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81687ce0)
Location: drivers/iommu/amd_iommu.c:2675
Inline: False
```
**Symbols:**

```
ffffffff81687ce0-ffffffff81687e5c: alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816c0aa0)
Location: drivers/iommu/amd_iommu.c:2656
Inline: False
```
**Symbols:**

```
ffffffff816c0aa0-ffffffff816c0c0f: alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e3ad0)
Location: drivers/iommu/amd_iommu.c:2688
Inline: False
```
**Symbols:**

```
ffffffff816e3ad0-ffffffff816e3c3f: alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
void *alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a9470)
Location: drivers/iommu/amd_iommu.c:2688
Inline: False
```
**Symbols:**

```
ffffffff816a9470-ffffffff816a9648: alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81686f10)
Location: drivers/iommu/amd_iommu.c:2688
Inline: False
```
**Symbols:**

```
ffffffff81686f10-ffffffff8168707f: alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d7790)
Location: drivers/iommu/amd_iommu.c:2688
Inline: False
```
**Symbols:**

```
ffffffff816d7790-ffffffff816d78ff: alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816f1d40)
Location: drivers/iommu/amd_iommu.c:2688
Inline: False
```
**Symbols:**

```
ffffffff816f1d40-ffffffff816f1eaf: alloc_coherent (STB_LOCAL)
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
