# Function: <code>free_page_is_bad_report</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_page_is_bad_report(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e4ea0)
Location: mm/page_alloc.c:1276
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:free_pcp_prepare
```
**Symbols:**

```
ffffffff813e4ea0-ffffffff813e4f12: free_page_is_bad_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_page_is_bad_report(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81419a30)
Location: mm/page_alloc.c:972
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff81419a30-ffffffff81419aa2: free_page_is_bad_report (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_page_is_bad_report(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81446770)
Location: mm/page_alloc.c:955
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
```
**Symbols:**

```
ffffffff81446770-ffffffff81446804: free_page_is_bad_report (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
