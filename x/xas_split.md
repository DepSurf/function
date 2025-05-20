# Function: <code>xas_split</code>

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
void xas_split(struct xa_state *xas, void *entry, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161f8c0)
Location: lib/xarray.c:1050
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
**Symbols:**

```
ffffffff8161f8c0-ffffffff8161fb07: xas_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xas_split(struct xa_state *xas, void *entry, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81603040)
Location: lib/xarray.c:1051
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
**Symbols:**

```
ffffffff81603040-ffffffff81603287: xas_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xas_split(struct xa_state *xas, void *entry, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81671530)
Location: lib/xarray.c:1051
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
```
**Symbols:**

```
ffffffff81671530-ffffffff8167181e: xas_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xas_split(struct xa_state *xas, void *entry, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178bf80)
Location: lib/xarray.c:1056
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff8178bf80-ffffffff8178c2ab: xas_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xas_split(struct xa_state *xas, void *entry, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff82048540)
Location: lib/xarray.c:1056
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff82048540-ffffffff82048844: xas_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xas_split(struct xa_state *xas, void *entry, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c6d40)
Location: lib/xarray.c:1054
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff820c6d40-ffffffff820c70ef: xas_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xas_split(struct xa_state *xas, void *entry, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a16c0)
Location: lib/xarray.c:1054
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff821a16c0-ffffffff821a1a6f: xas_split (STB_GLOBAL)
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
