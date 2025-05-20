# Function: <code>follow_pte_pmd</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e6b90)
Location: mm/memory.c:3834
Inline: False
```
**Symbols:**

```
ffffffff811e6b90-ffffffff811e6ba4: follow_pte_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, long unsigned int *start, long unsigned int *end, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f1da0)
Location: mm/memory.c:4123
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff811f1da0-ffffffff811f1db3: follow_pte_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, long unsigned int *start, long unsigned int *end, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81208bc0)
Location: mm/memory.c:4301
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff81208bc0-ffffffff81208bd3: follow_pte_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, long unsigned int *start, long unsigned int *end, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81229ba0)
Location: mm/memory.c:4346
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff81229ba0-ffffffff81229bb3: follow_pte_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123d070)
Location: mm/memory.c:4136
Inline: False
Direct callers:
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff8123d070-ffffffff8123d080: follow_pte_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124ed10)
Location: mm/memory.c:4187
Inline: False
Direct callers:
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff8124ed10-ffffffff8124ed20: follow_pte_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125d2f0)
Location: mm/memory.c:4212
Inline: False
Direct callers:
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff8125d2f0-ffffffff8125d300: follow_pte_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128d8d0)
Location: mm/memory.c:4577
Inline: False
Direct callers:
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff8128d8d0-ffffffff8128d8e0: follow_pte_pmd (STB_GLOBAL)
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
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f4780)
Location: mm/memory.c:4212
Inline: False
Direct callers:
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffff8000102f4780-ffff8000102f47e4: follow_pte_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0516a34)
Location: mm/memory.c:4212
Inline: False
```
**Symbols:**

```
c0516a34-c0516a60: follow_pte_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bb470)
Location: mm/memory.c:4212
Inline: False
Direct callers:
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
c0000000003bb470-c0000000003bb484: follow_pte_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020685c)
Location: mm/memory.c:4212
Inline: False
Direct callers:
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffe00020685c-ffffffe0002068ae: follow_pte_pmd (STB_GLOBAL)
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
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81255940)
Location: mm/memory.c:4212
Inline: False
Direct callers:
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff81255940-ffffffff81255950: follow_pte_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81248030)
Location: mm/memory.c:4212
Inline: False
Direct callers:
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff81248030-ffffffff81248040: follow_pte_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812536e0)
Location: mm/memory.c:4212
Inline: False
Direct callers:
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff812536e0-ffffffff812536f0: follow_pte_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int follow_pte_pmd(struct mm_struct *mm, long unsigned int address, struct mmu_notifier_range *range, pte_t **ptepp, pmd_t **pmdpp, spinlock_t **ptlp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812630b0)
Location: mm/memory.c:4212
Inline: False
Direct callers:
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff812630b0-ffffffff812630c0: follow_pte_pmd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int *start</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int *end</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, address, ptepp, pmdpp, ptlp</code> ➡️ <code>mm, address, start, end, ptepp, pmdpp, ptlp</code>
</li>
</ul>
</details>
</li>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
