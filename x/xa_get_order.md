# Function: <code>xa_get_order</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xa_get_order(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161fc10)
Location: lib/xarray.c:1753
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
**Symbols:**

```
ffffffff8161fc10-ffffffff8161fcd3: xa_get_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xa_get_order(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81603390)
Location: lib/xarray.c:1754
Inline: False
Direct callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
**Symbols:**

```
ffffffff81603390-ffffffff81603453: xa_get_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xa_get_order(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1754
Inline: False
Direct callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:__add_to_page_cache_locked
```
**Symbols:**

```
ffffffff81cdffb7-ffffffff81cdffdf: xa_get_order.cold (STB_LOCAL)
ffffffff81671930-ffffffff81671a1e: xa_get_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xa_get_order(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1761
Inline: False
Direct callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
**Symbols:**

```
ffffffff81ea654c-ffffffff81ea656b: xa_get_order.cold (STB_LOCAL)
ffffffff8178afc0-ffffffff8178b0c9: xa_get_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xa_get_order(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1761
Inline: False
Direct callers:
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
**Symbols:**

```
ffffffff820b7dd2-ffffffff820b7df1: xa_get_order.cold (STB_LOCAL)
ffffffff82048860-ffffffff82048969: xa_get_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xa_get_order(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1759
Inline: False
Direct callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
**Symbols:**

```
ffffffff8213923e-ffffffff8213925d: xa_get_order.cold (STB_LOCAL)
ffffffff820c7100-ffffffff820c7209: xa_get_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xa_get_order(struct xarray *xa, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1759
Inline: False
Direct callers:
  - mm/filemap.c:filemap_cachestat
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:__filemap_add_folio
```
**Symbols:**

```
ffffffff8221afe3-ffffffff8221b002: xa_get_order.cold (STB_LOCAL)
ffffffff821a1a80-ffffffff821a1b89: xa_get_order (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
