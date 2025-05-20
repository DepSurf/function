# Function: <code>check_pt_base</code>

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
In arch/x86/xen/mmu.c (ffffffff81f6346a)
Location: arch/x86/xen/mmu.c:1893
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
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
In arch/x86/xen/mmu.c (ffffffff81f8b026)
Location: arch/x86/xen/mmu.c:1883
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
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
In arch/x86/xen/mmu.c (ffffffff81fc6414)
Location: arch/x86/xen/mmu.c:1883
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
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
In arch/x86/xen/mmu_pv.c (ffffffff820a7295)
Location: arch/x86/xen/mmu_pv.c:1867
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
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
In arch/x86/xen/mmu_pv.c (ffffffff826ada42)
Location: arch/x86/xen/mmu_pv.c:1825
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
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
In arch/x86/xen/mmu_pv.c (ffffffff826d6db1)
Location: arch/x86/xen/mmu_pv.c:1853
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
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
In arch/x86/xen/mmu_pv.c (ffffffff8288ccfa)
Location: arch/x86/xen/mmu_pv.c:1861
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
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
In arch/x86/xen/mmu_pv.c (ffffffff828a4192)
Location: arch/x86/xen/mmu_pv.c:1851
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7225)
Location: arch/x86/xen/mmu_pv.c:1851
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void check_pt_base(long unsigned int *pt_base, long unsigned int *pt_end, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82ccc1ac)
Location: arch/x86/xen/mmu_pv.c:1851
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
**Symbols:**

```
ffffffff82ccc1ac-ffffffff82ccc296: check_pt_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void check_pt_base(long unsigned int *pt_base, long unsigned int *pt_end, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82fb7fea)
Location: arch/x86/xen/mmu_pv.c:1651
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
**Symbols:**

```
ffffffff82fb7fea-ffffffff82fb80d4: check_pt_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff831c3afd)
Location: arch/x86/xen/mmu_pv.c:1650
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff832a4664)
Location: arch/x86/xen/mmu_pv.c:1653
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff834539aa)
Location: arch/x86/xen/mmu_pv.c:1670
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
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
In arch/x86/xen/mmu_pv.c (ffffffff83e70f19)
Location: arch/x86/xen/mmu_pv.c:1670
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
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
In arch/x86/xen/mmu_pv.c (ffffffff83691d97)
Location: arch/x86/xen/mmu_pv.c:1679
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
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
In arch/x86/xen/mmu_pv.c (ffffffff838c18a7)
Location: arch/x86/xen/mmu_pv.c:1679
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
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
In arch/x86/xen/mmu_pv.c (ffffffff8289522e)
Location: arch/x86/xen/mmu_pv.c:1851
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff828a8225)
Location: arch/x86/xen/mmu_pv.c:1851
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
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
In arch/x86/xen/mmu_pv.c (ffffffff828a822b)
Location: arch/x86/xen/mmu_pv.c:1851
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
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
</ul>
