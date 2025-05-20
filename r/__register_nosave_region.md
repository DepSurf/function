# Function: <code>__register_nosave_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81f7e9c0)
Location: kernel/power/snapshot.c:842
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_mark_nosave_regions
  - arch/x86/kernel/e820.c:e820_mark_nosave_regions
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff81f7e9c0-ffffffff81f7ea6f: __register_nosave_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81fa78bb)
Location: kernel/power/snapshot.c:939
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_mark_nosave_regions
  - arch/x86/kernel/e820.c:e820_mark_nosave_regions
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff81fa78bb-ffffffff81fa796c: __register_nosave_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81fe35dc)
Location: kernel/power/snapshot.c:939
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_mark_nosave_regions
  - arch/x86/kernel/e820.c:e820_mark_nosave_regions
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff81fe35dc-ffffffff81fe368d: __register_nosave_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff820c4018)
Location: kernel/power/snapshot.c:941
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff820c4018-ffffffff820c40cf: __register_nosave_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff826cc26e)
Location: kernel/power/snapshot.c:943
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff826cc26e-ffffffff826cc325: __register_nosave_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff826f63da)
Location: kernel/power/snapshot.c:943
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff826f63da-ffffffff826f6491: __register_nosave_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff828ad2eb)
Location: kernel/power/snapshot.c:943
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff828ad2eb-ffffffff828ad3a5: __register_nosave_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff828c5c8a)
Location: kernel/power/snapshot.c:941
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff828c5c8a-ffffffff828c5d61: __register_nosave_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff828ce2ce)
Location: kernel/power/snapshot.c:948
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff828ce2ce-ffffffff828ce3a5: __register_nosave_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff82cef6ec)
Location: kernel/power/snapshot.c:947
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/aperture_64.c:allocate_aperture
```
**Symbols:**

```
ffffffff82cef6ec-ffffffff82cef7c3: __register_nosave_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff82fdbe17)
Location: kernel/power/snapshot.c:981
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/aperture_64.c:allocate_aperture
```
**Symbols:**

```
ffffffff82fdbe17-ffffffff82fdbeee: __register_nosave_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff831e6b7a)
Location: kernel/power/snapshot.c:981
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff831e6b7a-ffffffff831e6c51: __register_nosave_region (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c151ff9c)
Location: kernel/power/snapshot.c:948
Inline: False
```
**Symbols:**

```
c151ff9c-c15200a8: __register_nosave_region (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff828b6fc6)
Location: kernel/power/snapshot.c:947
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff828b6fc6-ffffffff828b709d: __register_nosave_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff828af251)
Location: kernel/power/snapshot.c:948
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff828af251-ffffffff828af328: __register_nosave_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff828c9f02)
Location: kernel/power/snapshot.c:948
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff828c9f02-ffffffff828c9fd9: __register_nosave_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __register_nosave_region(long unsigned int start_pfn, long unsigned int end_pfn, int use_kmalloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff828cf2b4)
Location: kernel/power/snapshot.c:948
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/e820.c:e820__register_nosave_regions
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
**Symbols:**

```
ffffffff828cf2b4-ffffffff828cf38b: __register_nosave_region (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
