# Function: <code>__xa_set_mark</code>

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
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a17390)
Location: lib/xarray.c:1662
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
ffffffff81a17390-ffffffff81a17401: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a87020)
Location: lib/xarray.c:1689
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
ffffffff81a87020-ffffffff81a87099: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abe2b0)
Location: lib/xarray.c:1700
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
ffffffff81abe2b0-ffffffff81abe329: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fb5ba)
Location: lib/xarray.c:1702
Inline: True
Inline callers:
  - lib/xarray.c:xa_set_mark
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff815faaf0-ffffffff815fab5d: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8162012a)
Location: lib/xarray.c:1892
Inline: True
Inline callers:
  - lib/xarray.c:xa_set_mark
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff8161f2f0-ffffffff8161f35d: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8160399a)
Location: lib/xarray.c:1893
Inline: True
Inline callers:
  - lib/xarray.c:xa_set_mark
Direct callers:
  - fs/buffer.c:__set_page_dirty
```
**Symbols:**

```
ffffffff81602940-ffffffff816029ad: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8167217a)
Location: lib/xarray.c:1893
Inline: True
Inline callers:
  - lib/xarray.c:xa_set_mark
Direct callers:
  - mm/page-writeback.c:__set_page_dirty
```
**Symbols:**

```
ffffffff81670db0-ffffffff81670e27: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178b490)
Location: lib/xarray.c:1900
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_mark_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
ffffffff8178b490-ffffffff8178b519: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff82048d70)
Location: lib/xarray.c:1900
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_mark_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
ffffffff82048d70-ffffffff82048df9: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c7620)
Location: lib/xarray.c:1898
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_mark_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
ffffffff820c7620-ffffffff820c76a9: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a1fa0)
Location: lib/xarray.c:1904
Inline: False
Direct callers:
  - mm/page-writeback.c:__folio_mark_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
ffffffff821a1fa0-ffffffff821a2029: __xa_set_mark (STB_GLOBAL)
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
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d99560)
Location: lib/xarray.c:1700
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
ffff800010d99560-ffff800010d995cc: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e95ffc)
Location: lib/xarray.c:1700
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
c0e95ffc-c0e96084: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000edf2e0)
Location: lib/xarray.c:1700
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
c000000000edf2e0-c000000000edf37c: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c2508)
Location: lib/xarray.c:1700
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
ffffffe0008c2508-ffffffe0008c2556: __xa_set_mark (STB_GLOBAL)
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
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5d100)
Location: lib/xarray.c:1700
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
ffffffff81a5d100-ffffffff81a5d179: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1a1d0)
Location: lib/xarray.c:1700
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
ffffffff81a1a1d0-ffffffff81a1a249: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac94f0)
Location: lib/xarray.c:1700
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
ffffffff81ac94f0-ffffffff81ac9569: __xa_set_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __xa_set_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad59c0)
Location: lib/xarray.c:1700
Inline: False
Direct callers:
  - fs/buffer.c:__set_page_dirty
  - lib/xarray.c:xa_set_mark
```
**Symbols:**

```
ffffffff81ad59c0-ffffffff81ad5a39: __xa_set_mark (STB_GLOBAL)
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
