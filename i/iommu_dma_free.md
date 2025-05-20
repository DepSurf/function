# Function: <code>iommu_dma_free</code>

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
void iommu_dma_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81792060)
Location: drivers/iommu/dma-iommu.c:978
Inline: False
```
**Symbols:**

```
ffffffff81792060-ffffffff8179208f: iommu_dma_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_dma_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817bea10)
Location: drivers/iommu/dma-iommu.c:1122
Inline: False
```
**Symbols:**

```
ffffffff817bea10-ffffffff817bea3f: iommu_dma_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_dma_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a18b0)
Location: drivers/iommu/dma-iommu.c:1142
Inline: False
```
**Symbols:**

```
ffffffff817a18b0-ffffffff817a18df: iommu_dma_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_dma_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8182ac80)
Location: drivers/iommu/dma-iommu.c:1159
Inline: False
```
**Symbols:**

```
ffffffff8182ac80-ffffffff8182acaf: iommu_dma_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iommu_dma_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8196be20)
Location: drivers/iommu/dma-iommu.c:1318
Inline: False
```
**Symbols:**

```
ffffffff8196be20-ffffffff8196be59: iommu_dma_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_dma_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad6b50)
Location: drivers/iommu/dma-iommu.c:1395
Inline: False
```
**Symbols:**

```
ffffffff81ad6b50-ffffffff81ad6b89: iommu_dma_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_dma_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b25320)
Location: drivers/iommu/dma-iommu.c:1439
Inline: False
```
**Symbols:**

```
ffffffff81b25320-ffffffff81b25359: iommu_dma_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_dma_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b7bfb0)
Location: drivers/iommu/dma-iommu.c:1560
Inline: False
```
**Symbols:**

```
ffffffff81b7bfb0-ffffffff81b7bfe9: iommu_dma_free (STB_LOCAL)
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
void iommu_dma_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t handle, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c9168)
Location: drivers/iommu/dma-iommu.c:953
Inline: False
```
**Symbols:**

```
ffff8000108c9168-ffff8000108c91c0: iommu_dma_free (STB_LOCAL)
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
