# Function: <code>get_hwpoison_huge_page</code>

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
int get_hwpoison_huge_page(struct page *page, bool *hugetlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812de530)
Location: mm/hugetlb.c:5932
Inline: False
Direct callers:
  - mm/memory-failure.c:get_any_page
```
**Symbols:**

```
ffffffff812de530-ffffffff812de5be: get_hwpoison_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_hwpoison_huge_page(struct page *page, bool *hugetlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81325820)
Location: mm/hugetlb.c:6269
Inline: False
Direct callers:
  - mm/memory-failure.c:get_any_page
```
**Symbols:**

```
ffffffff81325820-ffffffff813258ae: get_hwpoison_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_hwpoison_huge_page(struct page *page, bool *hugetlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81394420)
Location: mm/hugetlb.c:6998
Inline: False
Direct callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
**Symbols:**

```
ffffffff81394420-ffffffff813944ae: get_hwpoison_huge_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_hwpoison_huge_page(struct page *page, bool *hugetlb, bool unpoison);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81412e50)
Location: mm/hugetlb.c:7279
Inline: False
Direct callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:get_any_page
```
**Symbols:**

```
ffffffff81412e50-ffffffff81412eea: get_hwpoison_huge_page (STB_GLOBAL)
```
</details>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool unpoison</code>
</li>
</ul>
</details>
</li>
</ul>
