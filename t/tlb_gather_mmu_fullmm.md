# Function: <code>tlb_gather_mmu_fullmm</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tlb_gather_mmu_fullmm(struct mmu_gather *tlb, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812ae590)
Location: mm/mmu_gather.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff812ae590-ffffffff812ae5ef: tlb_gather_mmu_fullmm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tlb_gather_mmu_fullmm(struct mmu_gather *tlb, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812efd30)
Location: mm/mmu_gather.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff812efd30-ffffffff812efd8f: tlb_gather_mmu_fullmm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tlb_gather_mmu_fullmm(struct mmu_gather *tlb, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81353230)
Location: mm/mmu_gather.c:313
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff81353230-ffffffff81353299: tlb_gather_mmu_fullmm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tlb_gather_mmu_fullmm(struct mmu_gather *tlb, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff813cd4f0)
Location: mm/mmu_gather.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff813cd4f0-ffffffff813cd550: tlb_gather_mmu_fullmm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tlb_gather_mmu_fullmm(struct mmu_gather *tlb, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81401e50)
Location: mm/mmu_gather.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff81401e50-ffffffff81401eb0: tlb_gather_mmu_fullmm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tlb_gather_mmu_fullmm(struct mmu_gather *tlb, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8142e4a0)
Location: mm/mmu_gather.c:352
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:free_ldt_pgtables
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff8142e4a0-ffffffff8142e500: tlb_gather_mmu_fullmm (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
