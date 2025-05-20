# Function: <code>enable_gart_translations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066c90)
Location: arch/x86/kernel/amd_gart_64.c:568
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
```
**Symbols:**

```
ffffffff81066c90-ffffffff81066d8b: enable_gart_translations.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81f9dd94)
Location: arch/x86/kernel/amd_gart_64.c:567
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff81066a20-ffffffff81066b2a: enable_gart_translations.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a6a0)
Location: arch/x86/kernel/amd_gart_64.c:567
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff8106a6a0-ffffffff8106a7a0: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810699a0)
Location: arch/x86/kernel/amd_gart_64.c:568
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff810699a0-ffffffff81069a86: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106e250)
Location: arch/x86/kernel/amd_gart_64.c:568
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff8106e250-ffffffff8106e336: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810716d5)
Location: arch/x86/kernel/amd_gart_64.c:560
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff810716d5-ffffffff810717b6: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810776fd)
Location: arch/x86/kernel/amd_gart_64.c:548
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff810776fd-ffffffff810777de: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b21e)
Location: arch/x86/kernel/amd_gart_64.c:542
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff8107b21e-ffffffff8107b2f8: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107c30e)
Location: arch/x86/kernel/amd_gart_64.c:542
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff8107c30e-ffffffff8107c3e8: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810838fe)
Location: arch/x86/kernel/amd_gart_64.c:540
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff810838fe-ffffffff810839c6: enable_gart_translations.part.0 (STB_LOCAL)
ffffffff810839c6-ffffffff810839e4: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81bd84aa)
Location: arch/x86/kernel/amd_gart_64.c:540
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff81bd84aa-ffffffff81bd8572: enable_gart_translations.part.0 (STB_LOCAL)
ffffffff81bd8572-ffffffff81bd8590: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81bca34f)
Location: arch/x86/kernel/amd_gart_64.c:540
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff81bca34f-ffffffff81bca429: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81c9f7a6)
Location: arch/x86/kernel/amd_gart_64.c:540
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff81c9f7a6-ffffffff81c9f880: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81e4efc8)
Location: arch/x86/kernel/amd_gart_64.c:538
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff81e4efc8-ffffffff81e4f0b8: enable_gart_translations (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff83e99271)
Location: arch/x86/kernel/amd_gart_64.c:538
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff810bf7a0-ffffffff810bf887: enable_gart_translations.part.0 (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff836bcc91)
Location: arch/x86/kernel/amd_gart_64.c:538
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff810c2e80-ffffffff810c2f67: enable_gart_translations.part.0 (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff838ed751)
Location: arch/x86/kernel/amd_gart_64.c:538
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff810cb2c0-ffffffff810cb3a7: enable_gart_translations.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b30e)
Location: arch/x86/kernel/amd_gart_64.c:542
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff8107b30e-ffffffff8107b3e8: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106aa3e)
Location: arch/x86/kernel/amd_gart_64.c:542
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff8106aa3e-ffffffff8106ab18: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b2be)
Location: arch/x86/kernel/amd_gart_64.c:542
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff8107b2be-ffffffff8107b398: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void enable_gart_translations();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107d3be)
Location: arch/x86/kernel/amd_gart_64.c:542
Inline: True
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
```
**Symbols:**

```
ffffffff8107d3be-ffffffff8107d498: enable_gart_translations (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
