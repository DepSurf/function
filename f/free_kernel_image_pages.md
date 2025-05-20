# Function: <code>free_kernel_image_pages</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_kernel_image_pages(void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81073000)
Location: arch/x86/mm/init.c:783
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff81073000-ffffffff81073040: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_kernel_image_pages(void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81079090)
Location: arch/x86/mm/init.c:789
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff81079090-ffffffff810790d0: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_kernel_image_pages(void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8107cc90)
Location: arch/x86/mm/init.c:832
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff8107cc90-ffffffff8107ccd0: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_kernel_image_pages(void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8107dd30)
Location: arch/x86/mm/init.c:832
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff8107dd30-ffffffff8107dd70: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_kernel_image_pages(const char *what, void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81084430)
Location: arch/x86/mm/init.c:888
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff81084430-ffffffff81084463: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_kernel_image_pages(const char *what, void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81085980)
Location: arch/x86/mm/init.c:891
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff81085980-ffffffff810859b3: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_kernel_image_pages(const char *what, void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81086680)
Location: arch/x86/mm/init.c:900
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff81086680-ffffffff810866b3: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_kernel_image_pages(const char *what, void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810958f0)
Location: arch/x86/mm/init.c:907
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff810958f0-ffffffff81095923: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_kernel_image_pages(const char *what, void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810a7ae0)
Location: arch/x86/mm/init.c:921
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff810a7ae0-ffffffff810a7b1f: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_kernel_image_pages(const char *what, void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810c0f40)
Location: arch/x86/mm/init.c:925
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff810c0f40-ffffffff810c0f7f: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_kernel_image_pages(const char *what, void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810c4620)
Location: arch/x86/mm/init.c:950
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff810c4620-ffffffff810c465f: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_kernel_image_pages(const char *what, void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810cca70)
Location: arch/x86/mm/init.c:940
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff810cca70-ffffffff810ccaaf: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
void free_kernel_image_pages(void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8107cd30)
Location: arch/x86/mm/init.c:832
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff8107cd30-ffffffff8107cd70: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_kernel_image_pages(void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8106c4a0)
Location: arch/x86/mm/init.c:832
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff8106c4a0-ffffffff8106c4e0: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_kernel_image_pages(void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8107cce0)
Location: arch/x86/mm/init.c:832
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff8107cce0-ffffffff8107cd20: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_kernel_image_pages(void *begin, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8107ede0)
Location: arch/x86/mm/init.c:832
Inline: False
Direct callers:
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff8107ede0-ffffffff8107ee20: free_kernel_image_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *what</code>
</li>
<li>
<b>Param reordered. </b>
<code>begin, end</code> ➡️ <code>what, begin, end</code>
</li>
</ul>
</details>
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
