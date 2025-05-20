# Function: <code>pte_flags_need_flush</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81353db7)
Location: arch/x86/include/asm/tlbflush.h:262
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/huge_memory.c (ffffffff813bddfd)
Location: arch/x86/include/asm/tlbflush.h:262
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
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
In mm/mprotect.c (ffffffff813ce26d)
Location: arch/x86/include/asm/tlbflush.h:263
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/huge_memory.c (ffffffff814406fc)
Location: arch/x86/include/asm/tlbflush.h:263
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
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
In mm/mprotect.c (ffffffff81402d3b)
Location: arch/x86/include/asm/tlbflush.h:276
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/huge_memory.c (ffffffff81475e97)
Location: arch/x86/include/asm/tlbflush.h:276
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
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
In mm/mprotect.c (ffffffff8142f3a8)
Location: arch/x86/include/asm/tlbflush.h:296
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/huge_memory.c (ffffffff814a593c)
Location: arch/x86/include/asm/tlbflush.h:296
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
