# Function: <code>set_pud_at</code>

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
In mm/huge_memory.c (ffffffff81233455)
Location: arch/x86/include/asm/paravirt.h:486
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
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
In mm/huge_memory.c (ffffffff8124f738)
Location: arch/x86/include/asm/pgtable.h:995
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/huge_memory.c (ffffffff81275240)
Location: arch/x86/include/asm/pgtable.h:1046
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/huge_memory.c (ffffffff8128a1ad)
Location: arch/x86/include/asm/pgtable.h:1071
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/huge_memory.c (ffffffff812a4dce)
Location: arch/x86/include/asm/pgtable.h:1091
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/huge_memory.c (ffffffff812b628e)
Location: arch/x86/include/asm/pgtable.h:1091
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/huge_memory.c (ffffffff812eb3ae)
Location: arch/x86/include/asm/pgtable.h:1051
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
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
In mm/mremap.c (ffffffff812ab099)
Location: arch/x86/include/asm/pgtable.h:1047
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f7dfd)
Location: arch/x86/include/asm/pgtable.h:1047
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
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
In mm/mremap.c (ffffffff812b0599)
Location: arch/x86/include/asm/pgtable.h:1047
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fe3ec)
Location: arch/x86/include/asm/pgtable.h:1047
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
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
In mm/mremap.c (ffffffff812f28c0)
Location: arch/x86/include/asm/pgtable.h:1018
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff81347f8c)
Location: arch/x86/include/asm/pgtable.h:1018
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
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
In mm/mremap.c (ffffffff81356663)
Location: arch/x86/include/asm/pgtable.h:1018
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff813bc8ba)
Location: arch/x86/include/asm/pgtable.h:1018
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
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
In mm/mremap.c (ffffffff813d0c86)
Location: arch/x86/include/asm/pgtable.h:1036
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff8143ee7d)
Location: arch/x86/include/asm/pgtable.h:1036
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
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
In mm/mremap.c (ffffffff814056bf)
Location: arch/x86/include/asm/pgtable.h:1037
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff81474643)
Location: arch/x86/include/asm/pgtable.h:1037
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
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
In mm/mremap.c (ffffffff81431be0)
Location: arch/x86/include/asm/pgtable.h:1252
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff814a3c26)
Location: arch/x86/include/asm/pgtable.h:1252
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ae86e)
Location: arch/x86/include/asm/pgtable.h:1091
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/huge_memory.c (ffffffff8129fdf8)
Location: arch/x86/include/asm/pgtable.h:1091
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/huge_memory.c (ffffffff812ac67e)
Location: arch/x86/include/asm/pgtable.h:1091
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/huge_memory.c (ffffffff812bc9fb)
Location: arch/x86/include/asm/pgtable.h:1091
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
</ul>

## Differences
