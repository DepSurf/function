# Function: <code>iter_xarray_populate_pages</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t iter_xarray_populate_pages(struct page **pages, struct xarray *xa, long unsigned int index, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815ab1c0)
Location: lib/iov_iter.c:1450
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff815ab1c0-ffffffff815ab398: iter_xarray_populate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t iter_xarray_populate_pages(struct page **pages, struct xarray *xa, long unsigned int index, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1359
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff81614b40-ffffffff81614d78: iter_xarray_populate_pages (STB_LOCAL)
ffffffff81cda885-ffffffff81cda8ab: iter_xarray_populate_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t iter_xarray_populate_pages(struct page **pages, struct xarray *xa, long unsigned int index, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1411
Inline: False
Direct callers:
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
```
**Symbols:**

```
ffffffff816e17c0-ffffffff816e1a9d: iter_xarray_populate_pages (STB_LOCAL)
ffffffff81e92ee0-ffffffff81e92f06: iter_xarray_populate_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t iter_xarray_populate_pages(struct page **pages, struct xarray *xa, long unsigned int index, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:1342
Inline: False
Direct callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
```
**Symbols:**

```
ffffffff817d2460-ffffffff817d2733: iter_xarray_populate_pages (STB_LOCAL)
ffffffff8207807b-ffffffff820780a1: iter_xarray_populate_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t iter_xarray_populate_pages(struct page **pages, struct xarray *xa, long unsigned int index, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:992
Inline: False
Direct callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
```
**Symbols:**

```
ffffffff81810b60-ffffffff81810dde: iter_xarray_populate_pages (STB_LOCAL)
ffffffff820f844a-ffffffff820f8468: iter_xarray_populate_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t iter_xarray_populate_pages(struct page **pages, struct xarray *xa, long unsigned int index, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/iov_iter.c (0)
Location: lib/iov_iter.c:889
Inline: False
Direct callers:
  - lib/iov_iter.c:__iov_iter_get_pages_alloc
```
**Symbols:**

```
ffffffff81856f90-ffffffff81857208: iter_xarray_populate_pages (STB_LOCAL)
ffffffff821d6232-ffffffff821d6250: iter_xarray_populate_pages.cold (STB_LOCAL)
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
