# Function: <code>__xa_clear_mark</code>

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
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a18040)
Location: lib/xarray.c:1680
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
ffffffff81a18040-ffffffff81a180b1: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a87c10)
Location: lib/xarray.c:1707
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
ffffffff81a87c10-ffffffff81a87c89: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abeeb0)
Location: lib/xarray.c:1718
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
ffffffff81abeeb0-ffffffff81abef29: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fb64a)
Location: lib/xarray.c:1720
Inline: True
Inline callers:
  - lib/xarray.c:xa_clear_mark
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
**Symbols:**

```
ffffffff815fb110-ffffffff815fb17d: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816201ba)
Location: lib/xarray.c:1910
Inline: True
Inline callers:
  - lib/xarray.c:xa_clear_mark
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
**Symbols:**

```
ffffffff8161fb10-ffffffff8161fb7d: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81603a2a)
Location: lib/xarray.c:1911
Inline: True
Inline callers:
  - lib/xarray.c:xa_clear_mark
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
**Symbols:**

```
ffffffff81603290-ffffffff816032fd: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816720da)
Location: lib/xarray.c:1911
Inline: True
Inline callers:
  - lib/xarray.c:xa_clear_mark
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
**Symbols:**

```
ffffffff81671820-ffffffff81671897: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178b670)
Location: lib/xarray.c:1918
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_end_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
ffffffff8178b670-ffffffff8178b6f9: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820495b0)
Location: lib/xarray.c:1918
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_end_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
ffffffff820495b0-ffffffff82049639: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c8010)
Location: lib/xarray.c:1916
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_end_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
ffffffff820c8010-ffffffff820c8099: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a2990)
Location: lib/xarray.c:1922
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_end_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
ffffffff821a2990-ffffffff821a2a19: __xa_clear_mark (STB_GLOBAL)
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
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9a0b8)
Location: lib/xarray.c:1718
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
ffff800010d9a0b8-ffff800010d9a124: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e96e38)
Location: lib/xarray.c:1718
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
c0e96e38-c0e96ec0: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee03d0)
Location: lib/xarray.c:1718
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
c000000000ee03d0-c000000000ee046c: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c315c)
Location: lib/xarray.c:1718
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
ffffffe0008c315c-ffffffe0008c31aa: __xa_clear_mark (STB_GLOBAL)
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
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5dd00)
Location: lib/xarray.c:1718
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
ffffffff81a5dd00-ffffffff81a5dd79: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1add0)
Location: lib/xarray.c:1718
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
ffffffff81a1add0-ffffffff81a1ae49: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81aca0f0)
Location: lib/xarray.c:1718
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
ffffffff81aca0f0-ffffffff81aca169: __xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad6680)
Location: lib/xarray.c:1718
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - lib/xarray.c:xa_clear_mark
```
**Symbols:**

```
ffffffff81ad6680-ffffffff81ad66f9: __xa_clear_mark (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
