# Function: <code>__kernel_poison_pages</code>

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
void __kernel_poison_pages(struct page *page, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff812e2cc0)
Location: mm/page_poison.c:33
Inline: False
Direct callers:
  - kernel/power/snapshot.c:clear_or_poison_free_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
**Symbols:**

```
ffffffff812e2cc0-ffffffff812e2d42: __kernel_poison_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __kernel_poison_pages(struct page *page, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff812ea3e0)
Location: mm/page_poison.c:34
Inline: False
Direct callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
**Symbols:**

```
ffffffff812ea3e0-ffffffff812ea462: __kernel_poison_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __kernel_poison_pages(struct page *page, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff81332300)
Location: mm/page_poison.c:34
Inline: False
Direct callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
**Symbols:**

```
ffffffff81332300-ffffffff81332382: __kernel_poison_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __kernel_poison_pages(struct page *page, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff813a36f0)
Location: mm/page_poison.c:34
Inline: False
Direct callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
**Symbols:**

```
ffffffff813a36f0-ffffffff813a37af: __kernel_poison_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __kernel_poison_pages(struct page *page, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff81423470)
Location: mm/page_poison.c:34
Inline: False
Direct callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
**Symbols:**

```
ffffffff81423470-ffffffff8142352f: __kernel_poison_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __kernel_poison_pages(struct page *page, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff81458710)
Location: mm/page_poison.c:34
Inline: False
Direct callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff81458710-ffffffff814587cf: __kernel_poison_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __kernel_poison_pages(struct page *page, int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_poison.c (ffffffff81492e70)
Location: mm/page_poison.c:33
Inline: False
Direct callers:
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff81492e70-ffffffff81492ee7: __kernel_poison_pages (STB_GLOBAL)
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
