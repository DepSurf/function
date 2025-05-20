# Function: <code>apply_to_pmd_range</code>

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
In mm/memory.c (ffffffff811c0505)
Location: mm/memory.c:1833
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
In mm/memory.c (ffffffff811dbedb)
Location: mm/memory.c:1896
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
In mm/memory.c (ffffffff811eb9ee)
Location: mm/memory.c:1896
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
In mm/memory.c (ffffffff811f6934)
Location: mm/memory.c:2082
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
Location: mm/memory.c:2199
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
In mm/memory.c (ffffffff81230bad)
Location: mm/memory.c:2241
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
In mm/memory.c (ffffffff81242f3d)
Location: mm/memory.c:1977
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
In mm/memory.c (ffffffff81254dbd)
Location: mm/memory.c:2031
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
In mm/memory.c (ffffffff8126332d)
Location: mm/memory.c:2036
Inline: True
Inline callers:
  - mm/memory.c:apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81293391)
Location: mm/memory.c:2245
Inline: True
Inline callers:
  - mm/memory.c:apply_to_p4d_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129dd06)
Location: mm/memory.c:2424
Inline: True
Inline callers:
  - mm/memory.c:__apply_to_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apply_to_pmd_range(struct mm_struct *mm, pud_t *pud, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a30e0)
Location: mm/memory.c:2453
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pud_range
```
**Symbols:**

```
ffffffff812a30e0-ffffffff812a3368: apply_to_pmd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int apply_to_pmd_range(struct mm_struct *mm, pud_t *pud, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e43c0)
Location: mm/memory.c:2548
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pud_range
```
**Symbols:**

```
ffffffff812e43c0-ffffffff812e463a: apply_to_pmd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int apply_to_pmd_range(struct mm_struct *mm, pud_t *pud, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81345c80)
Location: mm/memory.c:2641
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pud_range
```
**Symbols:**

```
ffffffff81345c80-ffffffff81345f1e: apply_to_pmd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apply_to_pmd_range(struct mm_struct *mm, pud_t *pud, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813be030)
Location: mm/memory.c:2612
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pud_range
```
**Symbols:**

```
ffffffff813be030-ffffffff813be2d2: apply_to_pmd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apply_to_pmd_range(struct mm_struct *mm, pud_t *pud, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f2cc0)
Location: mm/memory.c:2612
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pud_range
```
**Symbols:**

```
ffffffff813f2cc0-ffffffff813f2f3d: apply_to_pmd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apply_to_pmd_range(struct mm_struct *mm, pud_t *pud, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141d9b0)
Location: mm/memory.c:2635
Inline: False
Direct callers:
  - mm/memory.c:apply_to_pud_range
```
**Symbols:**

```
ffffffff8141d9b0-ffffffff8141dc2d: apply_to_pmd_range (STB_LOCAL)
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
In mm/memory.c (ffff8000102fad78)
Location: mm/memory.c:2036
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
Location: mm/memory.c:2036
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
In mm/memory.c (c0000000003c5794)
Location: mm/memory.c:2036
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
Location: mm/memory.c:2036
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
In mm/memory.c (ffffffff8125b97d)
Location: mm/memory.c:2036
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
In mm/memory.c (ffffffff8124df2d)
Location: mm/memory.c:2036
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
In mm/memory.c (ffffffff8125971d)
Location: mm/memory.c:2036
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
In mm/memory.c (ffffffff8126911d)
Location: mm/memory.c:2036
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
