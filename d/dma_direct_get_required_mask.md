# Function: <code>dma_direct_get_required_mask</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118990)
Location: kernel/dma/direct.c:54
Inline: False
```
**Symbols:**

```
ffffffff81118990-ffffffff81118a1b: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81122e10)
Location: kernel/dma/direct.c:46
Inline: False
```
**Symbols:**

```
ffffffff81122e10-ffffffff81122e70: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112f250)
Location: kernel/dma/direct.c:46
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
  - drivers/iommu/intel-iommu.c:intel_get_required_mask
  - drivers/iommu/intel-iommu.c:iommu_need_mapping
```
**Symbols:**

```
ffffffff8112f250-ffffffff8112f2b0: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113dfd0)
Location: kernel/dma/direct.c:40
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
```
**Symbols:**

```
ffffffff8113dfd0-ffffffff8113e030: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81138930)
Location: kernel/dma/direct.c:39
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
```
**Symbols:**

```
ffffffff81138930-ffffffff811389f9: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81139a10)
Location: kernel/dma/direct.c:39
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
```
**Symbols:**

```
ffffffff81139a10-ffffffff81139ad9: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:39
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
```
**Symbols:**

```
ffffffff81cb039e-ffffffff81cb03bd: dma_direct_get_required_mask.cold (STB_LOCAL)
ffffffff8115ca50-ffffffff8115cb2a: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:39
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
```
**Symbols:**

```
ffffffff81e61040-ffffffff81e6105f: dma_direct_get_required_mask.cold (STB_LOCAL)
ffffffff81186840-ffffffff81186926: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:39
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
```
**Symbols:**

```
ffffffff8205a7c5-ffffffff8205a7e4: dma_direct_get_required_mask.cold (STB_LOCAL)
ffffffff811c22c0-ffffffff811c23a6: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:39
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
```
**Symbols:**

```
ffffffff820d9039-ffffffff820d9058: dma_direct_get_required_mask.cold (STB_LOCAL)
ffffffff811d4e00-ffffffff811d4ee6: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:39
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_addressing_limited
```
**Symbols:**

```
ffffffff821b47e6-ffffffff821b4805: dma_direct_get_required_mask.cold (STB_LOCAL)
ffffffff811e9cf0-ffffffff811e9ddc: dma_direct_get_required_mask (STB_GLOBAL)
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
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010194ca0)
Location: kernel/dma/direct.c:46
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
```
**Symbols:**

```
ffff800010194ca0-ffff800010194cf8: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c03e19dc)
Location: kernel/dma/direct.c:46
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
```
**Symbols:**

```
c03e19dc-c03e1a50: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f4fc0)
Location: kernel/dma/direct.c:46
Inline: False
Direct callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_get_required_mask
  - kernel/dma/mapping.c:dma_get_required_mask
```
**Symbols:**

```
c0000000001f4fc0-c0000000001f5010: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126b5e)
Location: kernel/dma/direct.c:46
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
```
**Symbols:**

```
ffffffe000126b5e-ffffffe000126bd6: dma_direct_get_required_mask (STB_GLOBAL)
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
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811278c0)
Location: kernel/dma/direct.c:46
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
  - drivers/iommu/intel-iommu.c:intel_get_required_mask
  - drivers/iommu/intel-iommu.c:iommu_need_mapping
```
**Symbols:**

```
ffffffff811278c0-ffffffff81127920: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8111a290)
Location: kernel/dma/direct.c:46
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
  - drivers/iommu/intel-iommu.c:intel_get_required_mask
  - drivers/iommu/intel-iommu.c:iommu_need_mapping
```
**Symbols:**

```
ffffffff8111a290-ffffffff8111a2f0: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81125720)
Location: kernel/dma/direct.c:46
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
  - drivers/iommu/intel-iommu.c:intel_get_required_mask
  - drivers/iommu/intel-iommu.c:iommu_need_mapping
```
**Symbols:**

```
ffffffff81125720-ffffffff81125780: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 dma_direct_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81131d60)
Location: kernel/dma/direct.c:46
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_get_required_mask
  - drivers/iommu/intel-iommu.c:intel_get_required_mask
  - drivers/iommu/intel-iommu.c:iommu_need_mapping
```
**Symbols:**

```
ffffffff81131d60-ffffffff81131dc0: dma_direct_get_required_mask (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
