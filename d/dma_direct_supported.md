# Function: <code>dma_direct_supported</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8110d0a0)
Location: kernel/dma/direct.c:167
Inline: True
```
**Symbols:**

```
ffffffff8110d0a0-ffffffff8110d0d3: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118da0)
Location: kernel/dma/direct.c:365
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_supported
```
**Symbols:**

```
ffffffff81118da0-ffffffff81118de0: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81123290)
Location: kernel/dma/direct.c:393
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_supported
```
**Symbols:**

```
ffffffff81123290-ffffffff811232d0: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112f6d0)
Location: kernel/dma/direct.c:393
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_supported
```
**Symbols:**

```
ffffffff8112f6d0-ffffffff8112f710: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113e440)
Location: kernel/dma/direct.c:516
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff8113e440-ffffffff8113e49e: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811397f0)
Location: kernel/dma/direct.c:472
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff811397f0-ffffffff81139886: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113a8c0)
Location: kernel/dma/direct.c:472
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff8113a8c0-ffffffff8113a955: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:514
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff81cb0480-ffffffff81cb049e: dma_direct_supported.cold (STB_LOCAL)
ffffffff8115d7e0-ffffffff8115d890: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:548
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff81e610c9-ffffffff81e610e7: dma_direct_supported.cold (STB_LOCAL)
ffffffff81187750-ffffffff81187818: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:579
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff8205a801-ffffffff8205a81f: dma_direct_supported.cold (STB_LOCAL)
ffffffff811c3340-ffffffff811c3408: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:578
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff820d9075-ffffffff820d9093: dma_direct_supported.cold (STB_LOCAL)
ffffffff811d5e90-ffffffff811d5f58: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:567
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_set_coherent_mask
  - kernel/dma/mapping.c:dma_set_mask
```
**Symbols:**

```
ffffffff821b48b6-ffffffff821b48d4: dma_direct_supported.cold (STB_LOCAL)
ffffffff811eae20-ffffffff811eaeeb: dma_direct_supported (STB_GLOBAL)
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
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010195208)
Location: kernel/dma/direct.c:393
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_supported
```
**Symbols:**

```
ffff800010195208-ffff80001019525c: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c03e1ea4)
Location: kernel/dma/direct.c:393
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_supported
```
**Symbols:**

```
c03e1ea4-c03e1efc: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f5500)
Location: kernel/dma/direct.c:393
Inline: False
Direct callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_sg_for_device
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_sg_for_cpu
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_for_device
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_for_cpu
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_free_coherent
  - kernel/dma/mapping.c:dma_supported
```
**Symbols:**

```
c0000000001f5500-c0000000001f5560: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126f1e)
Location: kernel/dma/direct.c:393
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_supported
```
**Symbols:**

```
ffffffe000126f1e-ffffffe000126f6c: dma_direct_supported (STB_GLOBAL)
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
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127d10)
Location: kernel/dma/direct.c:393
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_supported
```
**Symbols:**

```
ffffffff81127d10-ffffffff81127d50: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8111a710)
Location: kernel/dma/direct.c:393
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_supported
```
**Symbols:**

```
ffffffff8111a710-ffffffff8111a750: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81125ba0)
Location: kernel/dma/direct.c:393
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_supported
```
**Symbols:**

```
ffffffff81125ba0-ffffffff81125be0: dma_direct_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dma_direct_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811321e0)
Location: kernel/dma/direct.c:393
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_supported
```
**Symbols:**

```
ffffffff811321e0-ffffffff81132220: dma_direct_supported (STB_GLOBAL)
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
