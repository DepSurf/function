# Function: <code>pud_set_flags</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81233537)
Location: arch/x86/include/asm/pgtable.h:393
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/huge_memory.c (ffffffff81250e19)
Location: arch/x86/include/asm/pgtable.h:408
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff81077e88)
Location: arch/x86/include/asm/pgtable.h:413
Inline: True
```
```
In mm/huge_memory.c (ffffffff812752e5)
Location: arch/x86/include/asm/pgtable.h:413
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff8107e638)
Location: arch/x86/include/asm/pgtable.h:415
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128a245)
Location: arch/x86/include/asm/pgtable.h:415
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff81081f2f)
Location: arch/x86/include/asm/pgtable.h:432
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a4e65)
Location: arch/x86/include/asm/pgtable.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff81082fef)
Location: arch/x86/include/asm/pgtable.h:432
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b6325)
Location: arch/x86/include/asm/pgtable.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108c5c2)
Location: arch/x86/include/asm/pgtable.h:471
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff812eb445)
Location: arch/x86/include/asm/pgtable.h:471
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108c862)
Location: arch/x86/include/asm/pgtable.h:470
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff812f6505)
Location: arch/x86/include/asm/pgtable.h:470
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108d282)
Location: arch/x86/include/asm/pgtable.h:470
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff812fc8b5)
Location: arch/x86/include/asm/pgtable.h:470
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/pat/set_memory.c (ffffffff8109cb05)
Location: arch/x86/include/asm/pgtable.h:441
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff81346735)
Location: arch/x86/include/asm/pgtable.h:441
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/pat/set_memory.c (ffffffff810b030a)
Location: arch/x86/include/asm/pgtable.h:444
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff813bc953)
Location: arch/x86/include/asm/pgtable.h:444
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/pat/set_memory.c (ffffffff810ca991)
Location: arch/x86/include/asm/pgtable.h:461
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff8143ef40)
Location: arch/x86/include/asm/pgtable.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/pat/set_memory.c (ffffffff810cdfbd)
Location: arch/x86/include/asm/pgtable.h:462
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff81474703)
Location: arch/x86/include/asm/pgtable.h:462
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/pat/set_memory.c (ffffffff810d669d)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
```
```
In mm/huge_memory.c (ffffffff814a3d03)
Location: arch/x86/include/asm/pgtable.h:602
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff81081fef)
Location: arch/x86/include/asm/pgtable.h:432
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ae905)
Location: arch/x86/include/asm/pgtable.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff81070d00)
Location: arch/x86/include/asm/pgtable.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pgd
```
```
In mm/huge_memory.c (ffffffff8129fe6e)
Location: arch/x86/include/asm/pgtable.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff81081f9f)
Location: arch/x86/include/asm/pgtable.h:432
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ac715)
Location: arch/x86/include/asm/pgtable.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In arch/x86/mm/pageattr.c (ffffffff810840bf)
Location: arch/x86/include/asm/pgtable.h:432
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bca95)
Location: arch/x86/include/asm/pgtable.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:follow_devmap_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
</ul>

## Differences
