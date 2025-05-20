# Function: <code>gnttab_alloc_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff814c5530)
Location: drivers/xen/grant-table.c:685
Inline: False
```
**Symbols:**

```
ffffffff814c5530-ffffffff814c5575: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81515ba0)
Location: drivers/xen/grant-table.c:684
Inline: False
```
**Symbols:**

```
ffffffff81515ba0-ffffffff81515be5: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81542020)
Location: drivers/xen/grant-table.c:684
Inline: False
```
**Symbols:**

```
ffffffff81542020-ffffffff81542065: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81556490)
Location: drivers/xen/grant-table.c:685
Inline: True
```
**Symbols:**

```
ffffffff81556490-ffffffff815564d5: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815b9f90)
Location: drivers/xen/grant-table.c:777
Inline: True
```
**Symbols:**

```
ffffffff815b9f90-ffffffff815b9fd5: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815f1e00)
Location: drivers/xen/grant-table.c:777
Inline: True
```
**Symbols:**

```
ffffffff815f1e00-ffffffff815f1e45: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160cba0)
Location: drivers/xen/grant-table.c:802
Inline: True
```
**Symbols:**

```
ffffffff8160cba0-ffffffff8160cbe5: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81640740)
Location: drivers/xen/grant-table.c:802
Inline: True
```
**Symbols:**

```
ffffffff81640740-ffffffff81640785: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81662e50)
Location: drivers/xen/grant-table.c:802
Inline: True
```
**Symbols:**

```
ffffffff81662e50-ffffffff81662e95: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81712a70)
Location: drivers/xen/grant-table.c:800
Inline: True
```
**Symbols:**

```
ffffffff81712a70-ffffffff81712ab5: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8172f800)
Location: drivers/xen/grant-table.c:800
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_get
```
**Symbols:**

```
ffffffff8172f800-ffffffff8172f845: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81713190)
Location: drivers/xen/grant-table.c:800
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_get
```
**Symbols:**

```
ffffffff81713190-ffffffff817131d8: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8178fde0)
Location: drivers/xen/grant-table.c:807
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_get
```
**Symbols:**

```
ffffffff8178fde0-ffffffff8178fe28: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c9a34)
Location: drivers/xen/grant-table.c:873
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_get
  - drivers/xen/grant-table.c:gnttab_page_cache_get
```
**Symbols:**

```
ffffffff818c8bf0-ffffffff818c8c3f: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a1a934)
Location: drivers/xen/grant-table.c:873
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_get
  - drivers/xen/grant-table.c:gnttab_page_cache_get
```
**Symbols:**

```
ffffffff81a199e0-ffffffff81a19a2f: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a63ae4)
Location: drivers/xen/grant-table.c:891
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_get
  - drivers/xen/grant-table.c:gnttab_page_cache_get
```
**Symbols:**

```
ffffffff81a62a60-ffffffff81a62aaf: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab6324)
Location: drivers/xen/grant-table.c:889
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_get
  - drivers/xen/grant-table.c:gnttab_page_cache_get
```
**Symbols:**

```
ffffffff81ab5090-ffffffff81ab50df: gnttab_alloc_pages (STB_GLOBAL)
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
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082c3d0)
Location: drivers/xen/grant-table.c:802
Inline: True
```
**Symbols:**

```
ffff80001082c3d0-ffff80001082c448: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81628cc0)
Location: drivers/xen/grant-table.c:802
Inline: True
```
**Symbols:**

```
ffffffff81628cc0-ffffffff81628d05: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81656c90)
Location: drivers/xen/grant-table.c:802
Inline: True
```
**Symbols:**

```
ffffffff81656c90-ffffffff81656cd5: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int gnttab_alloc_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81671270)
Location: drivers/xen/grant-table.c:802
Inline: True
```
**Symbols:**

```
ffffffff81671270-ffffffff816712b5: gnttab_alloc_pages (STB_GLOBAL)
```
</details>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
