# Function: <code>is_new_memtype_allowed</code>

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
In arch/x86/mm/ioremap.c (ffffffff8106ba89)
Location: arch/x86/include/asm/pgtable.h:405
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat.c (ffffffff810705d2)
Location: arch/x86/include/asm/pgtable.h:405
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:reserve_pfn_range
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
In arch/x86/mm/ioremap.c (ffffffff8106b963)
Location: arch/x86/include/asm/pgtable.h:434
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat.c (ffffffff8107053d)
Location: arch/x86/include/asm/pgtable.h:434
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
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
In arch/x86/mm/ioremap.c (ffffffff8106f583)
Location: arch/x86/include/asm/pgtable.h:434
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat.c (ffffffff810741cd)
Location: arch/x86/include/asm/pgtable.h:434
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
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
In arch/x86/mm/ioremap.c (ffffffff8106ece7)
Location: arch/x86/include/asm/pgtable.h:572
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat.c (ffffffff8107374d)
Location: arch/x86/include/asm/pgtable.h:572
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
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
In arch/x86/mm/ioremap.c (ffffffff81073dd0)
Location: arch/x86/include/asm/pgtable.h:587
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat.c (ffffffff8107910d)
Location: arch/x86/include/asm/pgtable.h:587
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
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
In arch/x86/mm/ioremap.c (ffffffff810767eb)
Location: arch/x86/include/asm/pgtable.h:629
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat.c (ffffffff8107ba67)
Location: arch/x86/include/asm/pgtable.h:629
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
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
In arch/x86/mm/ioremap.c (ffffffff8107ce3f)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat.c (ffffffff810823d7)
Location: arch/x86/include/asm/pgtable.h:631
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:io_reserve_memtype
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
In arch/x86/mm/ioremap.c (ffffffff810806c1)
Location: arch/x86/include/asm/pgtable.h:648
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat.c (ffffffff81086055)
Location: arch/x86/include/asm/pgtable.h:648
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:io_reserve_memtype
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
In arch/x86/mm/ioremap.c (ffffffff810817b1)
Location: arch/x86/include/asm/pgtable.h:648
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat.c (ffffffff81086d45)
Location: arch/x86/include/asm/pgtable.h:648
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:io_reserve_memtype
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
In arch/x86/mm/ioremap.c (ffffffff81088750)
Location: arch/x86/include/asm/pgtable.h:684
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat/memtype.c (ffffffff8109045c)
Location: arch/x86/include/asm/pgtable.h:684
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
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
In arch/x86/mm/ioremap.c (ffffffff81088990)
Location: arch/x86/include/asm/pgtable.h:683
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat/memtype.c (ffffffff8109015c)
Location: arch/x86/include/asm/pgtable.h:683
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
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
In arch/x86/mm/ioremap.c (ffffffff81089730)
Location: arch/x86/include/asm/pgtable.h:683
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat/memtype.c (ffffffff81090ccc)
Location: arch/x86/include/asm/pgtable.h:683
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
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
In arch/x86/mm/ioremap.c (ffffffff81098a94)
Location: arch/x86/include/asm/pgtable.h:654
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810a080a)
Location: arch/x86/include/asm/pgtable.h:654
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
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
In arch/x86/mm/ioremap.c (ffffffff810ab848)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810b47ad)
Location: arch/x86/include/asm/pgtable.h:652
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
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
In arch/x86/mm/ioremap.c (ffffffff810c537c)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810cf481)
Location: arch/x86/include/asm/pgtable.h:669
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
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
In arch/x86/mm/ioremap.c (ffffffff810c8ae8)
Location: arch/x86/include/asm/pgtable.h:670
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810d2a3a)
Location: arch/x86/include/asm/pgtable.h:670
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
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
In arch/x86/mm/ioremap.c (ffffffff810d11e8)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810db1ca)
Location: arch/x86/include/asm/pgtable.h:877
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
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
In arch/x86/mm/ioremap.c (ffffffff810807b1)
Location: arch/x86/include/asm/pgtable.h:648
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat.c (ffffffff81085d45)
Location: arch/x86/include/asm/pgtable.h:648
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:io_reserve_memtype
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
In arch/x86/mm/ioremap.c (ffffffff8106f701)
Location: arch/x86/include/asm/pgtable.h:648
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat.c (ffffffff81074ac5)
Location: arch/x86/include/asm/pgtable.h:648
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:io_reserve_memtype
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
In arch/x86/mm/ioremap.c (ffffffff81080761)
Location: arch/x86/include/asm/pgtable.h:648
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat.c (ffffffff81085cf5)
Location: arch/x86/include/asm/pgtable.h:648
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:io_reserve_memtype
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
In arch/x86/mm/ioremap.c (ffffffff81082881)
Location: arch/x86/include/asm/pgtable.h:648
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
```
In arch/x86/mm/pat.c (ffffffff81087e45)
Location: arch/x86/include/asm/pgtable.h:648
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:io_reserve_memtype
```
</details>
</li>
</ul>

## Differences
