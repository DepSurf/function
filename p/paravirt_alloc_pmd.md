# Function: <code>paravirt_alloc_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff8103467d)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81068e8f)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In mm/memory.c (ffffffff811beb72)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff811de601)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8181f417)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff81033840)
Location: arch/x86/include/asm/paravirt.h:350
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81069017)
Location: arch/x86/include/asm/paravirt.h:350
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In mm/memory.c (ffffffff811da9ce)
Location: arch/x86/include/asm/paravirt.h:350
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff811fc9fd)
Location: arch/x86/include/asm/paravirt.h:350
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81899b04)
Location: arch/x86/include/asm/paravirt.h:350
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff8103346d)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff8106cc67)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In mm/memory.c (ffffffff811ea53b)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff8120d4e1)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff818ce1b6)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff8103163b)
Location: arch/x86/include/asm/paravirt.h:339
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff8106c042)
Location: arch/x86/include/asm/paravirt.h:339
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In mm/memory.c (ffffffff811f5592)
Location: arch/x86/include/asm/paravirt.h:339
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff812193b5)
Location: arch/x86/include/asm/paravirt.h:339
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8190564b)
Location: arch/x86/include/asm/paravirt.h:339
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff81033892)
Location: arch/x86/include/asm/paravirt.h:331
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81070a82)
Location: arch/x86/include/asm/paravirt.h:331
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In mm/memory.c (ffffffff8120e471)
Location: arch/x86/include/asm/paravirt.h:331
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff812343b1)
Location: arch/x86/include/asm/paravirt.h:331
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8198f6ab)
Location: arch/x86/include/asm/paravirt.h:331
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
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
In arch/x86/kernel/espfix_64.c (ffffffff81034c07)
Location: arch/x86/include/asm/paravirt.h:331
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff8107384e)
Location: arch/x86/include/asm/paravirt.h:331
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In mm/memory.c (ffffffff8122ee66)
Location: arch/x86/include/asm/paravirt.h:331
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff81257324)
Location: arch/x86/include/asm/paravirt.h:331
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff819ebf23)
Location: arch/x86/include/asm/paravirt.h:331
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff81035de7)
Location: arch/x86/include/asm/paravirt.h:345
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a23fdf)
Location: arch/x86/include/asm/paravirt.h:345
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:345
Inline: True
```
```
In mm/memory.c (ffffffff812418f6)
Location: arch/x86/include/asm/paravirt.h:345
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff8126b997)
Location: arch/x86/include/asm/paravirt.h:345
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a27191)
Location: arch/x86/include/asm/paravirt.h:345
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff81037f47)
Location: arch/x86/include/asm/paravirt.h:345
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a94302)
Location: arch/x86/include/asm/paravirt.h:345
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:345
Inline: True
```
```
In mm/memory.c (ffffffff81254275)
Location: arch/x86/include/asm/paravirt.h:345
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff81286c96)
Location: arch/x86/include/asm/paravirt.h:345
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a97a3c)
Location: arch/x86/include/asm/paravirt.h:345
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff81038717)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81acbbe2)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
```
```
In mm/memory.c (ffffffff812627d5)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff81296896)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81acf30a)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff8103b234)
Location: arch/x86/include/asm/paravirt.h:347
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81bc4a63)
Location: arch/x86/include/asm/paravirt.h:347
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:347
Inline: False
```
```
In mm/memory.c (ffffffff812926d5)
Location: arch/x86/include/asm/paravirt.h:347
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff812c9de4)
Location: arch/x86/include/asm/paravirt.h:347
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7cc5)
Location: arch/x86/include/asm/paravirt.h:347
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff8103ba44)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81c3d95c)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:343
Inline: False
```
```
In mm/memory.c (ffffffff8129cfbb)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff812d5a21)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81c409f0)
Location: arch/x86/include/asm/paravirt.h:343
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff8103d3e5)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81c2fd05)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:360
Inline: False
```
```
In mm/memory.c (ffffffff812a269e)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff812dc724)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81bdaca4)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff8104302d)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81d4e454)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:360
Inline: False
```
```
In mm/memory.c (ffffffff812e3a0e)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff812f1e75)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
```
In mm/hugetlb.c (ffffffff813238dc)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81cc073f)
Location: arch/x86/include/asm/paravirt.h:360
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff8104af5f)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/mm/init_64.c (ffffffff81f1e218)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:366
Inline: False
```
```
In mm/percpu.c (ffffffff81e6c7bb)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
```
```
In mm/memory.c (ffffffff81344d9c)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff81355bb0)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
```
```
In mm/hugetlb.c (ffffffff81391455)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81e72b65)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
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
In arch/x86/kernel/espfix_64.c (ffffffff810569d8)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/mm/init_64.c (ffffffff820c6706)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In mm/percpu.c (ffffffff8139aea8)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
```
```
In mm/memory.c (ffffffff813bcfcc)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff813d01c5)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140e47c)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8141ba98)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
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
In arch/x86/kernel/espfix_64.c (ffffffff810579a8)
Location: arch/x86/include/asm/paravirt.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/mm/init_64.c (ffffffff8214a754)
Location: arch/x86/include/asm/paravirt.h:361
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In mm/percpu.c (ffffffff813cdf68)
Location: arch/x86/include/asm/paravirt.h:361
Inline: True
```
```
In mm/memory.c (ffffffff813f1d12)
Location: arch/x86/include/asm/paravirt.h:361
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff81404f28)
Location: arch/x86/include/asm/paravirt.h:361
Inline: True
```
```
In mm/hugetlb.c (ffffffff8144185e)
Location: arch/x86/include/asm/paravirt.h:361
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff8144f098)
Location: arch/x86/include/asm/paravirt.h:361
Inline: True
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
In arch/x86/kernel/espfix_64.c (ffffffff8105ec48)
Location: arch/x86/include/asm/paravirt.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/mm/init_64.c (ffffffff8222d204)
Location: arch/x86/include/asm/paravirt.h:363
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In mm/percpu.c (ffffffff813f88d8)
Location: arch/x86/include/asm/paravirt.h:363
Inline: True
```
```
In mm/memory.c (ffffffff81414c38)
Location: arch/x86/include/asm/paravirt.h:363
Inline: True
Inline callers:
  - mm/memory.c:pud_populate
```
```
In mm/mremap.c (ffffffff814314a8)
Location: arch/x86/include/asm/paravirt.h:363
Inline: True
Inline callers:
  - mm/mremap.c:pud_populate
```
```
In mm/hugetlb.c (ffffffff81474348)
Location: arch/x86/include/asm/paravirt.h:363
Inline: True
Inline callers:
  - mm/hugetlb.c:pud_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81488c58)
Location: arch/x86/include/asm/paravirt.h:363
Inline: True
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff81038877)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81a6aa52)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
```
```
In mm/memory.c (ffffffff8125ae25)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff8128ee76)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e17a)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (0)
Location: arch/x86/include/asm/pgalloc.h:20
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgalloc.h:20
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:20
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgalloc.h:20
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgalloc.h:20
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgalloc.h:20
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff810386d7)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81ad6e62)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
```
```
In mm/memory.c (ffffffff81258bc5)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff8128cc86)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ada58a)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/espfix_64.c (ffffffff810396d7)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81ae3322)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:fill_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
```
```
In mm/memory.c (ffffffff812685c5)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/hugetlb.c (ffffffff8129ca54)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6a40)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
</details>
</li>
</ul>

## Differences
