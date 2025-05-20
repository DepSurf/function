# Function: <code>paravirt_release_pte</code>

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
In arch/x86/xen/p2m.c (ffffffff81024b23)
Location: arch/x86/include/asm/paravirt.h:355
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/mm/pgtable.c (ffffffff81070c47)
Location: arch/x86/include/asm/paravirt.h:355
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff81023e6a)
Location: arch/x86/include/asm/paravirt.h:345
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/mm/pgtable.c (ffffffff81070a58)
Location: arch/x86/include/asm/paravirt.h:345
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff8102459a)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/mm/pgtable.c (ffffffff810746e5)
Location: arch/x86/include/asm/paravirt.h:336
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff8101d761)
Location: arch/x86/include/asm/paravirt.h:334
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/mm/pgtable.c (ffffffff81073c35)
Location: arch/x86/include/asm/paravirt.h:334
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff8101e44c)
Location: arch/x86/include/asm/paravirt.h:326
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/mm/pgtable.c (ffffffff81079655)
Location: arch/x86/include/asm/paravirt.h:326
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff8101ee87)
Location: arch/x86/include/asm/paravirt.h:326
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/mm/pgtable.c (ffffffff8107c20e)
Location: arch/x86/include/asm/paravirt.h:326
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff8101e737)
Location: arch/x86/include/asm/paravirt.h:340
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/mm/pgtable.c (ffffffff81082b96)
Location: arch/x86/include/asm/paravirt.h:340
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff810202a6)
Location: arch/x86/include/asm/paravirt.h:340
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/mm/pgtable.c (ffffffff810867c6)
Location: arch/x86/include/asm/paravirt.h:340
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff81020c06)
Location: arch/x86/include/asm/paravirt.h:328
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/mm/pgtable.c (ffffffff810874b6)
Location: arch/x86/include/asm/paravirt.h:328
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff81022ec4)
Location: arch/x86/include/asm/paravirt.h:342
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81089966)
Location: arch/x86/include/asm/paravirt.h:342
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff81023494)
Location: arch/x86/include/asm/paravirt.h:338
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81089b98)
Location: arch/x86/include/asm/paravirt.h:338
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff81025944)
Location: arch/x86/include/asm/paravirt.h:355
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a816)
Location: arch/x86/include/asm/paravirt.h:355
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff81029e54)
Location: arch/x86/include/asm/paravirt.h:355
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff81099d96)
Location: arch/x86/include/asm/paravirt.h:355
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff8102e922)
Location: arch/x86/include/asm/paravirt.h:361
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810acdc6)
Location: arch/x86/include/asm/paravirt.h:361
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff8103591c)
Location: arch/x86/include/asm/paravirt.h:361
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810c6e66)
Location: arch/x86/include/asm/paravirt.h:361
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff8103589c)
Location: arch/x86/include/asm/paravirt.h:356
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810ca5b6)
Location: arch/x86/include/asm/paravirt.h:356
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff8103bdfc)
Location: arch/x86/include/asm/paravirt.h:358
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:alloc_p2m_pmd
```
```
In arch/x86/mm/pgtable.c (ffffffff810d2a62)
Location: arch/x86/include/asm/paravirt.h:358
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff81020d66)
Location: arch/x86/include/asm/paravirt.h:328
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/mm/pgtable.c (ffffffff810864b6)
Location: arch/x86/include/asm/paravirt.h:328
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgalloc.h:25
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
In arch/x86/xen/p2m.c (ffffffff81020bc6)
Location: arch/x86/include/asm/paravirt.h:328
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/mm/pgtable.c (ffffffff81086466)
Location: arch/x86/include/asm/paravirt.h:328
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/xen/p2m.c (ffffffff81020e16)
Location: arch/x86/include/asm/paravirt.h:328
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
```
```
In arch/x86/mm/pgtable.c (ffffffff810885a6)
Location: arch/x86/include/asm/paravirt.h:328
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
</details>
</li>
</ul>

## Differences
