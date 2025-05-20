# Function: <code>dma_get_required_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154d7a0)
Location: drivers/base/platform.c:1124
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_should_identity_map
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
```
**Symbols:**

```
ffffffff8154d7a0-ffffffff8154d7f6: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8159f5b0)
Location: drivers/base/platform.c:1144
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:iommu_should_identity_map
```
**Symbols:**

```
ffffffff8159f5b0-ffffffff8159f606: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815cdbb0)
Location: drivers/base/platform.c:1158
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:iommu_should_identity_map
```
**Symbols:**

```
ffffffff815cdbb0-ffffffff815cdc06: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e25e0)
Location: drivers/base/platform.c:1165
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:iommu_should_identity_map
```
**Symbols:**

```
ffffffff815e25e0-ffffffff815e2636: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81649780)
Location: drivers/base/platform.c:1167
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:iommu_should_identity_map
```
**Symbols:**

```
ffffffff81649780-ffffffff816497d6: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81684d40)
Location: drivers/base/platform.c:1183
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:iommu_should_identity_map
```
**Symbols:**

```
ffffffff81684d40-ffffffff81684d96: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81118100)
Location: kernel/dma/mapping.c:230
Inline: True
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_alloc_coherent
  - drivers/iommu/intel-iommu.c:iommu_should_identity_map
```
**Symbols:**

```
ffffffff81118100-ffffffff8111818d: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81122480)
Location: kernel/dma/mapping.c:255
Inline: True
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
  - drivers/iommu/intel-iommu.c:iommu_need_mapping
```
**Symbols:**

```
ffffffff81122480-ffffffff81122508: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8112e7c0)
Location: kernel/dma/mapping.c:274
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff8112e7c0-ffffffff8112e800: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8113d150)
Location: kernel/dma/mapping.c:245
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff8113d150-ffffffff8113d190: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137830)
Location: kernel/dma/mapping.c:404
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff81137830-ffffffff81137872: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138620)
Location: kernel/dma/mapping.c:406
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff81138620-ffffffff81138662: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115b470)
Location: kernel/dma/mapping.c:471
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff8115b470-ffffffff8115b4b2: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81184e60)
Location: kernel/dma/mapping.c:465
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff81184e60-ffffffff81184eb4: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c0570)
Location: kernel/dma/mapping.c:472
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff811c0570-ffffffff811c05c4: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d3050)
Location: kernel/dma/mapping.c:476
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff811d3050-ffffffff811d30a4: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e9309)
Location: kernel/dma/mapping.c:476
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_addressing_limited
```
**Symbols:**

```
ffffffff811e7cd0-ffffffff811e7d24: dma_get_required_mask (STB_GLOBAL)
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
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffff800010193a80)
Location: kernel/dma/mapping.c:274
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffff800010193a80-ffff800010193ad4: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c03e0dcc)
Location: kernel/dma/mapping.c:274
Inline: False
```
**Symbols:**

```
c03e0dcc-c03e0e2c: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (c0000000001f3c90)
Location: kernel/dma/mapping.c:274
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
c0000000001f3c90-c0000000001f3d24: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffe000125e8e)
Location: kernel/dma/mapping.c:274
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffe000125e8e-ffffffe000125ed4: dma_get_required_mask (STB_GLOBAL)
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
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81126da0)
Location: kernel/dma/mapping.c:274
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff81126da0-ffffffff81126de0: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81119800)
Location: kernel/dma/mapping.c:274
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff81119800-ffffffff81119840: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81124c90)
Location: kernel/dma/mapping.c:274
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff81124c90-ffffffff81124cd0: dma_get_required_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 dma_get_required_mask(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811312d0)
Location: kernel/dma/mapping.c:274
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_max_mapping_size
```
**Symbols:**

```
ffffffff811312d0-ffffffff81131310: dma_get_required_mask (STB_GLOBAL)
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
