# Function: <code>pmdp_huge_get_and_clear</code>

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
In mm/pgtable-generic.c (ffffffff811d06cd)
Location: arch/x86/include/asm/pgtable.h:830
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
```
```
In mm/huge_memory.c (ffffffff811f68f1)
Location: arch/x86/include/asm/pgtable.h:830
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81278f68)
Location: arch/x86/include/asm/pgtable.h:830
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/pgtable-generic.c (ffffffff811ed83a)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
```
```
In mm/huge_memory.c (ffffffff81215ba8)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff812a5823)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/pgtable-generic.c (ffffffff811f7c0a)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
```
```
In mm/huge_memory.c (ffffffff812281c8)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/proc/task_mmu.c (ffffffff812bb16d)
Location: arch/x86/include/asm/pgtable.h:881
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In mm/pgtable-generic.c (ffffffff81202bea)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff8123422a)
Location: arch/x86/include/asm/pgtable.h:1080
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff8121b94a)
Location: arch/x86/include/asm/pgtable.h:1086
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff81251e12)
Location: arch/x86/include/asm/pgtable.h:1086
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff8123d725)
Location: arch/x86/include/asm/pgtable.h:1137
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812763a9)
Location: arch/x86/include/asm/pgtable.h:1137
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff81251c75)
Location: arch/x86/include/asm/pgtable.h:1162
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff8128b222)
Location: arch/x86/include/asm/pgtable.h:1162
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff81264245)
Location: arch/x86/include/asm/pgtable.h:1182
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812a5e34)
Location: arch/x86/include/asm/pgtable.h:1182
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff81272ab5)
Location: arch/x86/include/asm/pgtable.h:1182
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812b72f4)
Location: arch/x86/include/asm/pgtable.h:1182
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff812a3585)
Location: arch/x86/include/asm/pgtable.h:1142
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ec494)
Location: arch/x86/include/asm/pgtable.h:1142
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff812aee65)
Location: arch/x86/include/asm/pgtable.h:1138
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f751a)
Location: arch/x86/include/asm/pgtable.h:1138
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff812b4395)
Location: arch/x86/include/asm/pgtable.h:1138
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fd9d9)
Location: arch/x86/include/asm/pgtable.h:1138
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff812f5f75)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
```
```
In mm/huge_memory.c (ffffffff81347579)
Location: arch/x86/include/asm/pgtable.h:1109
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff81359f25)
Location: arch/x86/include/asm/pgtable.h:1112
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bd877)
Location: arch/x86/include/asm/pgtable.h:1112
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff813d4965)
Location: arch/x86/include/asm/pgtable.h:1130
Inline: True
```
```
In mm/huge_memory.c (ffffffff8144008b)
Location: arch/x86/include/asm/pgtable.h:1130
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff81409335)
Location: arch/x86/include/asm/pgtable.h:1131
Inline: True
```
```
In mm/huge_memory.c (ffffffff814758fc)
Location: arch/x86/include/asm/pgtable.h:1131
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff81435b25)
Location: arch/x86/include/asm/pgtable.h:1350
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a52cc)
Location: arch/x86/include/asm/pgtable.h:1350
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffff800010308214)
Location: arch/arm64/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/huge_memory.c (ffff800010357f90)
Location: arch/arm64/include/asm/pgtable.h:765
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (c0000000003d73dc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1246
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/huge_memory.c (c000000000440614)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1246
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
</details>
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
In mm/pgtable-generic.c (ffffffff8126b105)
Location: arch/x86/include/asm/pgtable.h:1182
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812af8d4)
Location: arch/x86/include/asm/pgtable.h:1182
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff8125d115)
Location: arch/x86/include/asm/pgtable.h:1182
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812a0dee)
Location: arch/x86/include/asm/pgtable.h:1182
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff81268ea5)
Location: arch/x86/include/asm/pgtable.h:1182
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812ad6e4)
Location: arch/x86/include/asm/pgtable.h:1182
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
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
In mm/pgtable-generic.c (ffffffff81278835)
Location: arch/x86/include/asm/pgtable.h:1182
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
```
```
In mm/huge_memory.c (ffffffff812bda64)
Location: arch/x86/include/asm/pgtable.h:1182
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
</details>
</li>
</ul>

## Differences
