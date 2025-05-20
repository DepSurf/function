# Function: <code>is_refcount_suitable</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool is_refcount_suitable(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812efd40)
Location: mm/khugepaged.c:573
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812efd40-ffffffff812efdc1: is_refcount_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool is_refcount_suitable(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fb520)
Location: mm/khugepaged.c:588
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff812fb520-ffffffff812fb598: is_refcount_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool is_refcount_suitable(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813022f0)
Location: mm/khugepaged.c:586
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff813022f0-ffffffff81302368: is_refcount_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool is_refcount_suitable(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134c060)
Location: mm/khugepaged.c:590
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff8134c060-ffffffff8134c0d8: is_refcount_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool is_refcount_suitable(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c4120)
Location: mm/khugepaged.c:581
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff813c4120-ffffffff813c4290: is_refcount_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool is_refcount_suitable(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81448040)
Location: mm/khugepaged.c:522
Inline: False
Direct callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff81448040-ffffffff814481c0: is_refcount_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool is_refcount_suitable(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8147da20)
Location: mm/khugepaged.c:534
Inline: False
Direct callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff8147da20-ffffffff8147db7d: is_refcount_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool is_refcount_suitable(struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814aa770)
Location: mm/khugepaged.c:524
Inline: False
Direct callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
**Symbols:**

```
ffffffff814aa770-ffffffff814aa808: is_refcount_suitable (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
</li>
</ul>
