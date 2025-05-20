# Function: <code>__follow_pte_pmd</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff811e6900)
Location: mm/memory.c:3775
Inline: True
Direct callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
ffffffff811e6900-ffffffff811e6b81: __follow_pte_pmd.isra.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct *mm, long unsigned int address, long unsigned int *start, long unsigned int *end, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f1a00)
Location: mm/memory.c:4046
Inline: False
Direct callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
ffffffff811f1a00-ffffffff811f1d9a: __follow_pte_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct *mm, long unsigned int address, long unsigned int *start, long unsigned int *end, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81208760)
Location: mm/memory.c:4224
Inline: False
Direct callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
ffffffff81208760-ffffffff81208bc0: __follow_pte_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct *mm, long unsigned int address, long unsigned int *start, long unsigned int *end, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812297a0)
Location: mm/memory.c:4269
Inline: False
Direct callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
ffffffff812297a0-ffffffff81229b99: __follow_pte_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123ccb0)
Location: mm/memory.c:4059
Inline: False
Direct callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
ffffffff8123ccb0-ffffffff8123d068: __follow_pte_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124e910)
Location: mm/memory.c:4108
Inline: False
Direct callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
ffffffff8124e910-ffffffff8124ed0f: __follow_pte_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125ceb0)
Location: mm/memory.c:4133
Inline: False
Direct callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
ffffffff8125ceb0-ffffffff8125d2e7: __follow_pte_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128d450)
Location: mm/memory.c:4498
Inline: False
Direct callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
ffffffff8128d450-ffffffff8128d8d0: __follow_pte_pmd (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f4450)
Location: mm/memory.c:4133
Inline: False
Direct callers:
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
ffff8000102f4450-ffff8000102f477c: __follow_pte_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (c051681c)
Location: mm/memory.c:4133
Inline: True
Direct callers:
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
c051681c-c0516978: __follow_pte_pmd.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bae30)
Location: mm/memory.c:4133
Inline: False
Direct callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
c0000000003bae30-c0000000003bb46c: __follow_pte_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe0002065c8)
Location: mm/memory.c:4133
Inline: False
Direct callers:
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
ffffffe0002065c8-ffffffe00020685c: __follow_pte_pmd (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81255500)
Location: mm/memory.c:4133
Inline: False
Direct callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
ffffffff81255500-ffffffff81255937: __follow_pte_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81247c40)
Location: mm/memory.c:4133
Inline: False
Direct callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
ffffffff81247c40-ffffffff8124802a: __follow_pte_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812532a0)
Location: mm/memory.c:4133
Inline: False
Direct callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
ffffffff812532a0-ffffffff812536d7: __follow_pte_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81262cb0)
Location: mm/memory.c:4133
Inline: False
Direct callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:follow_pte_pmd
```
**Symbols:**

```
ffffffff81262cb0-ffffffff812630ae: __follow_pte_pmd (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmu_notifier_range *range</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *end</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, address, start, end, ptepp, pmdpp, ptlp</code> ➡️ <code>mm, address, range, ptepp, pmdpp, ptlp</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
