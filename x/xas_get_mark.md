# Function: <code>xas_get_mark</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a17da0)
Location: lib/xarray.c:831
Inline: True
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
  - lib/xarray.c:xa_get_mark
```
**Symbols:**

```
ffffffff81a17da0-ffffffff81a17ddc: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a87960)
Location: lib/xarray.c:850
Inline: True
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
  - lib/xarray.c:xa_get_mark
```
**Symbols:**

```
ffffffff81a87960-ffffffff81a8799e: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abec00)
Location: lib/xarray.c:851
Inline: True
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
  - lib/xarray.c:xa_get_mark
```
**Symbols:**

```
ffffffff81abec00-ffffffff81abec3e: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fb1cc)
Location: lib/xarray.c:851
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
Direct callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
```
**Symbols:**

```
ffffffff815f9f50-ffffffff815f9f8e: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161fd2c)
Location: lib/xarray.c:854
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
Direct callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
```
**Symbols:**

```
ffffffff8161e750-ffffffff8161e78e: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816034ac)
Location: lib/xarray.c:854
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
Direct callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
```
**Symbols:**

```
ffffffff81602090-ffffffff816020ce: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (ffffffff81671e43)
Location: lib/xarray.c:854
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
Direct callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
```
**Symbols:**

```
ffffffff81cdfe7d-ffffffff81cdfe9b: xas_get_mark.cold (STB_LOCAL)
ffffffff816709e0-ffffffff81670a35: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (ffffffff8178c5e1)
Location: lib/xarray.c:859
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
Direct callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
```
**Symbols:**

```
ffffffff81ea6784-ffffffff81ea67a2: xas_get_mark.cold (STB_LOCAL)
ffffffff8178bf10-ffffffff8178bf78: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (ffffffff82049c81)
Location: lib/xarray.c:859
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
Direct callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
```
**Symbols:**

```
ffffffff820b800a-ffffffff820b8028: xas_get_mark.cold (STB_LOCAL)
ffffffff820498b0-ffffffff82049918: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (ffffffff820c7da1)
Location: lib/xarray.c:857
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
Direct callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
```
**Symbols:**

```
ffffffff8213941f-ffffffff8213943d: xas_get_mark.cold (STB_LOCAL)
ffffffff820c8310-ffffffff820c838b: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/xarray.c (ffffffff821a2721)
Location: lib/xarray.c:857
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_get_mark
Direct callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:filemap_cachestat
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
```
**Symbols:**

```
ffffffff8221b1c4-ffffffff8221b1e2: xas_get_mark.cold (STB_LOCAL)
ffffffff821a2c90-ffffffff821a2d0b: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d99158)
Location: lib/xarray.c:851
Inline: True
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
  - lib/xarray.c:xa_get_mark
```
**Symbols:**

```
ffff800010d99158-ffff800010d991b0: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e95b8c)
Location: lib/xarray.c:851
Inline: True
Direct callers:
  - lib/xarray.c:xa_get_mark
```
**Symbols:**

```
c0e95b8c-c0e95bf8: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ededf0)
Location: lib/xarray.c:851
Inline: True
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
  - lib/xarray.c:xa_get_mark
```
**Symbols:**

```
c000000000ededf0-c000000000edee64: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c21be)
Location: lib/xarray.c:851
Inline: True
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
  - lib/xarray.c:xa_get_mark
```
**Symbols:**

```
ffffffe0008c21be-ffffffe0008c2214: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5da50)
Location: lib/xarray.c:851
Inline: True
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
  - lib/xarray.c:xa_get_mark
```
**Symbols:**

```
ffffffff81a5da50-ffffffff81a5da8e: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1ab20)
Location: lib/xarray.c:851
Inline: True
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
  - lib/xarray.c:xa_get_mark
```
**Symbols:**

```
ffffffff81a1ab20-ffffffff81a1ab5e: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac9e40)
Location: lib/xarray.c:851
Inline: True
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
  - lib/xarray.c:xa_get_mark
```
**Symbols:**

```
ffffffff81ac9e40-ffffffff81ac9e7e: xas_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool xas_get_mark(const struct xa_state *xas, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad63b0)
Location: lib/xarray.c:851
Inline: True
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_entry
  - fs/dax.c:__dax_invalidate_entry
  - lib/xarray.c:xa_get_mark
```
**Symbols:**

```
ffffffff81ad63b0-ffffffff81ad63ee: xas_get_mark (STB_GLOBAL)
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
