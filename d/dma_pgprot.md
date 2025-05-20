# Function: <code>dma_pgprot</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81122740)
Location: kernel/dma/mapping.c:158
Inline: True
```
**Symbols:**

```
ffffffff81122740-ffffffff8112274e: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8112ec70)
Location: kernel/dma/mapping.c:170
Inline: True
```
**Symbols:**

```
ffffffff8112ec70-ffffffff8112ec7e: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8113d708)
Location: kernel/dma/mapping.c:155
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
Direct callers:
  - kernel/dma/direct.c:dma_direct_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff8113d690-ffffffff8113d6bd: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811383a0)
Location: kernel/dma/mapping.c:345
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff811383a0-ffffffff811383cd: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811394c0)
Location: kernel/dma/mapping.c:347
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff811394c0-ffffffff811394ed: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115c350)
Location: kernel/dma/mapping.c:412
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffffffff8115c350-ffffffff8115c37d: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81186090)
Location: kernel/dma/mapping.c:408
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
**Symbols:**

```
ffffffff81186090-ffffffff811860a4: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c1a20)
Location: kernel/dma/mapping.c:415
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
**Symbols:**

```
ffffffff811c1a20-ffffffff811c1a34: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d4560)
Location: kernel/dma/mapping.c:419
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
**Symbols:**

```
ffffffff811d4560-ffffffff811d4574: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e9380)
Location: kernel/dma/mapping.c:419
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
**Symbols:**

```
ffffffff811e9380-ffffffff811e9394: dma_pgprot (STB_GLOBAL)
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
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffff800010194304)
Location: kernel/dma/mapping.c:170
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_common_mmap
Direct callers:
  - kernel/dma/remap.c:arch_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
**Symbols:**

```
ffff800010194240-ffff80001019428c: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c03e1514)
Location: kernel/dma/mapping.c:170
Inline: True
```
**Symbols:**

```
c03e1514-c03e1530: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c0000000001f4510)
Location: kernel/dma/mapping.c:170
Inline: True
```
**Symbols:**

```
c0000000001f4510-c0000000001f4520: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffe000126460)
Location: kernel/dma/mapping.c:170
Inline: True
```
**Symbols:**

```
ffffffe000126460-ffffffe000126482: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81127250)
Location: kernel/dma/mapping.c:170
Inline: True
```
**Symbols:**

```
ffffffff81127250-ffffffff8112725e: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81119cb0)
Location: kernel/dma/mapping.c:170
Inline: True
```
**Symbols:**

```
ffffffff81119cb0-ffffffff81119cbe: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81125140)
Location: kernel/dma/mapping.c:170
Inline: True
```
**Symbols:**

```
ffffffff81125140-ffffffff8112514e: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
pgprot_t dma_pgprot(struct device *dev, pgprot_t prot, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81131780)
Location: kernel/dma/mapping.c:170
Inline: True
```
**Symbols:**

```
ffffffff81131780-ffffffff8113178e: dma_pgprot (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
