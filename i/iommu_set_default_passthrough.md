# Function: <code>iommu_set_default_passthrough</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff829036b9)
Location: drivers/iommu/iommu.c:2255
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff816db5f0-ffffffff816db611: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff82d1a55a)
Location: drivers/iommu/iommu.c:2554
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - drivers/iommu/intel/iommu.c:platform_optin_force_iommu
```
**Symbols:**

```
ffffffff81790460-ffffffff81790481: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8300c37c)
Location: drivers/iommu/iommu.c:2777
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - drivers/iommu/intel/iommu.c:platform_optin_force_iommu
```
**Symbols:**

```
ffffffff817bc6a0-ffffffff817bc6c1: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff832170fb)
Location: drivers/iommu/iommu.c:2763
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff8179f950-ffffffff8179f971: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff83300acd)
Location: drivers/iommu/iommu.c:2848
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81828940-ffffffff81828961: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff834b97c8)
Location: drivers/iommu/iommu.c:2625
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81968900-ffffffff81968927: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff83ef6837)
Location: drivers/iommu/iommu.c:2687
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81ad2670-ffffffff81ad2697: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8371c2cb)
Location: drivers/iommu/iommu.c:2693
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81b20de0-ffffffff81b20e07: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8394fdbb)
Location: drivers/iommu/iommu.c:2969
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
  - drivers/iommu/intel/iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81b779c0-ffffffff81b779e7: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff800011496558)
Location: drivers/iommu/iommu.c:2255
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
```
**Symbols:**

```
ffff8000108c7608-ffff8000108c764c: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c15970fc)
Location: drivers/iommu/iommu.c:2255
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
```
**Symbols:**

```
c09be58c-c09be5c4: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c0000000013a99fc)
Location: drivers/iommu/iommu.c:2255
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
```
**Symbols:**

```
c00000000096e5a0-c00000000096e5d8: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
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
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff828eaea0)
Location: drivers/iommu/iommu.c:2255
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff816a1040-ffffffff816a1061: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff828e232d)
Location: drivers/iommu/iommu.c:2255
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff8167ea30-ffffffff8167ea51: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff828fe9dc)
Location: drivers/iommu/iommu.c:2255
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff816cf2b0-ffffffff816cf2d1: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_passthrough(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8290471b)
Location: drivers/iommu/iommu.c:2255
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff816e9820-ffffffff816e9841: iommu_set_default_passthrough (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
