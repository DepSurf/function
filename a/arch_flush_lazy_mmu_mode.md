# Function: <code>arch_flush_lazy_mmu_mode</code>

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
In arch/x86/mm/fault.c (ffffffff8106a735)
Location: arch/x86/include/asm/paravirt.h:678
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
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
In arch/x86/mm/fault.c (ffffffff8106a4a3)
Location: arch/x86/include/asm/paravirt.h:651
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
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
In arch/x86/mm/fault.c (ffffffff8106e043)
Location: arch/x86/include/asm/paravirt.h:642
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
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
In arch/x86/mm/fault.c (ffffffff8106d586)
Location: arch/x86/include/asm/paravirt.h:689
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
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
In arch/x86/mm/fault.c (ffffffff81072591)
Location: arch/x86/include/asm/paravirt.h:653
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
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
In arch/x86/mm/fault.c (ffffffff81075150)
Location: arch/x86/include/asm/paravirt.h:658
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
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
In arch/x86/mm/fault.c (ffffffff8107af50)
Location: arch/x86/include/asm/paravirt.h:636
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
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
In arch/x86/mm/fault.c (ffffffff8107fe4b)
Location: arch/x86/include/asm/paravirt.h:637
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81084a85)
Location: arch/x86/include/asm/paravirt.h:637
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
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
In arch/x86/mm/fault.c (ffffffff81080edb)
Location: arch/x86/include/asm/paravirt.h:625
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81085785)
Location: arch/x86/include/asm/paravirt.h:625
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
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
In arch/x86/mm/fault.c (ffffffff81087d99)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f557)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__kernel_map_pages
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/x86/mm/fault.c (ffffffff8107fedb)
Location: arch/x86/include/asm/paravirt.h:625
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81084785)
Location: arch/x86/include/asm/paravirt.h:625
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107fe8b)
Location: arch/x86/include/asm/paravirt.h:625
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81084735)
Location: arch/x86/include/asm/paravirt.h:625
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
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
In arch/x86/mm/fault.c (ffffffff81081f7b)
Location: arch/x86/include/asm/paravirt.h:625
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81086885)
Location: arch/x86/include/asm/paravirt.h:625
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
```
</details>
</li>
</ul>

## Differences
