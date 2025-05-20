# Function: <code>pud_same</code>

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
In arch/x86/mm/pgtable.c (ffffffff81073fd6)
Location: include/asm-generic/pgtable.h:376
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff81233511)
Location: include/asm-generic/pgtable.h:376
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
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
In arch/x86/mm/pgtable.c (ffffffff81079a06)
Location: include/asm-generic/pgtable.h:377
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff81250df1)
Location: include/asm-generic/pgtable.h:377
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
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
In arch/x86/mm/pgtable.c (ffffffff8107c5d5)
Location: include/asm-generic/pgtable.h:384
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff812752c9)
Location: include/asm-generic/pgtable.h:384
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_same(pud_t pud_a, pud_t pud_b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107a7c5)
Location: include/asm-generic/pgtable.h:383
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff81082fd5)
Location: include/asm-generic/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff8128a229)
Location: include/asm-generic/pgtable.h:383
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
```
**Symbols:**

```
ffffffff8107a7c5-ffffffff8107a7e8: pud_same (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_same(pud_t pud_a, pud_t pud_b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e51c)
Location: include/asm-generic/pgtable.h:383
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff81086c45)
Location: include/asm-generic/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff812a4e49)
Location: include/asm-generic/pgtable.h:383
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
```
**Symbols:**

```
ffffffff8107e51c-ffffffff8107e53f: pud_same (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_same(pud_t pud_a, pud_t pud_b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107f5ac)
Location: include/asm-generic/pgtable.h:383
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff81087935)
Location: include/asm-generic/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff812b6309)
Location: include/asm-generic/pgtable.h:383
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
```
**Symbols:**

```
ffffffff8107f5ac-ffffffff8107f5cf: pud_same (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81bc48fb)
Location: include/linux/pgtable.h:542
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff81089d65)
Location: include/linux/pgtable.h:542
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff812eb429)
Location: include/linux/pgtable.h:542
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
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
In arch/x86/mm/init_64.c (ffffffff81c3d7f4)
Location: include/linux/pgtable.h:597
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff81089fe9)
Location: include/linux/pgtable.h:597
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff812f64e9)
Location: include/linux/pgtable.h:597
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
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
In arch/x86/mm/init_64.c (ffffffff81c2fb9d)
Location: include/linux/pgtable.h:597
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff8108ac49)
Location: include/linux/pgtable.h:597
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff812fc899)
Location: include/linux/pgtable.h:597
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
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
In arch/x86/mm/init_64.c (ffffffff81d4e2ec)
Location: include/linux/pgtable.h:616
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a1e9)
Location: include/linux/pgtable.h:616
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff81346719)
Location: include/linux/pgtable.h:616
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
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
In arch/x86/mm/init_64.c (ffffffff81f1e0a9)
Location: include/linux/pgtable.h:649
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad309)
Location: include/linux/pgtable.h:649
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff813bc939)
Location: include/linux/pgtable.h:649
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
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
In arch/x86/mm/init_64.c (ffffffff820c6773)
Location: include/linux/pgtable.h:685
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810c73f4)
Location: include/linux/pgtable.h:685
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff8143ef15)
Location: include/linux/pgtable.h:685
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
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
In arch/x86/mm/init_64.c (ffffffff8214a7c1)
Location: include/linux/pgtable.h:697
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810cab44)
Location: include/linux/pgtable.h:697
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff814746d8)
Location: include/linux/pgtable.h:697
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
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
In arch/x86/mm/init_64.c (ffffffff8222d271)
Location: include/linux/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810d3094)
Location: include/linux/pgtable.h:827
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff814a3cd8)
Location: include/linux/pgtable.h:827
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_same(pud_t pud_a, pud_t pud_b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e5ac)
Location: include/asm-generic/pgtable.h:383
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff81086935)
Location: include/asm-generic/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff812ae8e9)
Location: include/asm-generic/pgtable.h:383
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
```
**Symbols:**

```
ffffffff8107e5ac-ffffffff8107e5cf: pud_same (STB_LOCAL)
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
In arch/x86/mm/init_64.c (0)
Location: include/asm-generic/pgtable.h:383
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: include/asm-generic/pgtable.h:383
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:383
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_same(pud_t pud_a, pud_t pud_b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e55c)
Location: include/asm-generic/pgtable.h:383
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff810868e5)
Location: include/asm-generic/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff812ac6f9)
Location: include/asm-generic/pgtable.h:383
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
```
**Symbols:**

```
ffffffff8107e55c-ffffffff8107e57f: pud_same (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pud_same(pud_t pud_a, pud_t pud_b);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8108064c)
Location: include/asm-generic/pgtable.h:383
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pgtable.c (ffffffff81088a15)
Location: include/asm-generic/pgtable.h:383
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pudp_set_access_flags
```
```
In mm/huge_memory.c (ffffffff812bca79)
Location: include/asm-generic/pgtable.h:383
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
```
**Symbols:**

```
ffffffff8108064c-ffffffff8108066f: pud_same (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
