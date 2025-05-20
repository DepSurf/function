# Function: <code>iommu_full</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void iommu_full(struct device *dev, size_t size, int dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066a80)
Location: arch/x86/kernel/amd_gart_64.c:173
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
**Symbols:**

```
ffffffff81066a80-ffffffff81066ad6: iommu_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_full(struct device *dev, size_t size, int dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066810)
Location: arch/x86/kernel/amd_gart_64.c:172
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
**Symbols:**

```
ffffffff81066810-ffffffff81066866: iommu_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void iommu_full(struct device *dev, size_t size, int dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a490)
Location: arch/x86/kernel/amd_gart_64.c:172
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
**Symbols:**

```
ffffffff8106a490-ffffffff8106a4e6: iommu_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_full(struct device *dev, size_t size, int dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069810)
Location: arch/x86/kernel/amd_gart_64.c:173
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
**Symbols:**

```
ffffffff81069810-ffffffff81069866: iommu_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_full(struct device *dev, size_t size, int dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106e0c0)
Location: arch/x86/kernel/amd_gart_64.c:173
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
**Symbols:**

```
ffffffff8106e0c0-ffffffff8106e116: iommu_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_full(struct device *dev, size_t size, int dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:174
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:dma_map_area
```
**Symbols:**

```
ffffffff81070fb0-ffffffff81070ff6: iommu_full (STB_LOCAL)
ffffffff810716ae-ffffffff810716c6: iommu_full.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810770c8)
Location: arch/x86/kernel/amd_gart_64.c:167
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b3af)
Location: arch/x86/kernel/amd_gart_64.c:167
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107c49f)
Location: arch/x86/kernel/amd_gart_64.c:167
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81083a8a)
Location: arch/x86/kernel/amd_gart_64.c:166
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81bd8636)
Location: arch/x86/kernel/amd_gart_64.c:166
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81bca4cf)
Location: arch/x86/kernel/amd_gart_64.c:166
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81c9f972)
Location: arch/x86/kernel/amd_gart_64.c:166
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81e4f1ca)
Location: arch/x86/kernel/amd_gart_64.c:164
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810c03bd)
Location: arch/x86/kernel/amd_gart_64.c:164
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810c3a9e)
Location: arch/x86/kernel/amd_gart_64.c:164
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810cbede)
Location: arch/x86/kernel/amd_gart_64.c:164
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b49f)
Location: arch/x86/kernel/amd_gart_64.c:167
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106abcf)
Location: arch/x86/kernel/amd_gart_64.c:167
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b44f)
Location: arch/x86/kernel/amd_gart_64.c:167
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107d54f)
Location: arch/x86/kernel/amd_gart_64.c:167
Inline: True
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
