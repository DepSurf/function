# Function: <code>apply_to_pud_range</code>

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
In mm/memory.c (ffffffff811c048e)
Location: mm/memory.c:1855
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
In mm/memory.c (ffffffff811dbe99)
Location: mm/memory.c:1918
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
In mm/memory.c (ffffffff811eb9ac)
Location: mm/memory.c:1918
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
In mm/memory.c (ffffffff811f68ee)
Location: mm/memory.c:2104
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
Location: mm/memory.c:2221
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
In mm/memory.c (ffffffff81230b3b)
Location: mm/memory.c:2263
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
In mm/memory.c (ffffffff81242ecb)
Location: mm/memory.c:1999
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
In mm/memory.c (ffffffff81254d4b)
Location: mm/memory.c:2053
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
In mm/memory.c (ffffffff812632bb)
Location: mm/memory.c:2058
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
In mm/memory.c (ffffffff8129331a)
Location: mm/memory.c:2275
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
In mm/memory.c (ffffffff8129dc96)
Location: mm/memory.c:2454
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
int apply_to_pud_range(struct mm_struct *mm, p4d_t *p4d, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a3370)
Location: mm/memory.c:2491
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
```
**Symbols:**

```
ffffffff812a3370-ffffffff812a3597: apply_to_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int apply_to_pud_range(struct mm_struct *mm, p4d_t *p4d, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e4640)
Location: mm/memory.c:2586
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
```
**Symbols:**

```
ffffffff812e4640-ffffffff812e484c: apply_to_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int apply_to_pud_range(struct mm_struct *mm, p4d_t *p4d, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81345f20)
Location: mm/memory.c:2679
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
```
**Symbols:**

```
ffffffff81345f20-ffffffff81346144: apply_to_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apply_to_pud_range(struct mm_struct *mm, p4d_t *p4d, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813be2f0)
Location: mm/memory.c:2650
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
```
**Symbols:**

```
ffffffff813be2f0-ffffffff813be507: apply_to_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apply_to_pud_range(struct mm_struct *mm, p4d_t *p4d, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f2f50)
Location: mm/memory.c:2650
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
```
**Symbols:**

```
ffffffff813f2f50-ffffffff813f3161: apply_to_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apply_to_pud_range(struct mm_struct *mm, p4d_t *p4d, long unsigned int addr, long unsigned int end, pte_fn_t fn, void *data, bool create, pgtbl_mod_mask *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141dc40)
Location: mm/memory.c:2673
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
```
**Symbols:**

```
ffffffff8141dc40-ffffffff8141de51: apply_to_pud_range (STB_LOCAL)
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
In mm/memory.c (ffff8000102fad20)
Location: mm/memory.c:2058
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
Location: mm/memory.c:2058
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
In mm/memory.c (c0000000003c56f0)
Location: mm/memory.c:2058
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
Location: mm/memory.c:2058
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
In mm/memory.c (ffffffff8125b90b)
Location: mm/memory.c:2058
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
In mm/memory.c (ffffffff8124dec5)
Location: mm/memory.c:2058
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
In mm/memory.c (ffffffff812596ab)
Location: mm/memory.c:2058
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
In mm/memory.c (ffffffff812690ab)
Location: mm/memory.c:2058
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
