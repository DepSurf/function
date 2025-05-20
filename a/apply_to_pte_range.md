# Function: <code>apply_to_pte_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c059b)
Location: mm/memory.c:1799
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dbfa5)
Location: mm/memory.c:1862
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ebab8)
Location: mm/memory.c:1862
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f6a0a)
Location: mm/memory.c:2048
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120ed0d)
Location: mm/memory.c:2165
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81230c45)
Location: mm/memory.c:2207
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81242fd5)
Location: mm/memory.c:1943
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81254e54)
Location: mm/memory.c:2000
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812633c4)
Location: mm/memory.c:2005
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apply_to_pte_range(struct mm_struct *mm, pmd_t *pmd, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128e840)
Location: mm/memory.c:2204
Inline: False
Direct callers:
  - mm/memory.c:apply_to_p4d_range
```
**Symbols:**

```
ffffffff8128e840-ffffffff8128eb05: apply_to_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apply_to_pte_range(struct mm_struct *mm, pmd_t *pmd, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81299460)
Location: mm/memory.c:2381
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
```
**Symbols:**

```
ffffffff81299460-ffffffff812996bb: apply_to_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apply_to_pte_range(struct mm_struct *mm, pmd_t *pmd, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129e6f0)
Location: mm/memory.c:2410
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pmd_range
```
**Symbols:**

```
ffffffff8129e6f0-ffffffff8129e8e0: apply_to_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int apply_to_pte_range(struct mm_struct *mm, pmd_t *pmd, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812df930)
Location: mm/memory.c:2505
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pmd_range
```
**Symbols:**

```
ffffffff812df930-ffffffff812dfb20: apply_to_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int apply_to_pte_range(struct mm_struct *mm, pmd_t *pmd, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8133fe90)
Location: mm/memory.c:2598
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pmd_range
```
**Symbols:**

```
ffffffff8133fe90-ffffffff8134009c: apply_to_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apply_to_pte_range(struct mm_struct *mm, pmd_t *pmd, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b7df0)
Location: mm/memory.c:2569
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pmd_range
```
**Symbols:**

```
ffffffff813b7df0-ffffffff813b7ffc: apply_to_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apply_to_pte_range(struct mm_struct *mm, pmd_t *pmd, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ecb60)
Location: mm/memory.c:2569
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pmd_range
```
**Symbols:**

```
ffffffff813ecb60-ffffffff813ecdcc: apply_to_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apply_to_pte_range(struct mm_struct *mm, pmd_t *pmd, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff814180b0)
Location: mm/memory.c:2592
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pmd_range
```
**Symbols:**

```
ffffffff814180b0-ffffffff81418321: apply_to_pte_range (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fadcc)
Location: mm/memory.c:2005
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0518250)
Location: mm/memory.c:2005
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
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
In mm/memory.c (c0000000003c5848)
Location: mm/memory.c:2005
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
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
In mm/memory.c (ffffffe00020a65a)
Location: mm/memory.c:2005
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125ba14)
Location: mm/memory.c:2005
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124dfc9)
Location: mm/memory.c:2005
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812597b4)
Location: mm/memory.c:2005
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812691b7)
Location: mm/memory.c:2005
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
