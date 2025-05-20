# Function: <code>tboot_force_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103e400)
Location: arch/x86/kernel/tboot.c:523
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8103e400-ffffffff8103e467: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103e230)
Location: arch/x86/kernel/tboot.c:508
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8103e230-ffffffff8103e297: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103dae0)
Location: arch/x86/kernel/tboot.c:508
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8103dae0-ffffffff8103db47: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103bb70)
Location: arch/x86/kernel/tboot.c:512
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8103bb70-ffffffff8103bbe7: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tboot.c (ffffffff8103e590)
Location: arch/x86/kernel/tboot.c:523
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8103e590-ffffffff8103e607: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:523
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8103fbbb-ffffffff8103fbcc: tboot_force_iommu.cold.20 (STB_LOCAL)
ffffffff8103fb20-ffffffff8103fb83: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:523
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff810411bb-ffffffff810411cc: tboot_force_iommu.cold.20 (STB_LOCAL)
ffffffff81041120-ffffffff81041183: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:510
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff810438a5-ffffffff810438b6: tboot_force_iommu.cold (STB_LOCAL)
ffffffff810437f0-ffffffff81043853: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:510
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81043ff5-ffffffff81044006: tboot_force_iommu.cold (STB_LOCAL)
ffffffff81043f40-ffffffff81043fa3: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:512
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81047c4b-ffffffff81047c5c: tboot_force_iommu.cold (STB_LOCAL)
ffffffff810478a0-ffffffff81047903: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:513
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81bd4ec2-ffffffff81bd4ed3: tboot_force_iommu.cold (STB_LOCAL)
ffffffff810470d0-ffffffff81047113: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:521
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81bc7276-ffffffff81bc7287: tboot_force_iommu.cold (STB_LOCAL)
ffffffff81048a90-ffffffff81048ad3: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:521
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81c9a86e-ffffffff81c9a87f: tboot_force_iommu.cold (STB_LOCAL)
ffffffff8104f460-ffffffff8104f4a3: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:520
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81e49cee-ffffffff81e49cff: tboot_force_iommu.cold (STB_LOCAL)
ffffffff8105a720-ffffffff8105a76f: tboot_force_iommu (STB_GLOBAL)
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
In drivers/iommu/intel/iommu.c (ffffffff83ef5aa0)
Location: drivers/iommu/intel/iommu.c:3916
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
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
In drivers/iommu/intel/iommu.c (ffffffff8371b550)
Location: drivers/iommu/intel/iommu.c:3804
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
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
In drivers/iommu/intel/iommu.c (ffffffff8394f060)
Location: drivers/iommu/intel/iommu.c:3646
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_init
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:510
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81044175-ffffffff81044186: tboot_force_iommu.cold (STB_LOCAL)
ffffffff810440c0-ffffffff81044123: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:510
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81033795-ffffffff810337a6: tboot_force_iommu.cold (STB_LOCAL)
ffffffff810336e0-ffffffff81033743: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:510
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81043fb5-ffffffff81043fc6: tboot_force_iommu.cold (STB_LOCAL)
ffffffff81043f00-ffffffff81043f63: tboot_force_iommu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tboot_force_iommu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/kernel/tboot.c:510
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff810453b5-ffffffff810453c6: tboot_force_iommu.cold (STB_LOCAL)
ffffffff81045300-ffffffff81045363: tboot_force_iommu (STB_GLOBAL)
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
