# Function: <code>pmd_migration_entry_wait</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124ce30)
Location: mm/migrate.c:357
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff8124ce30-ffffffff8124d04f: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81270930)
Location: mm/migrate.c:358
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
```
**Symbols:**

```
ffffffff81270930-ffffffff81270b44: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81284f50)
Location: mm/migrate.c:356
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff81284f50-ffffffff812850dd: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129f5c0)
Location: mm/migrate.c:354
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff8129f5c0-ffffffff8129f737: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b0960)
Location: mm/migrate.c:355
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812b0960-ffffffff812b0ad7: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e6aa0)
Location: mm/migrate.c:360
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812e6aa0-ffffffff812e6c17: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f1df0)
Location: mm/migrate.c:356
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812f1df0-ffffffff812f1f67: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f8120)
Location: mm/migrate.c:330
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812f8120-ffffffff812f82bf: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81342780)
Location: mm/migrate.c:338
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff81342780-ffffffff8134292b: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b4cd0)
Location: mm/migrate.c:341
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff813b4cd0-ffffffff813b4e42: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81433e80)
Location: mm/migrate.c:356
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff81433e80-ffffffff81433ff2: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff814697d0)
Location: mm/migrate.c:361
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff814697d0-ffffffff81469933: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81498700)
Location: mm/migrate.c:364
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff81498700-ffffffff81498863: pmd_migration_entry_wait (STB_GLOBAL)
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
In mm/gup.c (0)
Location: include/linux/swapops.h:288
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:288
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:288
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/swapops.h:288
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:288
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:288
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000436ee0)
Location: mm/migrate.c:355
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
c000000000436ee0-c0000000004370d4: pmd_migration_entry_wait (STB_GLOBAL)
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
In mm/gup.c (0)
Location: include/linux/swapops.h:288
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/swapops.h:288
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:288
Inline: True
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
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a8f40)
Location: mm/migrate.c:355
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812a8f40-ffffffff812a90b7: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129a8d0)
Location: mm/migrate.c:355
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff8129a8d0-ffffffff8129aa2d: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a6d50)
Location: mm/migrate.c:355
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812a6d50-ffffffff812a6ec7: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pmd_migration_entry_wait(struct mm_struct *mm, pmd_t *pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b7080)
Location: mm/migrate.c:355
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812b7080-ffffffff812b71f8: pmd_migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
