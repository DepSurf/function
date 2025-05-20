# Function: <code>paravirt_alloc_p4d</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086069)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
```
```
In mm/memory.c (ffffffff8128bfdd)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff812d17bb)
Location: arch/x86/include/asm/paravirt.h:366
Inline: True
```
**Symbols:**

```
ffffffff81086069-ffffffff81086080: paravirt_alloc_p4d.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bd89ad)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
```
In mm/memory.c (ffffffff81296f0d)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81be8ba6)
Location: arch/x86/include/asm/paravirt.h:362
Inline: True
```
**Symbols:**

```
ffffffff81bd89ad-ffffffff81bd89c4: paravirt_alloc_p4d.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bca85d)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
```
```
In mm/memory.c (ffffffff8129ccec)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81bdabd2)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
```
**Symbols:**

```
ffffffff81bca85d-ffffffff81bca874: paravirt_alloc_p4d.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c9fd45)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
```
```
In mm/memory.c (ffffffff812ddacc)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81cc066d)
Location: arch/x86/include/asm/paravirt.h:379
Inline: True
```
**Symbols:**

```
ffffffff81c9fd45-ffffffff81c9fd5c: paravirt_alloc_p4d.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81e4f445)
Location: arch/x86/include/asm/paravirt.h:385
Inline: True
```
```
In mm/percpu.c (ffffffff81e6c6d1)
Location: arch/x86/include/asm/paravirt.h:385
Inline: True
```
```
In mm/memory.c (ffffffff8133d60d)
Location: arch/x86/include/asm/paravirt.h:385
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81e72a7b)
Location: arch/x86/include/asm/paravirt.h:385
Inline: True
```
**Symbols:**

```
ffffffff81e4f445-ffffffff81e4f475: paravirt_alloc_p4d.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff810c1c88)
Location: arch/x86/include/asm/paravirt.h:385
Inline: True
```
```
In mm/percpu.c (ffffffff8139d3ad)
Location: arch/x86/include/asm/paravirt.h:385
Inline: True
```
```
In mm/memory.c (ffffffff813b52bd)
Location: arch/x86/include/asm/paravirt.h:385
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff8141bc9d)
Location: arch/x86/include/asm/paravirt.h:385
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
In arch/x86/mm/init_64.c (ffffffff810c5368)
Location: arch/x86/include/asm/paravirt.h:380
Inline: True
```
```
In mm/percpu.c (ffffffff813d04dd)
Location: arch/x86/include/asm/paravirt.h:380
Inline: True
```
```
In mm/memory.c (ffffffff813ea05d)
Location: arch/x86/include/asm/paravirt.h:380
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff8144f29d)
Location: arch/x86/include/asm/paravirt.h:380
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
In arch/x86/mm/init_64.c (ffffffff810cd648)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
```
```
In mm/percpu.c (ffffffff813fae9d)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
```
```
In mm/memory.c (ffffffff81415d6d)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81488f1d)
Location: arch/x86/include/asm/paravirt.h:382
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
