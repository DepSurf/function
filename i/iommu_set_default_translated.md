# Function: <code>iommu_set_default_translated</code>

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
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff829036c5)
Location: drivers/iommu/iommu.c:2263
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff816db620-ffffffff816db641: iommu_set_default_translated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff82d1a566)
Location: drivers/iommu/iommu.c:2562
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff81790490-ffffffff817904b1: iommu_set_default_translated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8300c388)
Location: drivers/iommu/iommu.c:2785
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff817bc6d0-ffffffff817bc6f1: iommu_set_default_translated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff83217107)
Location: drivers/iommu/iommu.c:2770
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff8179f980-ffffffff8179f9a1: iommu_set_default_translated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff83300ad9)
Location: drivers/iommu/iommu.c:2855
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff81828970-ffffffff81828991: iommu_set_default_translated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff834b9674)
Location: drivers/iommu/iommu.c:2632
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff81968930-ffffffff81968957: iommu_set_default_translated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff83ef69c8)
Location: drivers/iommu/iommu.c:2694
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff81ad26b0-ffffffff81ad26d7: iommu_set_default_translated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8371c2f4)
Location: drivers/iommu/iommu.c:2700
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff81b20e20-ffffffff81b20e47: iommu_set_default_translated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8394fde4)
Location: drivers/iommu/iommu.c:2976
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff81b77a00-ffffffff81b77a27: iommu_set_default_translated (STB_GLOBAL)
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
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff800011496568)
Location: drivers/iommu/iommu.c:2263
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_subsys_init
```
**Symbols:**

```
ffff8000108c7650-ffff8000108c7694: iommu_set_default_translated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c1597100)
Location: drivers/iommu/iommu.c:2263
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_subsys_init
```
**Symbols:**

```
c09be5c4-c09be5fc: iommu_set_default_translated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c0000000013a9a10)
Location: drivers/iommu/iommu.c:2263
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_subsys_init
```
**Symbols:**

```
c00000000096e5e0-c00000000096e618: iommu_set_default_translated (STB_GLOBAL)
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
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff828eaeac)
Location: drivers/iommu/iommu.c:2263
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff816a1070-ffffffff816a1091: iommu_set_default_translated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff828e2339)
Location: drivers/iommu/iommu.c:2263
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff8167ea60-ffffffff8167ea81: iommu_set_default_translated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff828fe9e8)
Location: drivers/iommu/iommu.c:2263
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff816cf2e0-ffffffff816cf301: iommu_set_default_translated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iommu_set_default_translated(bool cmd_line);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff82904727)
Location: drivers/iommu/iommu.c:2263
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/iommu.c:iommu_subsys_init
Direct callers:
  - arch/x86/kernel/pci-dma.c:iommu_setup
```
**Symbols:**

```
ffffffff816e9850-ffffffff816e9871: iommu_set_default_translated (STB_GLOBAL)
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
