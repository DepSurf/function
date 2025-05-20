# Function: <code>exclude_from_vmcore</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void exclude_from_vmcore(u64 aper_base, u32 aper_order);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8106ea41)
Location: arch/x86/kernel/aperture_64.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff8106ea41-ffffffff8106ea7f: exclude_from_vmcore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void exclude_from_vmcore(u64 aper_base, u32 aper_order);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107190b)
Location: arch/x86/kernel/aperture_64.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff8107190b-ffffffff81071948: exclude_from_vmcore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void exclude_from_vmcore(u64 aper_base, u32 aper_order);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107794d)
Location: arch/x86/kernel/aperture_64.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff8107794d-ffffffff8107798a: exclude_from_vmcore (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
