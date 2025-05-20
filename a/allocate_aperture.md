# Function: <code>allocate_aperture</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81f75fd9)
Location: arch/x86/kernel/aperture_64.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81f9e714)
Location: arch/x86/kernel/aperture_64.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81fd9c97)
Location: arch/x86/kernel/aperture_64.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff820bab00)
Location: arch/x86/kernel/aperture_64.c:61
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff826c14b7)
Location: arch/x86/kernel/aperture_64.c:90
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff826eb6ce)
Location: arch/x86/kernel/aperture_64.c:90
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
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
In arch/x86/kernel/aperture_64.c (ffffffff828a22d0)
Location: arch/x86/kernel/aperture_64.c:90
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
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
In arch/x86/kernel/aperture_64.c (ffffffff828ba5b3)
Location: arch/x86/kernel/aperture_64.c:96
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
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
In arch/x86/kernel/aperture_64.c (ffffffff828c0a80)
Location: arch/x86/kernel/aperture_64.c:96
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 allocate_aperture();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff82ce454a)
Location: arch/x86/kernel/aperture_64.c:96
Inline: False
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff82ce454a-ffffffff82ce45fe: allocate_aperture (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 allocate_aperture();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff82fd1dab)
Location: arch/x86/kernel/aperture_64.c:96
Inline: False
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff82fd1dab-ffffffff82fd1e5f: allocate_aperture (STB_LOCAL)
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
In arch/x86/kernel/aperture_64.c (ffffffff831dd2f1)
Location: arch/x86/kernel/aperture_64.c:96
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
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
In arch/x86/kernel/aperture_64.c (ffffffff832c04e6)
Location: arch/x86/kernel/aperture_64.c:96
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
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
In arch/x86/kernel/aperture_64.c (ffffffff83472a84)
Location: arch/x86/kernel/aperture_64.c:107
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
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
In arch/x86/kernel/aperture_64.c (ffffffff83e99fd7)
Location: arch/x86/kernel/aperture_64.c:107
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
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
In arch/x86/kernel/aperture_64.c (ffffffff836bd9e7)
Location: arch/x86/kernel/aperture_64.c:107
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
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
In arch/x86/kernel/aperture_64.c (ffffffff838ee4a7)
Location: arch/x86/kernel/aperture_64.c:107
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
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
In arch/x86/kernel/aperture_64.c (ffffffff828aba56)
Location: arch/x86/kernel/aperture_64.c:96
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
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
In arch/x86/kernel/aperture_64.c (ffffffff828a3d1d)
Location: arch/x86/kernel/aperture_64.c:96
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
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
In arch/x86/kernel/aperture_64.c (ffffffff828be955)
Location: arch/x86/kernel/aperture_64.c:96
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
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
In arch/x86/kernel/aperture_64.c (ffffffff828c1aa2)
Location: arch/x86/kernel/aperture_64.c:96
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
