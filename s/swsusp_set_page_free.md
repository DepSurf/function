# Function: <code>swsusp_set_page_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d039b)
Location: kernel/power/snapshot.c:889
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810d1040-ffffffff810d1071: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d72a7)
Location: kernel/power/snapshot.c:987
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810d5d80-ffffffff810d5db1: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810dde35)
Location: kernel/power/snapshot.c:987
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810dc900-ffffffff810dc92b: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810dcf36)
Location: kernel/power/snapshot.c:989
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810dba20-ffffffff810dba4f: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810e5161)
Location: kernel/power/snapshot.c:991
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810e3c40-ffffffff810e3c6f: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810ecddc)
Location: kernel/power/snapshot.c:991
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810ebed0-ffffffff810ebefe: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f847c)
Location: kernel/power/snapshot.c:992
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810f7570-ffffffff810f759e: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81100a5b)
Location: kernel/power/snapshot.c:993
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810ffad0-ffffffff810ffafe: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110cebb)
Location: kernel/power/snapshot.c:1000
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff8110bf30-ffffffff8110bf5e: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811165c6)
Location: kernel/power/snapshot.c:999
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - kernel/power/snapshot.c:alloc_image_page
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff81116e70-ffffffff81116e9e: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81112a46)
Location: kernel/power/snapshot.c:1033
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - kernel/power/snapshot.c:alloc_image_page
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff811132f0-ffffffff8111331e: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81113496)
Location: kernel/power/snapshot.c:1033
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - kernel/power/snapshot.c:alloc_image_page
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff81113bf0-ffffffff81113c1e: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81133636)
Location: kernel/power/snapshot.c:1026
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - kernel/power/snapshot.c:alloc_image_page
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff81133db0-ffffffff81133dde: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811554c2)
Location: kernel/power/snapshot.c:1030
Inline: True
Inline callers:
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - kernel/power/snapshot.c:alloc_image_page
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff81155c40-ffffffff81155c82: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81187529)
Location: kernel/power/snapshot.c:1030
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:preallocate_image_memory
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff81186180-ffffffff811861c2: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811986b9)
Location: kernel/power/snapshot.c:1030
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:preallocate_image_memory
  - kernel/power/snapshot.c:get_image_page
```
**Symbols:**

```
ffffffff81197300-ffffffff81197342: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811a753a)
Location: kernel/power/snapshot.c:1040
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:preallocate_image_memory
  - kernel/power/snapshot.c:get_image_page
```
**Symbols:**

```
ffffffff811a5e50-ffffffff811a5e92: swsusp_set_page_free (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03bdd8c)
Location: kernel/power/snapshot.c:1000
Inline: False
Direct callers:
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
c03bdd8c-c03bddec: swsusp_set_page_free (STB_GLOBAL)
```
</details>
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
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811050db)
Location: kernel/power/snapshot.c:999
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff81104150-ffffffff8110417e: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f637b)
Location: kernel/power/snapshot.c:1000
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff810f53f0-ffffffff810f541e: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110338b)
Location: kernel/power/snapshot.c:1000
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff81102400-ffffffff8110242e: swsusp_set_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void swsusp_set_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110e77b)
Location: kernel/power/snapshot.c:1000
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/power/snapshot.c:get_image_page
Direct callers:
  - mm/page_alloc.c:mark_free_pages
```
**Symbols:**

```
ffffffff8110d7d0-ffffffff8110d7fe: swsusp_set_page_free (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
