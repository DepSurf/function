# Function: <code>__kernel_unpoison_pages</code>

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
void __kernel_unpoison_pages(struct page *page, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff812e2d50)
Location: mm/page_poison.c:89
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff812e2d50-ffffffff812e2db9: __kernel_unpoison_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __kernel_unpoison_pages(struct page *page, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_poison.c (0)
Location: mm/page_poison.c:93
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81bdade2-ffffffff81bdae67: __kernel_unpoison_pages.cold (STB_LOCAL)
ffffffff812ea470-ffffffff812ea539: __kernel_unpoison_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __kernel_unpoison_pages(struct page *page, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_poison.c (0)
Location: mm/page_poison.c:93
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81cc093b-ffffffff81cc09c0: __kernel_unpoison_pages.cold (STB_LOCAL)
ffffffff81332390-ffffffff81332459: __kernel_unpoison_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __kernel_unpoison_pages(struct page *page, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_poison.c (0)
Location: mm/page_poison.c:93
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_bulk
```
**Symbols:**

```
ffffffff81e72dde-ffffffff81e72e63: __kernel_unpoison_pages.cold (STB_LOCAL)
ffffffff813a37b0-ffffffff813a38b7: __kernel_unpoison_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __kernel_unpoison_pages(struct page *page, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff81423540)
Location: mm/page_poison.c:93
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_bulk
```
**Symbols:**

```
ffffffff81423540-ffffffff814236d0: __kernel_unpoison_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __kernel_unpoison_pages(struct page *page, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff814587e0)
Location: mm/page_poison.c:93
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_bulk
```
**Symbols:**

```
ffffffff814587e0-ffffffff8145896f: __kernel_unpoison_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __kernel_unpoison_pages(struct page *page, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff81492f00)
Location: mm/page_poison.c:92
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_bulk
```
**Symbols:**

```
ffffffff81492f00-ffffffff8149305c: __kernel_unpoison_pages (STB_GLOBAL)
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
