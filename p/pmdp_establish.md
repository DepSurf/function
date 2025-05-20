# Function: <code>pmdp_establish</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8123d954)
Location: arch/x86/include/asm/pgtable.h:1165
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In mm/pgtable-generic.c (ffffffff81251f04)
Location: arch/x86/include/asm/pgtable.h:1190
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In mm/pgtable-generic.c (ffffffff812641e3)
Location: arch/x86/include/asm/pgtable.h:1210
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In mm/pgtable-generic.c (ffffffff81272a53)
Location: arch/x86/include/asm/pgtable.h:1210
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In mm/pgtable-generic.c (ffffffff812a3812)
Location: arch/x86/include/asm/pgtable.h:1170
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In mm/pgtable-generic.c (ffffffff812af0f2)
Location: arch/x86/include/asm/pgtable.h:1166
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In mm/pgtable-generic.c (ffffffff812b45a1)
Location: arch/x86/include/asm/pgtable.h:1166
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In mm/pgtable-generic.c (ffffffff812f6181)
Location: arch/x86/include/asm/pgtable.h:1137
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In arch/x86/mm/pgtable.c (ffffffff810ad5e3)
Location: arch/x86/include/asm/pgtable.h:1148
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In mm/pgtable-generic.c (ffffffff8135a191)
Location: arch/x86/include/asm/pgtable.h:1148
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In arch/x86/mm/pgtable.c (ffffffff810c7726)
Location: arch/x86/include/asm/pgtable.h:1166
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In mm/pgtable-generic.c (ffffffff813d4c11)
Location: arch/x86/include/asm/pgtable.h:1166
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In arch/x86/mm/pgtable.c (ffffffff810cae8e)
Location: arch/x86/include/asm/pgtable.h:1167
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In mm/pgtable-generic.c (ffffffff81409668)
Location: arch/x86/include/asm/pgtable.h:1167
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In arch/x86/mm/pgtable.c (ffffffff810d33de)
Location: arch/x86/include/asm/pgtable.h:1390
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
```
```
In mm/pgtable-generic.c (ffffffff81435e58)
Location: arch/x86/include/asm/pgtable.h:1390
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffff800010308464)
Location: arch/arm64/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
</details>
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
In mm/pgtable-generic.c (ffffffff8126b0a3)
Location: arch/x86/include/asm/pgtable.h:1210
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In mm/pgtable-generic.c (ffffffff8125d08b)
Location: arch/x86/include/asm/pgtable.h:1210
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81268e43)
Location: arch/x86/include/asm/pgtable.h:1210
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In mm/pgtable-generic.c (ffffffff812787d3)
Location: arch/x86/include/asm/pgtable.h:1210
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
</details>
</li>
</ul>

## Differences
