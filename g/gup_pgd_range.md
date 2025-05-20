# Function: <code>gup_pgd_range</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812053a0)
Location: mm/gup.c:1710
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
**Symbols:**

```
ffffffff812053a0-ffffffff81205f2c: gup_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81226850)
Location: mm/gup.c:1733
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
**Symbols:**

```
ffffffff81226850-ffffffff812273c6: gup_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, int write, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123a4d0)
Location: mm/gup.c:1759
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
**Symbols:**

```
ffffffff8123a4d0-ffffffff8123a592: gup_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124b730)
Location: mm/gup.c:2273
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
**Symbols:**

```
ffffffff8124b730-ffffffff8124b801: gup_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81259c20)
Location: mm/gup.c:2289
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
**Symbols:**

```
ffffffff81259c20-ffffffff81259cf1: gup_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128b1d0)
Location: mm/gup.c:2673
Inline: False
Direct callers:
  - mm/gup.c:internal_get_user_pages_fast
```
**Symbols:**

```
ffffffff8128b1d0-ffffffff8128b368: gup_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81294e90)
Location: mm/gup.c:2451
Inline: False
Direct callers:
  - mm/gup.c:lockless_pages_from_mm
```
**Symbols:**

```
ffffffff81294e90-ffffffff81295028: gup_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129a5c0)
Location: mm/gup.c:2517
Inline: False
Direct callers:
  - mm/gup.c:lockless_pages_from_mm
```
**Symbols:**

```
ffffffff8129a5c0-ffffffff8129a9e4: gup_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:2612
Inline: False
Direct callers:
  - mm/gup.c:lockless_pages_from_mm
```
**Symbols:**

```
ffffffff812daf50-ffffffff812db395: gup_pgd_range (STB_LOCAL)
ffffffff81cbc141-ffffffff81cbc1a4: gup_pgd_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:2760
Inline: False
Direct callers:
  - mm/gup.c:lockless_pages_from_mm
```
**Symbols:**

```
ffffffff8133ab30-ffffffff8133af7d: gup_pgd_range (STB_LOCAL)
ffffffff81e6dcb9-ffffffff81e6dd14: gup_pgd_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:2808
Inline: False
Direct callers:
  - mm/gup.c:lockless_pages_from_mm
```
**Symbols:**

```
ffffffff813b28b0-ffffffff813b2ba5: gup_pgd_range (STB_LOCAL)
ffffffff82063d6a-ffffffff82063de0: gup_pgd_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:3067
Inline: False
Direct callers:
  - mm/gup.c:lockless_pages_from_mm
```
**Symbols:**

```
ffffffff813e7380-ffffffff813e781f: gup_pgd_range (STB_LOCAL)
ffffffff820e346e-ffffffff820e34c9: gup_pgd_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/gup.c (0)
Location: mm/gup.c:3085
Inline: False
Direct callers:
  - mm/gup.c:lockless_pages_from_mm
```
**Symbols:**

```
ffffffff81412020-ffffffff8141248a: gup_pgd_range (STB_LOCAL)
ffffffff821bfec2-ffffffff821bff1e: gup_pgd_range.cold (STB_LOCAL)
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
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f1700)
Location: mm/gup.c:2289
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
**Symbols:**

```
ffff8000102f1700-ffff8000102f17b8: gup_pgd_range (STB_LOCAL)
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
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b74d0)
Location: mm/gup.c:2289
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
**Symbols:**

```
c0000000003b74d0-c0000000003b790c: gup_pgd_range (STB_LOCAL)
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
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81252270)
Location: mm/gup.c:2289
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
**Symbols:**

```
ffffffff81252270-ffffffff81252341: gup_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81245040)
Location: mm/gup.c:2289
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
**Symbols:**

```
ffffffff81245040-ffffffff81245111: gup_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81250010)
Location: mm/gup.c:2289
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
**Symbols:**

```
ffffffff81250010-ffffffff812500e1: gup_pgd_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gup_pgd_range(long unsigned int addr, long unsigned int end, unsigned int flags, struct page **pages, int *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125f9a0)
Location: mm/gup.c:2289
Inline: False
Direct callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
```
**Symbols:**

```
ffffffff8125f9a0-ffffffff8125fa71: gup_pgd_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
