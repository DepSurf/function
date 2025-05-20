# Function: <code>pgd_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070ea0)
Location: arch/x86/mm/pgtable.c:394
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81070ea0-ffffffff81070f45: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070de0)
Location: arch/x86/mm/pgtable.c:398
Inline: False
```
**Symbols:**

```
ffffffff81070de0-ffffffff81070e8c: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81074960)
Location: arch/x86/mm/pgtable.c:398
Inline: False
```
**Symbols:**

```
ffffffff81074960-ffffffff81074a06: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81073eb0)
Location: arch/x86/mm/pgtable.c:408
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81073eb0-ffffffff81073f56: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810798e0)
Location: arch/x86/mm/pgtable.c:410
Inline: False
```
**Symbols:**

```
ffffffff810798e0-ffffffff81079989: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107c4b0)
Location: arch/x86/mm/pgtable.c:415
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff8107c4b0-ffffffff8107c559: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81082ea0)
Location: arch/x86/mm/pgtable.c:481
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff81082ea0-ffffffff81082f4e: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086b00)
Location: arch/x86/mm/pgtable.c:468
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff81086b00-ffffffff81086baa: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810877f0)
Location: arch/x86/mm/pgtable.c:464
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810877f0-ffffffff8108789a: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089c00)
Location: arch/x86/mm/pgtable.c:471
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff81089c00-ffffffff81089caa: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089e80)
Location: arch/x86/mm/pgtable.c:471
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff81089e80-ffffffff81089f2a: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108aae0)
Location: arch/x86/mm/pgtable.c:471
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff8108aae0-ffffffff8108ab8a: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8109a080)
Location: arch/x86/mm/pgtable.c:471
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff8109a080-ffffffff8109a12a: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ad140)
Location: arch/x86/mm/pgtable.c:471
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810ad140-ffffffff810ad208: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c71e0)
Location: arch/x86/mm/pgtable.c:475
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810c71e0-ffffffff810c72a8: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ca930)
Location: arch/x86/mm/pgtable.c:475
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810ca930-ffffffff810ca9f8: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d2e80)
Location: arch/x86/mm/pgtable.c:487
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810d2e80-ffffffff810d2f48: pgd_free (STB_GLOBAL)
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
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/pgd.c (ffff8000100ae170)
Location: arch/arm64/mm/pgd.c:30
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffff8000100ae170-ffff8000100ae1a0: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/pgd.c (c031f92c)
Location: arch/arm/mm/pgd.c:116
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
c031f92c-c031f9fc: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000137534)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:81
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:__mmdrop
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
In kernel/fork.c (ffffffe0000be7f4)
Location: arch/riscv/include/asm/pgalloc.h:57
Inline: True
Inline callers:
  - kernel/fork.c:__mmdrop
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
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810867f0)
Location: arch/x86/mm/pgtable.c:464
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810867f0-ffffffff8108689a: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810754e0)
Location: arch/x86/mm/pgtable.c:464
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810754e0-ffffffff8107557e: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810867a0)
Location: arch/x86/mm/pgtable.c:464
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810867a0-ffffffff8108684a: pgd_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pgd_free(struct mm_struct *mm, pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810888d0)
Location: arch/x86/mm/pgtable.c:464
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff810888d0-ffffffff81088978: pgd_free (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pgd_t *pgd_base</code>
</li>
<li>
<b>Param removed. </b>
<code>pgd_t *pgd</code>
</li>
</ul>
</details>
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
