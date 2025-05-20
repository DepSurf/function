# Function: <code>pmd_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_clear(pmd_t *pmdp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d4df)
Location: arch/x86/include/asm/paravirt.h:650
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c4e6)
Location: arch/x86/include/asm/paravirt.h:650
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pte_range
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810713d5)
Location: arch/x86/include/asm/paravirt.h:650
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In mm/memory.c (ffffffff811bce48)
Location: arch/x86/include/asm/paravirt.h:650
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811d0425)
Location: arch/x86/include/asm/paravirt.h:650
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
**Symbols:**

```
ffffffff8107d4df-ffffffff8107d4fe: pmd_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_clear(pmd_t *pmdp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107efbc)
Location: arch/x86/include/asm/paravirt.h:623
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c4f0)
Location: arch/x86/include/asm/paravirt.h:623
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810712c1)
Location: arch/x86/include/asm/paravirt.h:623
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In mm/memory.c (ffffffff811d7bf8)
Location: arch/x86/include/asm/paravirt.h:623
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811ed5d5)
Location: arch/x86/include/asm/paravirt.h:623
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
**Symbols:**

```
ffffffff8107efbc-ffffffff8107efdb: pmd_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_clear(pmd_t *pmdp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8108366c)
Location: arch/x86/include/asm/paravirt.h:614
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81070190)
Location: arch/x86/include/asm/paravirt.h:614
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81074e41)
Location: arch/x86/include/asm/paravirt.h:614
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In mm/memory.c (ffffffff811e7900)
Location: arch/x86/include/asm/paravirt.h:614
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811f79c5)
Location: arch/x86/include/asm/paravirt.h:614
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
**Symbols:**

```
ffffffff8108366c-ffffffff8108368b: pmd_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_clear(pmd_t *pmdp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106ce5d)
Location: arch/x86/include/asm/paravirt.h:661
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pageattr.c (ffffffff8106f8b2)
Location: arch/x86/include/asm/paravirt.h:661
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810743f2)
Location: arch/x86/include/asm/paravirt.h:661
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In mm/memory.c (ffffffff811f2a5b)
Location: arch/x86/include/asm/paravirt.h:661
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81202b55)
Location: arch/x86/include/asm/paravirt.h:661
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
**Symbols:**

```
ffffffff8106ce5d-ffffffff8106ce7c: pmd_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_clear(pmd_t *pmdp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81071b7c)
Location: arch/x86/include/asm/paravirt.h:625
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/pageattr.c (ffffffff81074cce)
Location: arch/x86/include/asm/paravirt.h:625
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81079e95)
Location: arch/x86/include/asm/paravirt.h:625
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In mm/memory.c (ffffffff81209b63)
Location: arch/x86/include/asm/paravirt.h:625
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8121b8c5)
Location: arch/x86/include/asm/paravirt.h:625
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
**Symbols:**

```
ffffffff81071b7c-ffffffff81071b9b: pmd_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_clear(pmd_t *pmdp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81074844)
Location: arch/x86/include/asm/paravirt.h:630
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81077721)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107cd10)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In mm/memory.c (ffffffff8122a96c)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8123d6a5)
Location: arch/x86/include/asm/paravirt.h:630
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
**Symbols:**

```
ffffffff81074844-ffffffff81074863: pmd_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_clear(pmd_t *pmdp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107a734)
Location: arch/x86/include/asm/paravirt.h:608
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107ded1)
Location: arch/x86/include/asm/paravirt.h:608
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81083721)
Location: arch/x86/include/asm/paravirt.h:608
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In mm/memory.c (ffffffff8123dd1c)
Location: arch/x86/include/asm/paravirt.h:608
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/mremap.c (ffffffff8124f47d)
Location: arch/x86/include/asm/paravirt.h:608
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81251bf5)
Location: arch/x86/include/asm/paravirt.h:608
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
**Symbols:**

```
ffffffff8107a734-ffffffff8107a753: pmd_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_clear(pmd_t *pmdp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e48b)
Location: arch/x86/include/asm/paravirt.h:609
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff810817d5)
Location: arch/x86/include/asm/paravirt.h:609
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81087392)
Location: arch/x86/include/asm/paravirt.h:609
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In mm/memory.c (ffffffff8124e3fd)
Location: arch/x86/include/asm/paravirt.h:609
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812617cb)
Location: arch/x86/include/asm/paravirt.h:609
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81263ec6)
Location: arch/x86/include/asm/paravirt.h:609
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
**Symbols:**

```
ffffffff8107e48b-ffffffff8107e4aa: pmd_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_clear(pmd_t *pmdp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107f51b)
Location: arch/x86/include/asm/paravirt.h:597
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff81082895)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81088082)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In mm/memory.c (ffffffff8125c96d)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff8126ff89)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81272736)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
**Symbols:**

