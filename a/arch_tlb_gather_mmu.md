# Function: <code>arch_tlb_gather_mmu</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void arch_tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f25a0)
Location: mm/memory.c:219
Inline: False
Direct callers:
  - mm/memory.c:tlb_gather_mmu
```
**Symbols:**

```
ffffffff811f25a0-ffffffff811f2643: arch_tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void arch_tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81209560)
Location: mm/memory.c:220
Inline: False
Direct callers:
  - mm/memory.c:tlb_gather_mmu
```
**Symbols:**

```
ffffffff81209560-ffffffff8120960d: arch_tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void arch_tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122a400)
Location: mm/memory.c:219
Inline: False
Direct callers:
  - mm/memory.c:tlb_gather_mmu
```
**Symbols:**

```
ffffffff8122a400-ffffffff8122a4ad: arch_tlb_gather_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void arch_tlb_gather_mmu(struct mmu_gather *tlb, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8124d015)
Location: mm/mmu_gather.c:44
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
```
**Symbols:**

```
ffffffff8124ca10-ffffffff8124cac5: arch_tlb_gather_mmu (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
