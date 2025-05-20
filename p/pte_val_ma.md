# Function: <code>pte_val_ma</code>

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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/xen/page.h:270
Inline: True
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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/xen/page.h:270
Inline: True
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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/xen/page.h:270
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/xen/page.h:296
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/xen/page.h:296
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/xen/page.h:303
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/xen/page.h:303
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/xen/page.h:303
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/xen/page.h:303
Inline: True
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/xen/page.h:330
Inline: True
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/xen/page.h:330
Inline: True
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/xen/page.h:330
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82ccc770)
Location: arch/x86/include/asm/xen/page.h:329
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82fb85ac)
Location: arch/x86/include/asm/xen/page.h:329
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff831c2c0b)
Location: arch/x86/include/asm/xen/page.h:329
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff832a3617)
Location: arch/x86/include/asm/xen/page.h:329
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff81033110)
Location: arch/x86/include/asm/xen/page.h:321
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff8103aac0)
Location: arch/x86/include/asm/xen/page.h:321
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff8103ab90)
Location: arch/x86/include/asm/xen/page.h:321
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff81041050)
Location: arch/x86/include/asm/xen/page.h:324
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/xen/page.h:330
Inline: True
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/xen/page.h:330
Inline: True
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/xen/page.h:330
Inline: True
```
</details>
</li>
</ul>

## Differences
