# Function: <code>huge_ptep_clear_flush</code>

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
In mm/hugetlb.c (ffffffff811ddd3e)
Location: arch/x86/include/asm/hugetlb.h:49
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff811fc03b)
Location: arch/x86/include/asm/hugetlb.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff8120caec)
Location: arch/x86/include/asm/hugetlb.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff8121844d)
Location: arch/x86/include/asm/hugetlb.h:50
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff812332d7)
Location: arch/x86/include/asm/hugetlb.h:51
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff812564ea)
Location: arch/x86/include/asm/hugetlb.h:51
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff8126aa16)
Location: include/asm-generic/hugetlb.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff81285916)
Location: include/asm-generic/hugetlb.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff812954e6)
Location: include/asm-generic/hugetlb.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff812c8bf5)
Location: include/asm-generic/hugetlb.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff812d4780)
Location: include/asm-generic/hugetlb.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff812db52f)
Location: include/asm-generic/hugetlb.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff81322759)
Location: include/asm-generic/hugetlb.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/rmap.c (0)
Location: include/asm-generic/hugetlb.h:87
Inline: True
```
```
In mm/hugetlb.c (ffffffff8138fd26)
Location: include/asm-generic/hugetlb.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
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
In mm/rmap.c (ffffffff813d9463)
Location: include/asm-generic/hugetlb.h:87
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff814106a3)
Location: include/asm-generic/hugetlb.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
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
In mm/rmap.c (ffffffff8140db52)
Location: include/asm-generic/hugetlb.h:94
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81443a67)
Location: include/asm-generic/hugetlb.h:94
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
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
In mm/rmap.c (ffffffff8143a9fa)
Location: include/asm-generic/hugetlb.h:94
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8147dafa)
Location: include/asm-generic/hugetlb.h:94
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void huge_ptep_clear_flush(struct vm_area_struct *vma, long unsigned int addr, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b1740)
Location: arch/arm64/mm/hugetlbpage.c:429
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_cow
```
**Symbols:**

```
ffff8000100b1740-ffff8000100b18d8: huge_ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040cf28)
Location: arch/powerpc/include/asm/hugetlb.h:51
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00023027e)
Location: include/asm-generic/hugetlb.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
</details>
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
In mm/hugetlb.c (ffffffff8128dac6)
Location: include/asm-generic/hugetlb.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff8127f84e)
Location: include/asm-generic/hugetlb.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff8128b8d6)
Location: include/asm-generic/hugetlb.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
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
In mm/hugetlb.c (ffffffff8129b6d8)
Location: include/asm-generic/hugetlb.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
