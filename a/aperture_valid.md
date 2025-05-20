# Function: <code>aperture_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107d3b1)
Location: arch/x86/include/asm/gart.h:91
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8151f9b6)
Location: arch/x86/include/asm/gart.h:91
Inline: True
```
**Symbols:**

```
ffffffff8107d3b1-ffffffff8107d43a: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107ee94)
Location: arch/x86/include/asm/gart.h:91
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81572822)
Location: arch/x86/include/asm/gart.h:91
Inline: True
```
**Symbols:**

```
ffffffff8107ee94-ffffffff8107ef1d: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81083544)
Location: arch/x86/include/asm/gart.h:91
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8159eeb2)
Location: arch/x86/include/asm/gart.h:91
Inline: True
```
**Symbols:**

```
ffffffff81083544-ffffffff810835cd: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8106a0de)
Location: arch/x86/include/asm/gart.h:91
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/char/agp/amd64-agp.c (ffffffff815b2d80)
Location: arch/x86/include/asm/gart.h:91
Inline: True
```
**Symbols:**

```
ffffffff8106a0de-ffffffff8106a162: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8106e9bd)
Location: arch/x86/include/asm/gart.h:92
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816199c0)
Location: arch/x86/include/asm/gart.h:92
Inline: True
```
**Symbols:**

```
ffffffff8106e9bd-ffffffff8106ea41: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107188d)
Location: arch/x86/include/asm/gart.h:92
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81653665)
Location: arch/x86/include/asm/gart.h:92
Inline: True
```
**Symbols:**

```
ffffffff8107188d-ffffffff8107190b: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff810778cf)
Location: arch/x86/include/asm/gart.h:92
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81671865)
Location: arch/x86/include/asm/gart.h:92
Inline: True
```
**Symbols:**

```
ffffffff810778cf-ffffffff8107794d: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107b468)
Location: arch/x86/include/asm/gart.h:92
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816a7478)
Location: arch/x86/include/asm/gart.h:92
Inline: True
```
**Symbols:**

```
ffffffff8107b468-ffffffff8107b4e5: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107c558)
Location: arch/x86/include/asm/gart.h:92
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816ca1b8)
Location: arch/x86/include/asm/gart.h:92
Inline: True
```
**Symbols:**

```
ffffffff8107c558-ffffffff8107c5d5: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81083b58)
Location: arch/x86/include/asm/gart.h:92
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8177ef84)
Location: arch/x86/include/asm/gart.h:92
Inline: True
```
**Symbols:**

```
ffffffff81083b58-ffffffff81083bd5: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81bd86c3)
Location: arch/x86/include/asm/gart.h:92
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81c09658)
Location: arch/x86/include/asm/gart.h:92
Inline: True
```
**Symbols:**

```
ffffffff81bd86c3-ffffffff81bd8740: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81bca564)
Location: arch/x86/include/asm/gart.h:92
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81bfb001)
Location: arch/x86/include/asm/gart.h:92
Inline: True
```
**Symbols:**

```
ffffffff81bca564-ffffffff81bca5e1: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81c9f9c3)
Location: arch/x86/include/asm/gart.h:92
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81cfbbb2)
Location: arch/x86/include/asm/gart.h:92
Inline: True
```
**Symbols:**

```
ffffffff81c9f9c3-ffffffff81c9fa40: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff81e4f1ea)
Location: arch/x86/include/asm/gart.h:91
Inline: False
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81ec4337)
Location: arch/x86/include/asm/gart.h:91
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_aperture_valid
```
**Symbols:**

```
ffffffff81e4f1ea-ffffffff81e4f279: aperture_valid (STB_LOCAL)
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
In arch/x86/kernel/aperture_64.c (ffffffff83e99f42)
Location: arch/x86/include/asm/gart.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81aa0685)
Location: arch/x86/include/asm/gart.h:91
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_aperture_valid
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
In arch/x86/kernel/aperture_64.c (ffffffff836bd94a)
Location: arch/x86/include/asm/gart.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81aebfa5)
Location: arch/x86/include/asm/gart.h:91
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_aperture_valid
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
In arch/x86/kernel/aperture_64.c (ffffffff838ee40a)
Location: arch/x86/include/asm/gart.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:read_agp
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81b3f4e5)
Location: arch/x86/include/asm/gart.h:91
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_aperture_valid
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107b558)
Location: arch/x86/include/asm/gart.h:92
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8168fc08)
Location: arch/x86/include/asm/gart.h:92
Inline: True
```
**Symbols:**

```
ffffffff8107b558-ffffffff8107b5d5: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8106ac88)
Location: arch/x86/include/asm/gart.h:92
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8166d5f8)
Location: arch/x86/include/asm/gart.h:92
Inline: True
```
**Symbols:**

```
ffffffff8106ac88-ffffffff8106ad05: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107b508)
Location: arch/x86/include/asm/gart.h:92
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816bde78)
Location: arch/x86/include/asm/gart.h:92
Inline: True
```
**Symbols:**

```
ffffffff8107b508-ffffffff8107b585: aperture_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int aperture_valid(u64 aper_base, u32 aper_size, u32 min_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/aperture_64.c (ffffffff8107d608)
Location: arch/x86/include/asm/gart.h:92
Inline: True
Direct callers:
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:search_agp_bridge
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816d8448)
Location: arch/x86/include/asm/gart.h:92
Inline: True
```
**Symbols:**

```
ffffffff8107d608-ffffffff8107d685: aperture_valid (STB_LOCAL)
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
