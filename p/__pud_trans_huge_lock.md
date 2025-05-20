# Function: <code>__pud_trans_huge_lock</code>

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
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812345a0)
Location: mm/huge_memory.c:1852
Inline: False
Direct callers:
  - mm/huge_memory.c:zap_huge_pud
```
**Symbols:**

```
ffffffff812345a0-ffffffff81234605: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812524a0)
Location: mm/huge_memory.c:1959
Inline: False
Direct callers:
  - mm/huge_memory.c:zap_huge_pud
```
**Symbols:**

```
ffffffff812524a0-ffffffff81252505: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812768c0)
Location: mm/huge_memory.c:1947
Inline: False
Direct callers:
  - mm/huge_memory.c:zap_huge_pud
```
**Symbols:**

```
ffffffff812768c0-ffffffff81276927: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128b7d0)
Location: mm/huge_memory.c:1967
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/huge_memory.c:zap_huge_pud
```
**Symbols:**

```
ffffffff8128b7d0-ffffffff8128b837: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a63e0)
Location: mm/huge_memory.c:2025
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/huge_memory.c:zap_huge_pud
```
**Symbols:**

```
ffffffff812a63e0-ffffffff812a6446: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b78b0)
Location: mm/huge_memory.c:2030
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/huge_memory.c:zap_huge_pud
```
**Symbols:**

```
ffffffff812b78b0-ffffffff812b7916: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812eca70)
Location: mm/huge_memory.c:1903
Inline: False
Direct callers:
  - mm/huge_memory.c:zap_huge_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff812eca70-ffffffff812ecad6: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f7b00)
Location: mm/huge_memory.c:1918
Inline: False
Direct callers:
  - mm/huge_memory.c:zap_huge_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff812f7b00-ffffffff812f7b66: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fe0b0)
Location: mm/huge_memory.c:1925
Inline: False
Direct callers:
  - mm/huge_memory.c:zap_huge_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff812fe0b0-ffffffff812fe116: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81347c50)
Location: mm/huge_memory.c:1848
Inline: False
Direct callers:
  - mm/huge_memory.c:zap_huge_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff81347c50-ffffffff81347cb6: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813be0c0)
Location: mm/huge_memory.c:1874
Inline: False
Direct callers:
  - mm/huge_memory.c:zap_huge_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff813be0c0-ffffffff813be12d: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814408f0)
Location: mm/huge_memory.c:1973
Inline: False
Direct callers:
  - mm/huge_memory.c:zap_huge_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff814408f0-ffffffff8144095f: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814761a0)
Location: mm/huge_memory.c:1962
Inline: False
Direct callers:
  - mm/huge_memory.c:zap_huge_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff814761a0-ffffffff81476212: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a5a50)
Location: mm/huge_memory.c:2301
Inline: False
Direct callers:
  - mm/huge_memory.c:zap_huge_pud
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff814a5a50-ffffffff814a5ac2: __pud_trans_huge_lock (STB_GLOBAL)
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
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010358378)
Location: mm/huge_memory.c:2030
Inline: False
```
**Symbols:**

```
ffff800010358378-ffff800010358414: __pud_trans_huge_lock (STB_GLOBAL)
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
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c000000000440be0)
Location: mm/huge_memory.c:2030
Inline: False
```
**Symbols:**

```
c000000000440be0-c000000000440c8c: __pud_trans_huge_lock (STB_GLOBAL)
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
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812afe90)
Location: mm/huge_memory.c:2030
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/huge_memory.c:zap_huge_pud
```
**Symbols:**

```
ffffffff812afe90-ffffffff812afef6: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a1370)
Location: mm/huge_memory.c:2030
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/huge_memory.c:zap_huge_pud
```
**Symbols:**

```
ffffffff812a1370-ffffffff812a13c5: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812adca0)
Location: mm/huge_memory.c:2030
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/huge_memory.c:zap_huge_pud
```
**Symbols:**

```
ffffffff812adca0-ffffffff812add06: __pud_trans_huge_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
spinlock_t *__pud_trans_huge_lock(pud_t *pud, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812be000)
Location: mm/huge_memory.c:2030
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/huge_memory.c:zap_huge_pud
```
**Symbols:**

```
ffffffff812be000-ffffffff812be064: __pud_trans_huge_lock (STB_GLOBAL)
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
