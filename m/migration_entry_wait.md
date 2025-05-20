# Function: <code>migration_entry_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff811f14f0)
Location: mm/migrate.c:239
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:handle_mm_fault
```
**Symbols:**

```
ffffffff811f14f0-ffffffff811f157d: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81211930)
Location: mm/migrate.c:332
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81211930-ffffffff812119ad: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81223ae0)
Location: mm/migrate.c:332
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81223ae0-ffffffff81223b56: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8122f420)
Location: mm/migrate.c:318
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8122f420-ffffffff8122f496: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124cce0)
Location: mm/migrate.c:341
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8124cce0-ffffffff8124cd92: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812707f0)
Location: mm/migrate.c:342
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff812707f0-ffffffff8127089c: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81284e10)
Location: mm/migrate.c:340
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
  - mm/hmm.c:hmm_vma_walk_pmd
```
**Symbols:**

```
ffffffff81284e10-ffffffff81284ebc: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129f480)
Location: mm/migrate.c:338
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8129f480-ffffffff8129f52f: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b0820)
Location: mm/migrate.c:339
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812b0820-ffffffff812b08cf: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e6960)
Location: mm/migrate.c:344
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812e6960-ffffffff812e6a0e: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f1cb0)
Location: mm/migrate.c:340
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812f1cb0-ffffffff812f1d5e: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f7fe0)
Location: mm/migrate.c:314
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812f7fe0-ffffffff812f808b: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81342630)
Location: mm/migrate.c:322
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81342630-ffffffff813426db: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b4a80)
Location: mm/migrate.c:310
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff813b4a80-ffffffff813b4b3e: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81433be0)
Location: mm/migrate.c:325
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81433be0-ffffffff81433cb4: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81469550)
Location: mm/migrate.c:300
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/hmm.c:hmm_vma_handle_pte
```
**Symbols:**

```
ffffffff81469550-ffffffff8146963f: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81498460)
Location: mm/migrate.c:303
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/userfaultfd.c:move_pages_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
**Symbols:**

```
ffffffff81498460-ffffffff81498563: migration_entry_wait (STB_GLOBAL)
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
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff800010350e00)
Location: mm/migrate.c:339
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffff800010350e00-ffff800010350e70: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0552504)
Location: mm/migrate.c:339
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
c0552504-c055256c: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000436d80)
Location: mm/migrate.c:339
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
c000000000436d80-c000000000436e28: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023f7e4)
Location: mm/migrate.c:339
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffe00023f7e4-ffffffe00023f846: migration_entry_wait (STB_GLOBAL)
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
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a8e00)
Location: mm/migrate.c:339
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812a8e00-ffffffff812a8eaf: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129a7c0)
Location: mm/migrate.c:339
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8129a7c0-ffffffff8129a83e: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a6c10)
Location: mm/migrate.c:339
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812a6c10-ffffffff812a6cbf: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void migration_entry_wait(struct mm_struct *mm, pmd_t *pmd, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b6f40)
Location: mm/migrate.c:339
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812b6f40-ffffffff812b6fef: migration_entry_wait (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
