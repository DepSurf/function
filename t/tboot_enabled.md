# Function: <code>tboot_enabled</code>

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
In arch/x86/kernel/tboot.c (ffffffff81f6a2c2)
Location: include/linux/tboot.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_shutdown
  - arch/x86/kernel/tboot.c:tboot_sleep
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
In arch/x86/kernel/tboot.c (ffffffff81f92534)
Location: include/linux/tboot.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_sleep
  - arch/x86/kernel/tboot.c:tboot_shutdown
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
In arch/x86/kernel/tboot.c (ffffffff81fcd800)
Location: include/linux/tboot.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_sleep
  - arch/x86/kernel/tboot.c:tboot_shutdown
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
In arch/x86/kernel/tboot.c (ffffffff820ade41)
Location: include/linux/tboot.h:139
Inline: True
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
In arch/x86/kernel/tboot.c (ffffffff8103e275)
Location: include/linux/tboot.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
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
In arch/x86/kernel/tboot.c (ffffffff8103fb25)
Location: include/linux/tboot.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_force_iommu
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
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
In arch/x86/kernel/tboot.c (ffffffff81041125)
Location: include/linux/tboot.h:139
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_force_iommu
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
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
In arch/x86/kernel/tboot.c (ffffffff810437f5)
Location: include/linux/tboot.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_force_iommu
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
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
In arch/x86/kernel/tboot.c (ffffffff81043f45)
Location: include/linux/tboot.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_force_iommu
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool tboot_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff810478a5)
Location: arch/x86/kernel/tboot.c:47
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_force_iommu
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
Direct callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
**Symbols:**

```
ffffffff810477c0-ffffffff810477d6: tboot_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool tboot_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff810470d5)
Location: arch/x86/kernel/tboot.c:47
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_force_iommu
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
Direct callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
**Symbols:**

```
ffffffff81046ff0-ffffffff81047006: tboot_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool tboot_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81048a95)
Location: arch/x86/kernel/tboot.c:47
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_force_iommu
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
Direct callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
**Symbols:**

```
ffffffff81048770-ffffffff81048786: tboot_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool tboot_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8104f465)
Location: arch/x86/kernel/tboot.c:47
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_force_iommu
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
Direct callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
**Symbols:**

```
ffffffff8104f0b0-ffffffff8104f0c6: tboot_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool tboot_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8105a725)
Location: arch/x86/kernel/tboot.c:46
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_force_iommu
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
  - arch/x86/kernel/tboot.c:tboot_sleep
Direct callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
```
**Symbols:**

```
ffffffff8105a320-ffffffff8105a33a: tboot_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool tboot_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81068465)
Location: arch/x86/kernel/tboot.c:45
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
  - arch/x86/kernel/tboot.c:tboot_sleep
Direct callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff810680c0-ffffffff810680da: tboot_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool tboot_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81069d85)
Location: arch/x86/kernel/tboot.c:45
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
  - arch/x86/kernel/tboot.c:tboot_sleep
Direct callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81069940-ffffffff8106995a: tboot_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool tboot_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff81071255)
Location: arch/x86/kernel/tboot.c:45
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
  - arch/x86/kernel/tboot.c:tboot_sleep
Direct callers:
  - arch/x86/kernel/cpu/feat_ctl.c:init_ia32_feat_ctl
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81070e70-ffffffff81070e8a: tboot_enabled (STB_GLOBAL)
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
In arch/x86/kernel/tboot.c (ffffffff810440c5)
Location: include/linux/tboot.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_force_iommu
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
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
In arch/x86/kernel/tboot.c (ffffffff810336e5)
Location: include/linux/tboot.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_force_iommu
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
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
In arch/x86/kernel/tboot.c (ffffffff81043f05)
Location: include/linux/tboot.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_force_iommu
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
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
In arch/x86/kernel/tboot.c (ffffffff81045305)
Location: include/linux/tboot.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_force_iommu
  - arch/x86/kernel/tboot.c:tboot_get_dmar_table
  - arch/x86/kernel/tboot.c:tboot_late_init
  - arch/x86/kernel/tboot.c:tboot_extended_sleep
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
