# Function: <code>amd_gart_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff810632c3)
Location: arch/x86/include/asm/amd_nb.h:101
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff81f75a0f)
Location: arch/x86/include/asm/amd_nb.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81062f3a)
Location: arch/x86/include/asm/amd_nb.h:109
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff81f9e45b)
Location: arch/x86/include/asm/amd_nb.h:109
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81066428)
Location: arch/x86/include/asm/amd_nb.h:102
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff81fd99de)
Location: arch/x86/include/asm/amd_nb.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81065739)
Location: arch/x86/include/asm/amd_nb.h:103
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff820ba84c)
Location: arch/x86/include/asm/amd_nb.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81069909)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff826c11fb)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8106c51c)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff826eb423)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8107236f)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff828a202f)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff810778ad-ffffffff810778cf: amd_gart_present.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81075e80)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff828ba301)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff8107b446-ffffffff8107b468: amd_gart_present.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81076e50)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff828c07cf)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff8107c536-ffffffff8107c558: amd_gart_present.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8107e177)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff82ce4bee)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff81083b36-ffffffff81083b58: amd_gart_present.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8107de37)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff82fd244f)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff81bd86a1-ffffffff81bd86c3: amd_gart_present.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8107ef57)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff831dd044)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff81bca542-ffffffff81bca564: amd_gart_present.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8108dbe7)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff832c021e)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff81c9f9a1-ffffffff81c9f9c3: amd_gart_present.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81e4e681)
Location: arch/x86/include/asm/amd_nb.h:102
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff8347276f)
Location: arch/x86/include/asm/amd_nb.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff81e4f279-ffffffff81e4f2a3: amd_gart_present.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff810b5a32)
Location: arch/x86/include/asm/amd_nb.h:102
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff83e99d0a)
Location: arch/x86/include/asm/amd_nb.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff810b8b28)
Location: arch/x86/include/asm/amd_nb.h:102
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff836bd70a)
Location: arch/x86/include/asm/amd_nb.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff810bff68)
Location: arch/x86/include/asm/amd_nb.h:102
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff838ee1ca)
Location: arch/x86/include/asm/amd_nb.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
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
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81075e50)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff828ab7a5)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff8107b536-ffffffff8107b558: amd_gart_present.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81065e31)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff828a3a6c)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff8106ac66-ffffffff8106ac88: amd_gart_present.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81075e00)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff828be6a4)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff8107b4e6-ffffffff8107b508: amd_gart_present.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81077e60)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
```
```
In arch/x86/kernel/aperture_64.c (ffffffff828c17f1)
Location: arch/x86/include/asm/amd_nb.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
```
**Symbols:**

```
ffffffff8107d5e6-ffffffff8107d608: amd_gart_present.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
