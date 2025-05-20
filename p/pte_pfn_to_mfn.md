# Function: <code>pte_pfn_to_mfn</code>

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
In arch/x86/xen/mmu.c (ffffffff8101e780)
Location: arch/x86/xen/mmu.c:383
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:convert_pfn_mfn
  - arch/x86/xen/mmu.c:xen_make_pgd
  - arch/x86/xen/mmu.c:xen_make_pmd
  - arch/x86/xen/mmu.c:xen_make_pud
Direct callers:
  - arch/x86/xen/mmu.c:convert_pfn_mfn
  - arch/x86/xen/mmu.c:xen_make_pgd
  - arch/x86/xen/mmu.c:xen_make_pmd
  - arch/x86/xen/mmu.c:xen_make_pud
```
**Symbols:**

```
ffffffff8101e780-ffffffff8101e808: pte_pfn_to_mfn.part.12 (STB_LOCAL)
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
In arch/x86/xen/mmu.c (ffffffff81f8a062)
Location: arch/x86/xen/mmu.c:384
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:convert_pfn_mfn
  - arch/x86/xen/mmu.c:xen_make_pte_init
  - arch/x86/xen/mmu.c:xen_make_pud
  - arch/x86/xen/mmu.c:xen_make_pmd
  - arch/x86/xen/mmu.c:xen_make_pgd
Direct callers:
  - arch/x86/xen/mmu.c:convert_pfn_mfn
  - arch/x86/xen/mmu.c:xen_make_pte_init
  - arch/x86/xen/mmu.c:xen_make_pud
  - arch/x86/xen/mmu.c:xen_make_pmd
  - arch/x86/xen/mmu.c:xen_make_pgd
```
**Symbols:**

```
ffffffff8101dba0-ffffffff8101dc25: pte_pfn_to_mfn.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81fc545c)
Location: arch/x86/xen/mmu.c:384
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:convert_pfn_mfn
  - arch/x86/xen/mmu.c:xen_make_pte_init
  - arch/x86/xen/mmu.c:xen_make_pud
  - arch/x86/xen/mmu.c:xen_make_pmd
  - arch/x86/xen/mmu.c:xen_make_pgd
Direct callers:
  - arch/x86/xen/mmu.c:convert_pfn_mfn
  - arch/x86/xen/mmu.c:xen_make_pte_init
  - arch/x86/xen/mmu.c:xen_make_pud
  - arch/x86/xen/mmu.c:xen_make_pmd
  - arch/x86/xen/mmu.c:xen_make_pgd
```
**Symbols:**

```
ffffffff8101e290-ffffffff8101e315: pte_pfn_to_mfn.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff820a62b3)
Location: arch/x86/xen/mmu_pv.c:351
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
Direct callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
```
**Symbols:**

```
ffffffff81020470-ffffffff810204ea: pte_pfn_to_mfn.part.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff826ac97d)
Location: arch/x86/xen/mmu_pv.c:331
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
Direct callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
```
**Symbols:**

```
ffffffff81021140-ffffffff810211d3: pte_pfn_to_mfn.part.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff826d5aa8)
Location: arch/x86/xen/mmu_pv.c:340
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
Direct callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
```
**Symbols:**

```
ffffffff810218f0-ffffffff81021971: pte_pfn_to_mfn.part.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8288bbc0)
Location: arch/x86/xen/mmu_pv.c:349
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
Direct callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
```
**Symbols:**

```
ffffffff81021460-ffffffff810214e1: pte_pfn_to_mfn.part.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a2ff3)
Location: arch/x86/xen/mmu_pv.c:349
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
Direct callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
```
**Symbols:**

```
ffffffff81022fd0-ffffffff8102305a: pte_pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a60a6)
Location: arch/x86/xen/mmu_pv.c:349
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
Direct callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
```
**Symbols:**

```
ffffffff81023910-ffffffff8102399a: pte_pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81029fe9)
Location: arch/x86/xen/mmu_pv.c:349
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
  - arch/x86/xen/mmu_pv.c:xen_make_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
  - arch/x86/xen/mmu_pv.c:xen_make_pte
```
**Symbols:**

```
ffffffff81025d70-ffffffff81025e00: pte_pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102a9c9)
Location: arch/x86/xen/mmu_pv.c:328
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
  - arch/x86/xen/mmu_pv.c:xen_make_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
  - arch/x86/xen/mmu_pv.c:xen_make_pte
```
**Symbols:**

```
ffffffff81026480-ffffffff81026510: pte_pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102b5b9)
Location: arch/x86/xen/mmu_pv.c:328
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
  - arch/x86/xen/mmu_pv.c:xen_make_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
  - arch/x86/xen/mmu_pv.c:xen_make_pte
```
**Symbols:**

```
ffffffff81028440-ffffffff810284d2: pte_pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102fd19)
Location: arch/x86/xen/mmu_pv.c:328
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
  - arch/x86/xen/mmu_pv.c:xen_make_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
  - arch/x86/xen/mmu_pv.c:xen_make_pte
```
**Symbols:**

```
ffffffff8102caf0-ffffffff8102cb82: pte_pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810352f9)
Location: arch/x86/xen/mmu_pv.c:332
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
  - arch/x86/xen/mmu_pv.c:xen_make_pte
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
  - arch/x86/xen/mmu_pv.c:xen_make_pte
```
**Symbols:**

```
ffffffff810318c0-ffffffff81031957: pte_pfn_to_mfn.part.0 (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff83e6f3d5)
Location: arch/x86/xen/mmu_pv.c:332
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
```
**Symbols:**

```
ffffffff81039110-ffffffff810391a7: pte_pfn_to_mfn.part.0 (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff836902d5)
Location: arch/x86/xen/mmu_pv.c:348
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
```
**Symbols:**

```
ffffffff81039050-ffffffff810390e7: pte_pfn_to_mfn.part.0 (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff838bfe25)
Location: arch/x86/xen/mmu_pv.c:348
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_p4d
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
```
**Symbols:**

```
ffffffff8103f500-ffffffff8103f597: pte_pfn_to_mfn.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828940af)
Location: arch/x86/xen/mmu_pv.c:349
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
Direct callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
```
**Symbols:**

```
ffffffff81023a70-ffffffff81023afa: pte_pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a70a6)
Location: arch/x86/xen/mmu_pv.c:349
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
Direct callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
```
**Symbols:**

```
ffffffff810238d0-ffffffff8102395a: pte_pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a707a)
Location: arch/x86/xen/mmu_pv.c:349
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
Direct callers:
  - arch/x86/xen/mmu_pv.c:convert_pfn_mfn
  - arch/x86/xen/mmu_pv.c:xen_make_pte_init
  - arch/x86/xen/mmu_pv.c:xen_make_pud
  - arch/x86/xen/mmu_pv.c:xen_make_pmd
  - arch/x86/xen/mmu_pv.c:xen_make_pgd
```
**Symbols:**

```
ffffffff81023d80-ffffffff81023e0a: pte_pfn_to_mfn.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
