# Function: <code>dma_map_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
dma_addr_t dma_map_area(struct device *dev, dma_addr_t phys_mem, size_t size, int dir, long unsigned int align_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066ae0)
Location: arch/x86/kernel/amd_gart_64.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff81066ae0-ffffffff81066c09: dma_map_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
dma_addr_t dma_map_area(struct device *dev, dma_addr_t phys_mem, size_t size, int dir, long unsigned int align_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066870)
Location: arch/x86/kernel/amd_gart_64.c:213
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff81066870-ffffffff81066997: dma_map_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
dma_addr_t dma_map_area(struct device *dev, dma_addr_t phys_mem, size_t size, int dir, long unsigned int align_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a4f0)
Location: arch/x86/kernel/amd_gart_64.c:213
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff8106a4f0-ffffffff8106a617: dma_map_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
dma_addr_t dma_map_area(struct device *dev, dma_addr_t phys_mem, size_t size, int dir, long unsigned int align_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069870)
Location: arch/x86/kernel/amd_gart_64.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff81069870-ffffffff81069994: dma_map_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
dma_addr_t dma_map_area(struct device *dev, dma_addr_t phys_mem, size_t size, int dir, long unsigned int align_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106e120)
Location: arch/x86/kernel/amd_gart_64.c:214
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff8106e120-ffffffff8106e244: dma_map_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
dma_addr_t dma_map_area(struct device *dev, dma_addr_t phys_mem, size_t size, int dir, long unsigned int align_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff81071000-ffffffff81071128: dma_map_area (STB_LOCAL)
ffffffff810716c6-ffffffff810716d5: dma_map_area.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:200
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff81076fb0-ffffffff8107710d: dma_map_area.isra.9 (STB_LOCAL)
ffffffff810776ee-ffffffff810776fd: dma_map_area.isra.9.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:200
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff8107ab50-ffffffff8107ac81: dma_map_area.isra.0 (STB_LOCAL)
ffffffff8107b386-ffffffff8107b3bd: dma_map_area.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:200
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff8107bc40-ffffffff8107bd71: dma_map_area.isra.0 (STB_LOCAL)
ffffffff8107c476-ffffffff8107c4ad: dma_map_area.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:199
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff81083060-ffffffff8108318b: dma_map_area.constprop.0 (STB_LOCAL)
ffffffff81083a72-ffffffff81083aa1: dma_map_area.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:199
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:dma_map_sg_nonforce
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff81084850-ffffffff81084975: dma_map_area.constprop.0 (STB_LOCAL)
ffffffff81bd861e-ffffffff81bd864d: dma_map_area.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:199
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff810855b0-ffffffff810856d8: dma_map_area.constprop.0 (STB_LOCAL)
ffffffff81bca4b7-ffffffff81bca4e6: dma_map_area.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:199
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff810947d0-ffffffff810948f8: dma_map_area.constprop.0 (STB_LOCAL)
ffffffff81c9f924-ffffffff81c9f953: dma_map_area.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:197
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff810a6a50-ffffffff810a6b91: dma_map_area.constprop.0 (STB_LOCAL)
ffffffff81e4f168-ffffffff81e4f19b: dma_map_area.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810bfb80)
Location: arch/x86/kernel/amd_gart_64.c:197
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff810bfb80-ffffffff810bfd09: dma_map_area.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810c3260)
Location: arch/x86/kernel/amd_gart_64.c:197
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff810c3260-ffffffff810c33e9: dma_map_area.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810cb6a0)
Location: arch/x86/kernel/amd_gart_64.c:197
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff810cb6a0-ffffffff810cb829: dma_map_area.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:200
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff8107ac40-ffffffff8107ad71: dma_map_area.isra.0 (STB_LOCAL)
ffffffff8107b476-ffffffff8107b4ad: dma_map_area.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:200
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff8106a370-ffffffff8106a4a1: dma_map_area.isra.0 (STB_LOCAL)
ffffffff8106aba6-ffffffff8106abdd: dma_map_area.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:200
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff8107abf0-ffffffff8107ad21: dma_map_area.isra.0 (STB_LOCAL)
ffffffff8107b426-ffffffff8107b45d: dma_map_area.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:200
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent
  - arch/x86/kernel/amd_gart_64.c:gart_map_page
```
**Symbols:**

```
ffffffff8107ccf0-ffffffff8107ce21: dma_map_area.isra.0 (STB_LOCAL)
ffffffff8107d526-ffffffff8107d55d: dma_map_area.isra.0.cold (STB_LOCAL)
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
</ul>
