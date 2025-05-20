# Function: <code>gup_huge_pud</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gup_huge_pud(pud_t pud, long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff810715e0)
Location: arch/x86/mm/gup.c:193
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff810715e0-ffffffff81071711: gup_huge_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gup_huge_pud(pud_t pud, long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81071a60)
Location: arch/x86/mm/gup.c:246
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff81071a60-ffffffff81071b63: gup_huge_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gup_huge_pud(pud_t pud, long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff810755e0)
Location: arch/x86/mm/gup.c:250
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffffffff810755e0-ffffffff810756dd: gup_huge_pud (STB_LOCAL)
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
In mm/gup.c (ffffffff811f0fdd)
Location: mm/gup.c:1451
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
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
In mm/gup.c (ffffffff81205c32)
Location: mm/gup.c:1540
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
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
In mm/gup.c (ffffffff812270cb)
Location: mm/gup.c:1563
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
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
In mm/gup.c (ffffffff8123a1c1)
Location: mm/gup.c:1588
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
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
In mm/gup.c (ffffffff8124b390)
Location: mm/gup.c:2099
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
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
In mm/gup.c (ffffffff81259880)
Location: mm/gup.c:2115
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gup_huge_pud(pud_t orig, pud_t *pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128a950)
Location: mm/gup.c:2514
Inline: False
```
**Symbols:**

```
ffffffff8128a950-ffffffff8128ac06: gup_huge_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gup_huge_pud(pud_t orig, pud_t *pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81294610)
Location: mm/gup.c:2292
Inline: False
```
**Symbols:**

```
ffffffff81294610-ffffffff812948c6: gup_huge_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gup_huge_pud(pud_t orig, pud_t *pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129a060)
Location: mm/gup.c:2358
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff8129a060-ffffffff8129a310: gup_huge_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gup_huge_pud(pud_t orig, pud_t *pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812da9f0)
Location: mm/gup.c:2453
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff812da9f0-ffffffff812dac92: gup_huge_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gup_huge_pud(pud_t orig, pud_t *pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133a570)
Location: mm/gup.c:2594
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff8133a570-ffffffff8133a849: gup_huge_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gup_huge_pud(pud_t orig, pud_t *pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b2040)
Location: mm/gup.c:2646
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff813b2040-ffffffff813b2343: gup_huge_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gup_huge_pud(pud_t orig, pud_t *pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e6de0)
Location: mm/gup.c:2890
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff813e6de0-ffffffff813e7099: gup_huge_pud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gup_huge_pud(pud_t orig, pud_t *pudp, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81411a60)
Location: mm/gup.c:2908
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff81411a60-ffffffff81411d19: gup_huge_pud (STB_LOCAL)
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
In mm/gup.c (ffff8000102f1490)
Location: mm/gup.c:2115
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b6c40)
Location: mm/gup.c:2115
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81251ed0)
Location: mm/gup.c:2115
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
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
In mm/gup.c (ffffffff81244cd4)
Location: mm/gup.c:2115
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
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
In mm/gup.c (ffffffff8124fc70)
Location: mm/gup.c:2115
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
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
In mm/gup.c (ffffffff8125f60a)
Location: mm/gup.c:2115
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
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
