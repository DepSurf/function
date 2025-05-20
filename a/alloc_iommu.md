# Function: <code>alloc_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066560)
Location: arch/x86/kernel/amd_gart_64.c:94
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In drivers/iommu/dmar.c (ffffffff81533f55)
Location: drivers/iommu/dmar.c:1000
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff81066560-ffffffff810666a6: alloc_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810662f0)
Location: arch/x86/kernel/amd_gart_64.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In drivers/iommu/dmar.c (ffffffff815887b8)
Location: drivers/iommu/dmar.c:1012
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff810662f0-ffffffff81066436: alloc_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069f80)
Location: arch/x86/kernel/amd_gart_64.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In drivers/iommu/dmar.c (ffffffff815b5e78)
Location: drivers/iommu/dmar.c:1013
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff81069f80-ffffffff8106a0c6: alloc_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810692e0)
Location: arch/x86/kernel/amd_gart_64.c:94
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In drivers/iommu/dmar.c (ffffffff815cbca6)
Location: drivers/iommu/dmar.c:1016
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff810692e0-ffffffff8106941d: alloc_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106db90)
Location: arch/x86/kernel/amd_gart_64.c:94
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In drivers/iommu/dmar.c (ffffffff81632a76)
Location: drivers/iommu/dmar.c:1019
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff8106db90-ffffffff8106dccd: alloc_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81070a90)
Location: arch/x86/kernel/amd_gart_64.c:95
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
```
In drivers/iommu/dmar.c (ffffffff8166dd09)
Location: drivers/iommu/dmar.c:1019
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff81070a90-ffffffff81070bcd: alloc_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81076a80)
Location: arch/x86/kernel/amd_gart_64.c:91
Inline: False
```
```
In drivers/iommu/dmar.c (ffffffff8168c139)
Location: drivers/iommu/dmar.c:1019
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff81076a80-ffffffff81076bbd: alloc_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a620)
Location: arch/x86/kernel/amd_gart_64.c:91
Inline: False
```
```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1008
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff8107a620-ffffffff8107a75d: alloc_iommu (STB_LOCAL)
ffffffff816c3790-ffffffff816c3b50: alloc_iommu (STB_LOCAL)
ffffffff816c5283-ffffffff816c534c: alloc_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b710)
Location: arch/x86/kernel/amd_gart_64.c:91
Inline: False
```
```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1018
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff8107b710-ffffffff8107b84d: alloc_iommu (STB_LOCAL)
ffffffff816e66e0-ffffffff816e6a88: alloc_iommu (STB_LOCAL)
ffffffff816e81ba-ffffffff816e8283: alloc_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81082de0)
Location: arch/x86/kernel/amd_gart_64.c:90
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1023
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff81082de0-ffffffff81082f16: alloc_iommu.isra.0 (STB_LOCAL)
ffffffff8179d110-ffffffff8179d31a: alloc_iommu (STB_LOCAL)
ffffffff8179ed97-ffffffff8179ee03: alloc_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81084320)
Location: arch/x86/kernel/amd_gart_64.c:91
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
```
```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1046
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff81084320-ffffffff81084477: alloc_iommu (STB_LOCAL)
ffffffff817aadf0-ffffffff817ab047: alloc_iommu (STB_LOCAL)
ffffffff81c0c1c2-ffffffff81c0c24b: alloc_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81085080)
Location: arch/x86/kernel/amd_gart_64.c:91
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
```
```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1053
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff81085080-ffffffff810851da: alloc_iommu (STB_LOCAL)
ffffffff8178d690-ffffffff8178d8e5: alloc_iommu (STB_LOCAL)
ffffffff81bfd9f9-ffffffff81bfda82: alloc_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81094530)
Location: arch/x86/kernel/amd_gart_64.c:91
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
```
```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1052
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff81094530-ffffffff8109468a: alloc_iommu (STB_LOCAL)
ffffffff81814f10-ffffffff81815165: alloc_iommu (STB_LOCAL)
ffffffff81cfefce-ffffffff81cff057: alloc_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810a6790)
Location: arch/x86/kernel/amd_gart_64.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
```
```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1048
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff810a6790-ffffffff810a68fc: alloc_iommu (STB_LOCAL)
ffffffff81956130-ffffffff819563a6: alloc_iommu (STB_LOCAL)
ffffffff81ec77c6-ffffffff81ec7852: alloc_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810bf8a0)
Location: arch/x86/kernel/amd_gart_64.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abce50)
Location: drivers/iommu/intel/dmar.c:1027
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff810bf8a0-ffffffff810bfa0c: alloc_iommu (STB_LOCAL)
ffffffff81abce50-ffffffff81abd18d: alloc_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810c2f80)
Location: arch/x86/kernel/amd_gart_64.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b09790)
Location: drivers/iommu/intel/dmar.c:1038
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff810c2f80-ffffffff810c30ec: alloc_iommu (STB_LOCAL)
ffffffff81b09790-ffffffff81b09b15: alloc_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810cb3c0)
Location: arch/x86/kernel/amd_gart_64.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:__dma_map_cont
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5d8a0)
Location: drivers/iommu/intel/dmar.c:1038
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff810cb3c0-ffffffff810cb52c: alloc_iommu (STB_LOCAL)
ffffffff81b5d8a0-ffffffff81b5dc54: alloc_iommu (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a710)
Location: arch/x86/kernel/amd_gart_64.c:91
Inline: False
```
```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1018
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff8107a710-ffffffff8107a84d: alloc_iommu (STB_LOCAL)
ffffffff816ac1c0-ffffffff816ac568: alloc_iommu (STB_LOCAL)
ffffffff816adc9a-ffffffff816add63: alloc_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Transformation ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069e40)
Location: arch/x86/kernel/amd_gart_64.c:91
Inline: False
```
```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1018
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff81069e40-ffffffff81069f7d: alloc_iommu (STB_LOCAL)
ffffffff81689b20-ffffffff81689ec8: alloc_iommu (STB_LOCAL)
ffffffff8168b5fa-ffffffff8168b6c3: alloc_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a6c0)
Location: arch/x86/kernel/amd_gart_64.c:91
Inline: False
```
```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1018
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff8107a6c0-ffffffff8107a7fd: alloc_iommu (STB_LOCAL)
ffffffff816da3a0-ffffffff816da748: alloc_iommu (STB_LOCAL)
ffffffff816dbe7a-ffffffff816dbf43: alloc_iommu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
long unsigned int alloc_iommu(struct device *dev, int size, long unsigned int align_mask);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107c7c0)
Location: arch/x86/kernel/amd_gart_64.c:91
Inline: False
```
```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1018
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
**Symbols:**

```
ffffffff8107c7c0-ffffffff8107c8fd: alloc_iommu (STB_LOCAL)
ffffffff816f4950-ffffffff816f4cf8: alloc_iommu (STB_LOCAL)
ffffffff816f644a-ffffffff816f6513: alloc_iommu.cold (STB_LOCAL)
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
