# Function: <code>xas_split_alloc</code>

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
void xas_split_alloc(struct xa_state *xas, void *entry, unsigned int order, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161e530)
Location: lib/xarray.c:1000
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
**Symbols:**

```
ffffffff8161e530-ffffffff8161e624: xas_split_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xas_split_alloc(struct xa_state *xas, void *entry, unsigned int order, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81601e70)
Location: lib/xarray.c:1000
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
**Symbols:**

```
ffffffff81601e70-ffffffff81601f6b: xas_split_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xas_split_alloc(struct xa_state *xas, void *entry, unsigned int order, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8166fd30)
Location: lib/xarray.c:1000
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
**Symbols:**

```
ffffffff8166fd30-ffffffff8166fe87: xas_split_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xas_split_alloc(struct xa_state *xas, void *entry, unsigned int order, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178c400)
Location: lib/xarray.c:1005
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8178c400-ffffffff8178c577: xas_split_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xas_split_alloc(struct xa_state *xas, void *entry, unsigned int order, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff82049a90)
Location: lib/xarray.c:1005
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff82049a90-ffffffff82049c07: xas_split_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xas_split_alloc(struct xa_state *xas, void *entry, unsigned int order, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c8500)
Location: lib/xarray.c:1003
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff820c8500-ffffffff820c8677: xas_split_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xas_split_alloc(struct xa_state *xas, void *entry, unsigned int order, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a2e80)
Location: lib/xarray.c:1003
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff821a2e80-ffffffff821a2ff7: xas_split_alloc (STB_GLOBAL)
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
