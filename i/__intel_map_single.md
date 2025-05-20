# Function: <code>__intel_map_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
dma_addr_t __intel_map_single(struct device *dev, phys_addr_t paddr, size_t size, int dir, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8153ade0)
Location: drivers/iommu/intel-iommu.c:3424
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_map_page
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
**Symbols:**

```
ffffffff8153ade0-ffffffff8153af64: __intel_map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
dma_addr_t __intel_map_single(struct device *dev, phys_addr_t paddr, size_t size, int dir, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158f8b0)
Location: drivers/iommu/intel-iommu.c:3485
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_map_page
```
**Symbols:**

```
ffffffff8158f8b0-ffffffff8158fa3a: __intel_map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
dma_addr_t __intel_map_single(struct device *dev, phys_addr_t paddr, size_t size, int dir, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bd0f0)
Location: drivers/iommu/intel-iommu.c:3576
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_map_page
```
**Symbols:**

```
ffffffff815bd0f0-ffffffff815bd27a: __intel_map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
dma_addr_t __intel_map_single(struct device *dev, phys_addr_t paddr, size_t size, int dir, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d2d10)
Location: drivers/iommu/intel-iommu.c:3572
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_map_page
```
**Symbols:**

```
ffffffff815d2d10-ffffffff815d2ea2: __intel_map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
dma_addr_t __intel_map_single(struct device *dev, phys_addr_t paddr, size_t size, int dir, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81639a10)
Location: drivers/iommu/intel-iommu.c:3580
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_map_page
```
**Symbols:**

```
ffffffff81639a10-ffffffff81639ba2: __intel_map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
dma_addr_t __intel_map_single(struct device *dev, phys_addr_t paddr, size_t size, int dir, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:3636
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:intel_map_page
```
**Symbols:**

```
ffffffff81674bf0-ffffffff81674d1f: __intel_map_single (STB_LOCAL)
ffffffff8167581e-ffffffff8167583f: __intel_map_single.cold.99 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
dma_addr_t __intel_map_single(struct device *dev, phys_addr_t paddr, size_t size, int dir, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816caab0)
Location: drivers/iommu/intel-iommu.c:3491
Inline: False
```
**Symbols:**

```
ffffffff816caab0-ffffffff816cabe3: __intel_map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
dma_addr_t __intel_map_single(struct device *dev, phys_addr_t paddr, size_t size, int dir, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ee1c0)
Location: drivers/iommu/intel-iommu.c:3503
Inline: False
```
**Symbols:**

```
ffffffff816ee1c0-ffffffff816ee35e: __intel_map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
dma_addr_t __intel_map_single(struct device *dev, phys_addr_t paddr, size_t size, int dir, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a5f30)
Location: drivers/iommu/intel/iommu.c:3386
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_alloc_coherent
  - drivers/iommu/intel/iommu.c:intel_map_resource
  - drivers/iommu/intel/iommu.c:intel_map_page
```
**Symbols:**

```
ffffffff817a5f30-ffffffff817a613a: __intel_map_single (STB_LOCAL)
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
dma_addr_t __intel_map_single(struct device *dev, phys_addr_t paddr, size_t size, int dir, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b3930)
Location: drivers/iommu/intel-iommu.c:3503
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
**Symbols:**

```
ffffffff816b3930-ffffffff816b3ace: __intel_map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
dma_addr_t __intel_map_single(struct device *dev, phys_addr_t paddr, size_t size, int dir, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816915f0)
Location: drivers/iommu/intel-iommu.c:3503
Inline: False
```
**Symbols:**

```
ffffffff816915f0-ffffffff8169178e: __intel_map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
dma_addr_t __intel_map_single(struct device *dev, phys_addr_t paddr, size_t size, int dir, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e1e80)
Location: drivers/iommu/intel-iommu.c:3503
Inline: False
```
**Symbols:**

```
ffffffff816e1e80-ffffffff816e201e: __intel_map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
dma_addr_t __intel_map_single(struct device *dev, phys_addr_t paddr, size_t size, int dir, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fc4c0)
Location: drivers/iommu/intel-iommu.c:3503
Inline: False
```
**Symbols:**

```
ffffffff816fc4c0-ffffffff816fc677: __intel_map_single (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
