# Function: <code>alloc_iova_fast</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81580f20)
Location: drivers/iommu/iova.c:402
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
```
**Symbols:**

```
ffffffff81580f20-ffffffff8158110d: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815adae0)
Location: drivers/iommu/iova.c:402
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
```
**Symbols:**

```
ffffffff815adae0-ffffffff815adcd9: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff815c3750)
Location: drivers/iommu/iova.c:378
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
```
**Symbols:**

```
ffffffff815c3750-ffffffff815c3957: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8162a400)
Location: drivers/iommu/iova.c:404
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
```
**Symbols:**

```
ffffffff8162a400-ffffffff8162a63c: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81665110)
Location: drivers/iommu/iova.c:404
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
```
**Symbols:**

```
ffffffff81665110-ffffffff81665349: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81683710)
Location: drivers/iommu/iova.c:413
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
```
**Symbols:**

```
ffffffff81683710-ffffffff81683949: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816bb020)
Location: drivers/iommu/iova.c:412
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
```
**Symbols:**

```
ffffffff816bb020-ffffffff816bb0bc: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816dde80)
Location: drivers/iommu/iova.c:412
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
```
**Symbols:**

```
ffffffff816dde80-ffffffff816ddf1c: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff81794b50)
Location: drivers/iommu/iova.c:412
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/intel/iommu.c:intel_alloc_iova
  - drivers/iommu/intel/iommu.c:intel_alloc_iova
```
**Symbols:**

```
ffffffff81794b50-ffffffff81794bec: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817c1150)
Location: drivers/iommu/iova.c:426
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
```
**Symbols:**

```
ffffffff817c1150-ffffffff817c1259: alloc_iova_fast.part.0 (STB_LOCAL)
ffffffff817c1260-ffffffff817c12e4: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff817a3d20)
Location: drivers/iommu/iova.c:493
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
```
**Symbols:**

```
ffffffff817a3d20-ffffffff817a3fd0: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff8182d650)
Location: drivers/iommu/iova.c:493
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
```
**Symbols:**

```
ffffffff8182d650-ffffffff8182d9cc: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:434
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
```
**Symbols:**

```
ffffffff81eca5c6-ffffffff81eca5df: alloc_iova_fast.cold (STB_LOCAL)
ffffffff8196e3b0-ffffffff8196e6e3: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:439
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
```
**Symbols:**

```
ffffffff82098141-ffffffff8209815a: alloc_iova_fast.cold (STB_LOCAL)
ffffffff81ad8d40-ffffffff81ad9050: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:439
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
```
**Symbols:**

```
ffffffff82119130-ffffffff82119157: alloc_iova_fast.cold (STB_LOCAL)
ffffffff81b26ce0-ffffffff81b27103: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iova.c (0)
Location: drivers/iommu/iova.c:440
Inline: False
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova
```
**Symbols:**

```
ffffffff821f710c-ffffffff821f7135: alloc_iova_fast.cold (STB_LOCAL)
ffffffff81b7dde0-ffffffff81b7e1aa: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffff8000108ce488)
Location: drivers/iommu/iova.c:412
Inline: True
```
**Symbols:**

```
ffff8000108ce488-ffff8000108ce54c: alloc_iova_fast (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816a38d0)
Location: drivers/iommu/iova.c:412
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
```
**Symbols:**

```
ffffffff816a38d0-ffffffff816a396c: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816812c0)
Location: drivers/iommu/iova.c:412
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
```
**Symbols:**

```
ffffffff816812c0-ffffffff8168135c: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816d1b40)
Location: drivers/iommu/iova.c:412
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
```
**Symbols:**

```
ffffffff816d1b40-ffffffff816d1bdc: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iova_fast(struct iova_domain *iovad, long unsigned int size, long unsigned int limit_pfn, bool flush_rcache);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iova.c (ffffffff816ec100)
Location: drivers/iommu/iova.c:412
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
  - drivers/iommu/intel-iommu.c:intel_alloc_iova
```
**Symbols:**

```
ffffffff816ec100-ffffffff816ec19c: alloc_iova_fast (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool flush_rcache</code>
</li>
</ul>
</details>
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
