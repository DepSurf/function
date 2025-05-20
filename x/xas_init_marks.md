# Function: <code>xas_init_marks</code>

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
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a17f30)
Location: lib/xarray.c:913
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81a17f30-ffffffff81a17f79: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a87ae0)
Location: lib/xarray.c:932
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81a87ae0-ffffffff81a87b2b: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abed80)
Location: lib/xarray.c:933
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81abed80-ffffffff81abedcb: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fb70f)
Location: lib/xarray.c:933
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
Direct callers:
  - mm/filemap.c:page_cache_delete
```
**Symbols:**

```
ffffffff815f9ff0-ffffffff815fa039: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8162027f)
Location: lib/xarray.c:936
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
Direct callers:
  - mm/filemap.c:page_cache_delete
```
**Symbols:**

```
ffffffff8161e7f0-ffffffff8161e839: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816038bf)
Location: lib/xarray.c:936
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffffffff81602120-ffffffff81602169: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81671ff4)
Location: lib/xarray.c:936
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffffffff81670990-ffffffff816709db: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178c7ac)
Location: lib/xarray.c:941
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
Direct callers:
  - mm/filemap.c:__filemap_remove_folio
```
**Symbols:**

```
ffffffff8178b610-ffffffff8178b665: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff82049e5c)
Location: lib/xarray.c:941
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
Direct callers:
  - mm/filemap.c:__filemap_remove_folio
```
**Symbols:**

```
ffffffff82049540-ffffffff82049595: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c8704)
Location: lib/xarray.c:939
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
Direct callers:
  - mm/filemap.c:__filemap_remove_folio
```
**Symbols:**

```
ffffffff820c7fb0-ffffffff820c7ffc: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a3084)
Location: lib/xarray.c:939
Inline: True
Inline callers:
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
Direct callers:
  - mm/filemap.c:__filemap_remove_folio
```
**Symbols:**

```
ffffffff821a2930-ffffffff821a297c: xas_init_marks (STB_GLOBAL)
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
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9a048)
Location: lib/xarray.c:933
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffff800010d9a048-ffff800010d9a0b8: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e96d0c)
Location: lib/xarray.c:933
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
```
**Symbols:**

```
c0e96d0c-c0e96d60: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee0210)
Location: lib/xarray.c:933
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
```
**Symbols:**

```
c000000000ee0210-c000000000ee02b8: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c2b74)
Location: lib/xarray.c:933
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffe0008c2b74-ffffffe0008c2bc4: xas_init_marks (STB_GLOBAL)
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
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5dbd0)
Location: lib/xarray.c:933
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81a5dbd0-ffffffff81a5dc1b: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1aca0)
Location: lib/xarray.c:933
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81a1aca0-ffffffff81a1aceb: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac9fc0)
Location: lib/xarray.c:933
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81ac9fc0-ffffffff81aca00b: xas_init_marks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xas_init_marks(const struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad6550)
Location: lib/xarray.c:933
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - lib/xarray.c:xa_destroy
  - lib/xarray.c:xas_store
```
**Symbols:**

```
ffffffff81ad6550-ffffffff81ad659b: xas_init_marks (STB_GLOBAL)
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
