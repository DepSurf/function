# Function: <code>p4d_clear_huge</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:900
Inline: True
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
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:969
Inline: True
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
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:1012
Inline: True
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
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:1050
Inline: True
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
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:1050
Inline: True
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
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:1049
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int p4d_clear_huge(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a030)
Location: arch/x86/mm/pgtable.c:679
Inline: False
Direct callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
**Symbols:**

```
ffffffff8108a030-ffffffff8108a03d: p4d_clear_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int p4d_clear_huge(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a2b0)
Location: arch/x86/mm/pgtable.c:679
Inline: False
Direct callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
**Symbols:**

```
ffffffff8108a2b0-ffffffff8108a2bd: p4d_clear_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int p4d_clear_huge(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108af10)
Location: arch/x86/mm/pgtable.c:679
Inline: False
Direct callers:
  - mm/vmalloc.c:vunmap_range_noflush
```
**Symbols:**

```
ffffffff8108af10-ffffffff8108af1d: p4d_clear_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int p4d_clear_huge(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8109a4b0)
Location: arch/x86/mm/pgtable.c:679
Inline: False
Direct callers:
  - mm/vmalloc.c:vunmap_range_noflush
```
**Symbols:**

```
ffffffff8109a4b0-ffffffff8109a4bd: p4d_clear_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void p4d_clear_huge(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ad710)
Location: arch/x86/mm/pgtable.c:689
Inline: False
Direct callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
**Symbols:**

```
ffffffff810ad710-ffffffff810ad71f: p4d_clear_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void p4d_clear_huge(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c78a0)
Location: arch/x86/mm/pgtable.c:696
Inline: False
Direct callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
**Symbols:**

```
ffffffff810c78a0-ffffffff810c78af: p4d_clear_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void p4d_clear_huge(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810caff0)
Location: arch/x86/mm/pgtable.c:696
Inline: False
Direct callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
**Symbols:**

```
ffffffff810caff0-ffffffff810cafff: p4d_clear_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void p4d_clear_huge(p4d_t *p4d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d3540)
Location: arch/x86/mm/pgtable.c:708
Inline: False
Direct callers:
  - mm/vmalloc.c:vunmap_p4d_range
```
**Symbols:**

```
ffffffff810d3540-ffffffff810d354f: p4d_clear_huge (STB_GLOBAL)
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
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:1049
Inline: True
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
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:1075
Inline: True
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
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:1049
Inline: True
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
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:1075
Inline: True
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
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:1049
Inline: True
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
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:1049
Inline: True
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
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:1049
Inline: True
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
In mm/vmalloc.c (0)
Location: include/asm-generic/pgtable.h:1049
Inline: True
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
