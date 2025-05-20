# Function: <code>gup_pud_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gup_pud_range(pgd_t pgd, long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81071860)
Location: arch/x86/mm/gup.c:226
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:__get_user_pages_fast
  - arch/x86/mm/gup.c:get_user_pages_fast
```
**Symbols:**

```
ffffffff81071860-ffffffff81071a7f: gup_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gup_pud_range(pgd_t pgd, long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81071b70)
Location: arch/x86/mm/gup.c:273
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:get_user_pages_fast
  - arch/x86/mm/gup.c:__get_user_pages_fast
```
**Symbols:**

```
ffffffff81071b70-ffffffff81071d48: gup_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gup_pud_range(pgd_t pgd, long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff810756e0)
Location: arch/x86/mm/gup.c:277
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:get_user_pages_fast
  - arch/x86/mm/gup.c:__get_user_pages_fast
```
**Symbols:**

```
ffffffff810756e0-ffffffff810758b8: gup_pud_range (STB_LOCAL)
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
In mm/gup.c (ffffffff811f0891)
Location: mm/gup.c:1568
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
In mm/gup.c (ffffffff812053c0)
Location: mm/gup.c:1657
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
In mm/gup.c (ffffffff812268ff)
Location: mm/gup.c:1680
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812399b0)
Location: mm/gup.c:1706
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff812399b0-ffffffff8123a4c7: gup_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124abe0)
Location: mm/gup.c:2220
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff8124abe0-ffffffff8124b724: gup_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812590d0)
Location: mm/gup.c:2236
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff812590d0-ffffffff81259c14: gup_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (ffffffff8128b0a0)
Location: mm/gup.c:2620
Inline: True
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff8128b0a0-ffffffff8128b1c9: gup_pud_range.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/gup.c (ffffffff81294d60)
Location: mm/gup.c:2398
Inline: True
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff81294d60-ffffffff81294e89: gup_pud_range.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129a701)
Location: mm/gup.c:2464
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812db0c2)
Location: mm/gup.c:2559
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133ac70)
Location: mm/gup.c:2707
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b2a0a)
Location: mm/gup.c:2755
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e74f1)
Location: mm/gup.c:3014
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81412176)
Location: mm/gup.c:3032
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
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
int gup_pud_range(pgd_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f0fe0)
Location: mm/gup.c:2236
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffff8000102f0fe0-ffff8000102f1700: gup_pud_range (STB_LOCAL)
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
int gup_pud_range(pgd_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b6700)
Location: mm/gup.c:2236
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
c0000000003b6700-c0000000003b74c4: gup_pud_range (STB_LOCAL)
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
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81251720)
Location: mm/gup.c:2236
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff81251720-ffffffff81252264: gup_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81244610)
Location: mm/gup.c:2236
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff81244610-ffffffff81245036: gup_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124f4c0)
Location: mm/gup.c:2236
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff8124f4c0-ffffffff81250004: gup_pud_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gup_pud_range(p4d_t p4d, long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125ee30)
Location: mm/gup.c:2236
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
```
**Symbols:**

```
ffffffff8125ee30-ffffffff8125f996: gup_pud_range (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t p4d</code> ➡️ <code>pgd_t p4d</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t p4d</code> ➡️ <code>pgd_t p4d</code>
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
