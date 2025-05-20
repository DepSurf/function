# Function: <code>dma_direct_free</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8110cf60)
Location: kernel/dma/direct.c:126
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/swiotlb.c:swiotlb_free
```
**Symbols:**

```
ffffffff8110cf60-ffffffff8110cfbb: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118d90)
Location: kernel/dma/direct.c:204
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
ffffffff81118d90-ffffffff81118da0: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81123280)
Location: kernel/dma/direct.c:213
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
  - drivers/iommu/intel-iommu.c:intel_free_coherent
```
**Symbols:**

```
ffffffff81123280-ffffffff81123290: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112f6c0)
Location: kernel/dma/direct.c:213
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
  - drivers/iommu/intel-iommu.c:intel_free_coherent
```
**Symbols:**

```
ffffffff8112f6c0-ffffffff8112f6d0: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113e2b0)
Location: kernel/dma/direct.c:299
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
ffffffff8113e2b0-ffffffff8113e2c0: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81138ca0)
Location: kernel/dma/direct.c:244
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
ffffffff81138ca0-ffffffff81138dd7: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81139d80)
Location: kernel/dma/direct.c:244
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
ffffffff81139d80-ffffffff81139eb7: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:274
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
ffffffff81cb03dc-ffffffff81cb03fa: dma_direct_free.cold (STB_LOCAL)
ffffffff8115cde0-ffffffff8115cf13: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:322
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
ffffffff81e6105f-ffffffff81e61070: dma_direct_free.cold (STB_LOCAL)
ffffffff81186bc0-ffffffff81186d59: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c2660)
Location: kernel/dma/direct.c:322
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
ffffffff811c2660-ffffffff811c2805: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d51a0)
Location: kernel/dma/direct.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
ffffffff811d51a0-ffffffff811d5345: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811ea090)
Location: kernel/dma/direct.c:312
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_free_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
ffffffff811ea090-ffffffff811ea237: dma_direct_free (STB_GLOBAL)
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
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010195170)
Location: kernel/dma/direct.c:213
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
**Symbols:**

```
ffff800010195170-ffff800010195204: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c03e1e78)
Location: kernel/dma/direct.c:213
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
c03e1e78-c03e1ea4: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f54e0)
Location: kernel/dma/direct.c:213
Inline: False
Direct callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_free_coherent
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
c0000000001f54e0-c0000000001f54f4: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126ed4)
Location: kernel/dma/direct.c:213
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
**Symbols:**

```
ffffffe000126ed4-ffffffe000126f1e: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127d00)
Location: kernel/dma/direct.c:213
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
  - drivers/iommu/intel-iommu.c:intel_free_coherent
```
**Symbols:**

```
ffffffff81127d00-ffffffff81127d10: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8111a700)
Location: kernel/dma/direct.c:213
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
  - drivers/iommu/intel-iommu.c:intel_free_coherent
```
**Symbols:**

```
ffffffff8111a700-ffffffff8111a710: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81125b90)
Location: kernel/dma/direct.c:213
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
  - drivers/iommu/intel-iommu.c:intel_free_coherent
```
**Symbols:**

```
ffffffff81125b90-ffffffff81125ba0: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_direct_free(struct device *dev, size_t size, void *cpu_addr, dma_addr_t dma_addr, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811321d0)
Location: kernel/dma/direct.c:213
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_free_attrs
  - drivers/iommu/intel-iommu.c:intel_free_coherent
```
**Symbols:**

```
ffffffff811321d0-ffffffff811321e0: dma_direct_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
