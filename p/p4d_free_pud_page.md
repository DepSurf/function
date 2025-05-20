# Function: <code>p4d_free_pud_page</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int p4d_free_pud_page(p4d_t *p4d, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81083550)
Location: arch/x86/mm/pgtable.c:800
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81083550-ffffffff8108355d: p4d_free_pud_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int p4d_free_pud_page(p4d_t *p4d, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810871c0)
Location: arch/x86/mm/pgtable.c:787
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff810871c0-ffffffff810871cd: p4d_free_pud_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int p4d_free_pud_page(p4d_t *p4d, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81087eb0)
Location: arch/x86/mm/pgtable.c:783
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81087eb0-ffffffff81087ebd: p4d_free_pud_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int p4d_free_pud_page(p4d_t *p4d, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a350)
Location: arch/x86/mm/pgtable.c:786
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8108a350-ffffffff8108a35d: p4d_free_pud_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int p4d_free_pud_page(p4d_t *p4d, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a5c0)
Location: arch/x86/mm/pgtable.c:786
Inline: False
Direct callers:
  - mm/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff8108a5c0-ffffffff8108a5cd: p4d_free_pud_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
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
int p4d_free_pud_page(pgd_t *p4d, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff8000100af598)
Location: arch/arm64/mm/mmu.c:1047
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffff8000100af598-ffff8000100af5b4: p4d_free_pud_page (STB_GLOBAL)
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
In lib/ioremap.c (0)
Location: include/asm-generic/pgtable.h:1087
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int p4d_free_pud_page(pgd_t *p4d, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000095830)
Location: arch/powerpc/mm/book3s64/radix_pgtable.c:1095
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
c000000000095830-c000000000095840: p4d_free_pud_page (STB_GLOBAL)
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
In lib/ioremap.c (0)
Location: include/asm-generic/pgtable.h:1087
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
int p4d_free_pud_page(p4d_t *p4d, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086eb0)
Location: arch/x86/mm/pgtable.c:783
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81086eb0-ffffffff81086ebd: p4d_free_pud_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int p4d_free_pud_page(p4d_t *p4d, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81075af0)
Location: arch/x86/mm/pgtable.c:783
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81075af0-ffffffff81075afd: p4d_free_pud_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int p4d_free_pud_page(p4d_t *p4d, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086e60)
Location: arch/x86/mm/pgtable.c:783
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81086e60-ffffffff81086e6d: p4d_free_pud_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int p4d_free_pud_page(p4d_t *p4d, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81088f90)
Location: arch/x86/mm/pgtable.c:783
Inline: False
Direct callers:
  - lib/ioremap.c:ioremap_page_range
```
**Symbols:**

```
ffffffff81088f90-ffffffff81088f9d: p4d_free_pud_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>p4d_t *p4d</code> ➡️ <code>pgd_t *p4d</code>
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
<code>p4d_t *p4d</code> ➡️ <code>pgd_t *p4d</code>
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
