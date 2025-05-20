# Function: <code>pmd_mknotpresent</code>

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
In mm/pgtable-generic.c (ffffffff811d067f)
Location: arch/x86/include/asm/pgtable.h:302
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In mm/pgtable-generic.c (ffffffff811ed7ef)
Location: arch/x86/include/asm/pgtable.h:331
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In mm/pgtable-generic.c (ffffffff811f7bbf)
Location: arch/x86/include/asm/pgtable.h:331
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In mm/pgtable-generic.c (ffffffff81202daf)
Location: arch/x86/include/asm/pgtable.h:388
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In mm/pgtable-generic.c (ffffffff8121bb06)
Location: arch/x86/include/asm/pgtable.h:403
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In arch/x86/mm/kmmio.c (ffffffff8107fdfb)
Location: arch/x86/include/asm/pgtable.h:570
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8123d8c0)
Location: arch/x86/include/asm/pgtable.h:570
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In arch/x86/mm/kmmio.c (ffffffff8108693b)
Location: arch/x86/include/asm/pgtable.h:572
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81251e70)
Location: arch/x86/include/asm/pgtable.h:572
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In arch/x86/mm/kmmio.c (ffffffff8108a54b)
Location: arch/x86/include/asm/pgtable.h:589
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81264151)
Location: arch/x86/include/asm/pgtable.h:589
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In arch/x86/mm/kmmio.c (ffffffff8108b1bb)
Location: arch/x86/include/asm/pgtable.h:589
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812729c1)
Location: arch/x86/include/asm/pgtable.h:589
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
In arch/x86/mm/kmmio.c (ffffffff8108a17b)
Location: arch/x86/include/asm/pgtable.h:589
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8126b011)
Location: arch/x86/include/asm/pgtable.h:589
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In arch/x86/mm/kmmio.c (ffffffff81078c28)
Location: arch/x86/include/asm/pgtable.h:589
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In mm/pgtable-generic.c (ffffffff8125d045)
Location: arch/x86/include/asm/pgtable.h:589
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In arch/x86/mm/kmmio.c (ffffffff8108a12b)
Location: arch/x86/include/asm/pgtable.h:589
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81268db1)
Location: arch/x86/include/asm/pgtable.h:589
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
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
In arch/x86/mm/kmmio.c (ffffffff8108c3cb)
Location: arch/x86/include/asm/pgtable.h:589
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81278741)
Location: arch/x86/include/asm/pgtable.h:589
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
</details>
</li>
</ul>

## Differences
