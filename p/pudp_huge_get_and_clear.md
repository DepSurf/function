# Function: <code>pudp_huge_get_and_clear</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81202c1a)
Location: arch/x86/include/asm/pgtable.h:1087
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff81234639)
Location: arch/x86/include/asm/pgtable.h:1087
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff8121b97a)
Location: arch/x86/include/asm/pgtable.h:1093
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff81252539)
Location: arch/x86/include/asm/pgtable.h:1093
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff8123d755)
Location: arch/x86/include/asm/pgtable.h:1144
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff81276959)
Location: arch/x86/include/asm/pgtable.h:1144
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff81251cd5)
Location: arch/x86/include/asm/pgtable.h:1169
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff8128b869)
Location: arch/x86/include/asm/pgtable.h:1169
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff81263fb5)
Location: arch/x86/include/asm/pgtable.h:1189
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812a647c)
Location: arch/x86/include/asm/pgtable.h:1189
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff81272825)
Location: arch/x86/include/asm/pgtable.h:1189
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812b794c)
Location: arch/x86/include/asm/pgtable.h:1189
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff812a35e5)
Location: arch/x86/include/asm/pgtable.h:1149
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812ecb0c)
Location: arch/x86/include/asm/pgtable.h:1149
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff812aeec5)
Location: arch/x86/include/asm/pgtable.h:1145
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812f7b9c)
Location: arch/x86/include/asm/pgtable.h:1145
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff812b43f5)
Location: arch/x86/include/asm/pgtable.h:1145
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812fe14c)
Location: arch/x86/include/asm/pgtable.h:1145
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff812f5fd5)
Location: arch/x86/include/asm/pgtable.h:1116
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff81347cec)
Location: arch/x86/include/asm/pgtable.h:1116
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff81359f95)
Location: arch/x86/include/asm/pgtable.h:1123
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff813be15c)
Location: arch/x86/include/asm/pgtable.h:1123
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff813d49e5)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff8144099c)
Location: arch/x86/include/asm/pgtable.h:1141
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff814093b5)
Location: arch/x86/include/asm/pgtable.h:1142
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff8147625c)
Location: arch/x86/include/asm/pgtable.h:1142
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff81435ba5)
Location: arch/x86/include/asm/pgtable.h:1361
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff814a5b0c)
Location: arch/x86/include/asm/pgtable.h:1361
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff8126ae75)
Location: arch/x86/include/asm/pgtable.h:1189
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812aff2c)
Location: arch/x86/include/asm/pgtable.h:1189
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff8125cea5)
Location: arch/x86/include/asm/pgtable.h:1189
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812a13fc)
Location: arch/x86/include/asm/pgtable.h:1189
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff81268c15)
Location: arch/x86/include/asm/pgtable.h:1189
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812add3c)
Location: arch/x86/include/asm/pgtable.h:1189
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
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
In mm/pgtable-generic.c (ffffffff812785a5)
Location: arch/x86/include/asm/pgtable.h:1189
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pudp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812be09c)
Location: arch/x86/include/asm/pgtable.h:1189
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pud
```
</details>
</li>
</ul>

## Differences