```
ffffffff8107f51b-ffffffff8107f53a: pmd_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_clear(pmd_t *pmdp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81085efe)
Location: arch/x86/include/asm/paravirt.h:611
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a51f)
Location: arch/x86/include/asm/paravirt.h:611
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c85e)
Location: arch/x86/include/asm/paravirt.h:611
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pte_range
```
```
In mm/memory.c (ffffffff8128c25d)
Location: arch/x86/include/asm/paravirt.h:611
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff8129fe6e)
Location: arch/x86/include/asm/paravirt.h:611
Inline: True
Inline callers:
  - mm/mremap.c:move_normal_pmd
```
```
In mm/pgtable-generic.c (ffffffff812a34e6)
Location: arch/x86/include/asm/paravirt.h:611
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
**Symbols:**

```
ffffffff81085efe-ffffffff81085f1d: pmd_clear (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81c3ccb3)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a7ef)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c26e)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff812971de)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812ab2e9)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812aedd6)
Location: arch/x86/include/asm/paravirt.h:510
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff81c2efa3)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b41f)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d50e)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff8129d018)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812b06e8)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812b4306)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff81d4d6a4)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a9bf)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109cd8c)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff812de463)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812f2006)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812f5ee6)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff81f1d3c8)
Location: arch/x86/include/asm/paravirt.h:547
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pgtable.c (ffffffff810adcad)
Location: arch/x86/include/asm/paravirt.h:547
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b05c3)
Location: arch/x86/include/asm/paravirt.h:547
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff8133e532)
Location: arch/x86/include/asm/paravirt.h:547
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff81355d75)
Location: arch/x86/include/asm/paravirt.h:547
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81359e64)
Location: arch/x86/include/asm/paravirt.h:547
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff820c590c)
Location: arch/x86/include/asm/paravirt.h:547
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7ed3)
Location: arch/x86/include/asm/paravirt.h:547
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cac7b)
Location: arch/x86/include/asm/paravirt.h:547
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff813b559e)
Location: arch/x86/include/asm/paravirt.h:547
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff813d039b)
Location: arch/x86/include/asm/paravirt.h:547
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff813d4884)
Location: arch/x86/include/asm/paravirt.h:547
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff8214997c)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb613)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce2ab)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff813eac59)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff8140510b)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81409254)
Location: arch/x86/include/asm/paravirt.h:542
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
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
In arch/x86/mm/init_64.c (ffffffff8222c43c)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pgtable.c (ffffffff810d3b73)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d698b)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
```
```
In mm/memory.c (ffffffff81417459)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff814315eb)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81435a44)
Location: arch/x86/include/asm/paravirt.h:540
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff8000100af428)
Location: arch/arm64/include/asm/pgtable.h:486
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:pmd_clear_huge
```
```
In virt/kvm/arm/mmu.c (ffff8000100cb35c)
Location: arch/arm64/include/asm/pgtable.h:486
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In mm/memory.c (ffff8000102f5534)
Location: arch/arm64/include/asm/pgtable.h:486
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffff800010307f9c)
Location: arch/arm64/include/asm/pgtable.h:486
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/hash_pgtable.c (c00000000008b9f4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:863
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_pgtable.c:hash__pmdp_collapse_flush
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000095b7c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:863
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_free_pte_page
  - arch/powerpc/mm/book3s64/radix_pgtable.c:pmd_clear_huge
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__pmdp_collapse_flush
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
```
```
In mm/memory.c (c0000000003bc730)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:863
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (c0000000003d755c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:863
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000206ac0)
Location: arch/riscv/include/asm/pgtable.h:143
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffe000212e66)
Location: arch/riscv/include/asm/pgtable.h:143
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_clear(pmd_t *pmdp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e51b)
Location: arch/x86/include/asm/paravirt.h:597
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff81081895)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81087082)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In mm/memory.c (ffffffff81254fbd)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff812685d9)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8126ad86)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
**Symbols:**

```
ffffffff8107e51b-ffffffff8107e53a: pmd_clear (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_clear(pmd_t *pmdp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e4cb)
Location: arch/x86/include/asm/paravirt.h:597
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff81081845)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81087032)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In mm/memory.c (ffffffff81252d5d)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff81266379)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff81268b26)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
**Symbols:**

```
ffffffff8107e4cb-ffffffff8107e4ea: pmd_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pmd_clear(pmd_t *pmdp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810805bb)
Location: arch/x86/include/asm/paravirt.h:597
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff81083965)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81089162)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In mm/memory.c (ffffffff812626bd)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
```
```
In mm/mremap.c (ffffffff81275d0a)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff812784b6)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
**Symbols:**

```
ffffffff810805bb-ffffffff810805da: pmd_clear (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
