# Function: <code>__khugepaged_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f7830)
Location: mm/huge_memory.c:2094
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff811f7830-ffffffff811f795e: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8121c980)
Location: mm/khugepaged.c:395
Inline: False
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff8121c980-ffffffff8121cab0: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8122ef80)
Location: mm/khugepaged.c:397
Inline: False
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff8122ef80-ffffffff8122f0b0: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8123a7c0)
Location: mm/khugepaged.c:399
Inline: False
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff8123a7c0-ffffffff8123a8f0: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8125a050)
Location: mm/khugepaged.c:400
Inline: False
Direct callers:
  - mm/shmem.c:shmem_zero_setup
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff8125a050-ffffffff8125a180: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8127dd70)
Location: mm/khugepaged.c:400
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
  - mm/shmem.c:shmem_zero_setup
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff8127dd70-ffffffff8127dea8: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81292450)
Location: mm/khugepaged.c:420
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81292450-ffffffff81292588: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812ace40)
Location: mm/khugepaged.c:420
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812ace40-ffffffff812acf6f: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812bda40)
Location: mm/khugepaged.c:431
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812bda40-ffffffff812bdb6f: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812f3240)
Location: mm/khugepaged.c:459
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_mmap
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812f3240-ffffffff812f336f: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fe9a0)
Location: mm/khugepaged.c:474
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_zero_setup
  - mm/shmem.c:shmem_mmap
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812fe9a0-ffffffff812feacf: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81305610)
Location: mm/khugepaged.c:472
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_zero_setup
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81305610-ffffffff8130573f: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134f470)
Location: mm/khugepaged.c:476
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_zero_setup
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff8134f470-ffffffff8134f5a1: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c76d0)
Location: mm/khugepaged.c:477
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:hugepage_madvise
```
**Symbols:**

```
ffffffff813c76d0-ffffffff813c77fa: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8144b6c0)
Location: mm/khugepaged.c:416
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff8144b6c0-ffffffff8144b7ea: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81480f40)
Location: mm/khugepaged.c:419
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81480f40-ffffffff8148106a: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814aff30)
Location: mm/khugepaged.c:413
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff814aff30-ffffffff814b005a: __khugepaged_enter (STB_GLOBAL)
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
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffff80001035ef00)
Location: mm/khugepaged.c:431
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffff80001035ef00-ffff80001035f0cc: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c0000000004499e0)
Location: mm/khugepaged.c:431
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/shmem.c:shmem_zero_setup
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
c0000000004499e0-c000000000449c10: __khugepaged_enter (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b6020)
Location: mm/khugepaged.c:431
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812b6020-ffffffff812b614f: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a7210)
Location: mm/khugepaged.c:431
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812a7210-ffffffff812a733f: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b3e30)
Location: mm/khugepaged.c:431
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812b3e30-ffffffff812b3f5f: __khugepaged_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __khugepaged_enter(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812c42c0)
Location: mm/khugepaged.c:431
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812c42c0-ffffffff812c43f5: __khugepaged_enter (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
