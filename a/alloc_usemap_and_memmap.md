# Function: <code>alloc_usemap_and_memmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void alloc_usemap_and_memmap(void (*alloc_func)(void *, long unsigned int, long unsigned int, long unsigned int, int), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81f8c53d)
Location: mm/sparse.c:474
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
**Symbols:**

```
ffffffff81f8c53d-ffffffff81f8c607: alloc_usemap_and_memmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void alloc_usemap_and_memmap(void (*alloc_func)(void *, long unsigned int, long unsigned int, long unsigned int, int), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81fb6245)
Location: mm/sparse.c:473
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
**Symbols:**

```
ffffffff81fb6245-ffffffff81fb631f: alloc_usemap_and_memmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void alloc_usemap_and_memmap(void (*alloc_func)(void *, long unsigned int, long unsigned int, long unsigned int, int), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81ff2c0e)
Location: mm/sparse.c:473
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
**Symbols:**

```
ffffffff81ff2c0e-ffffffff81ff2ce8: alloc_usemap_and_memmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void alloc_usemap_and_memmap(void (*alloc_func)(void *, long unsigned int, long unsigned int, long unsigned int, int), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff820d52da)
Location: mm/sparse.c:510
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
**Symbols:**

```
ffffffff820d52da-ffffffff820d53e4: alloc_usemap_and_memmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void alloc_usemap_and_memmap(void (*alloc_func)(void *, long unsigned int, long unsigned int, long unsigned int, int), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff826ddea0)
Location: mm/sparse.c:522
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
**Symbols:**

```
ffffffff826ddea0-ffffffff826ddfbe: alloc_usemap_and_memmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void alloc_usemap_and_memmap(void (*alloc_func)(void *, long unsigned int, long unsigned int, long unsigned int, int), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff827083fa)
Location: mm/sparse.c:488
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
```
**Symbols:**

```
ffffffff827083fa-ffffffff82708554: alloc_usemap_and_memmap (STB_LOCAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
