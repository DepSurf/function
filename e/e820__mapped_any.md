# Function: <code>e820__mapped_any</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81031be0)
Location: arch/x86/kernel/e820.c:76
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff81031be0-ffffffff81031c39: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81033e90)
Location: arch/x86/kernel/e820.c:76
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff81033e90-ffffffff81033ee9: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff810351c0)
Location: arch/x86/kernel/e820.c:76
Inline: True
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff810351c0-ffffffff81035219: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff810363a0)
Location: arch/x86/kernel/e820.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff810363a0-ffffffff810363f9: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81038590)
Location: arch/x86/kernel/e820.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff81038590-ffffffff810385e9: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81038d60)
Location: arch/x86/kernel/e820.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff81038d60-ffffffff81038db9: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8103b860)
Location: arch/x86/kernel/e820.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff8103b860-ffffffff8103b8c0: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8103c000)
Location: arch/x86/kernel/e820.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff8103c000-ffffffff8103c060: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8103d990)
Location: arch/x86/kernel/e820.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff8103d990-ffffffff8103d9ec: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81043600)
Location: arch/x86/kernel/e820.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff81043600-ffffffff8104365c: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8104b5c0)
Location: arch/x86/kernel/e820.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:aperture_valid
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - drivers/char/agp/amd64-agp.c:agp_aperture_valid
```
**Symbols:**

```
ffffffff8104b5c0-ffffffff8104b646: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81057180)
Location: arch/x86/kernel/e820.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - drivers/char/agp/amd64-agp.c:agp_aperture_valid
```
**Symbols:**

```
ffffffff81057180-ffffffff81057206: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81058180)
Location: arch/x86/kernel/e820.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - drivers/char/agp/amd64-agp.c:agp_aperture_valid
```
**Symbols:**

```
ffffffff81058180-ffffffff81058293: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8105f420)
Location: arch/x86/kernel/e820.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/aperture_64.c:gart_iommu_hole_init
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/kernel/aperture_64.c:read_agp
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - drivers/char/agp/amd64-agp.c:agp_aperture_valid
```
**Symbols:**

```
ffffffff8105f420-ffffffff8105f533: e820__mapped_any (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81038ec0)
Location: arch/x86/kernel/e820.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff81038ec0-ffffffff81038f19: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff810287d0)
Location: arch/x86/kernel/e820.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff810287d0-ffffffff81028829: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81038d20)
Location: arch/x86/kernel/e820.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff81038d20-ffffffff81038d79: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool e820__mapped_any(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81039d20)
Location: arch/x86/kernel/e820.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_probe
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/aperture_64.c:early_gart_iommu_check
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:phys_pte_init
```
**Symbols:**

```
ffffffff81039d20-ffffffff81039d79: e820__mapped_any (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
