# Function: <code>gnttab_free_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff814c5580)
Location: drivers/xen/grant-table.c:717
Inline: False
```
**Symbols:**

```
ffffffff814c5580-ffffffff814c55b8: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81515bf0)
Location: drivers/xen/grant-table.c:716
Inline: False
```
**Symbols:**

```
ffffffff81515bf0-ffffffff81515c28: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81542070)
Location: drivers/xen/grant-table.c:716
Inline: False
```
**Symbols:**

```
ffffffff81542070-ffffffff815420a8: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81555e60)
Location: drivers/xen/grant-table.c:717
Inline: False
```
**Symbols:**

```
ffffffff81555e60-ffffffff81555e98: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815b9ac0)
Location: drivers/xen/grant-table.c:809
Inline: False
```
**Symbols:**

```
ffffffff815b9ac0-ffffffff815b9af8: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815f1950)
Location: drivers/xen/grant-table.c:809
Inline: False
```
**Symbols:**

```
ffffffff815f1950-ffffffff815f1988: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160c610)
Location: drivers/xen/grant-table.c:838
Inline: True
```
**Symbols:**

```
ffffffff8160c610-ffffffff8160c635: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81641770)
Location: drivers/xen/grant-table.c:838
Inline: True
```
**Symbols:**

```
ffffffff81641770-ffffffff81641799: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81662910)
Location: drivers/xen/grant-table.c:838
Inline: True
```
**Symbols:**

```
ffffffff81662910-ffffffff81662939: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81712070)
Location: drivers/xen/grant-table.c:836
Inline: True
```
**Symbols:**

```
ffffffff81712070-ffffffff81712099: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8173000a)
Location: drivers/xen/grant-table.c:959
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
**Symbols:**

```
ffffffff8172ee00-ffffffff8172ee29: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81713a59)
Location: drivers/xen/grant-table.c:959
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
**Symbols:**

```
ffffffff81712850-ffffffff81712879: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8179046b)
Location: drivers/xen/grant-table.c:966
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
**Symbols:**

```
ffffffff8178f2f0-ffffffff8178f319: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c8925)
Location: drivers/xen/grant-table.c:1032
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
**Symbols:**

```
ffffffff818c75c0-ffffffff818c75ed: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a19385)
Location: drivers/xen/grant-table.c:1032
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
**Symbols:**

```
ffffffff81a180f0-ffffffff81a1811d: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a626f5)
Location: drivers/xen/grant-table.c:1050
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
**Symbols:**

```
ffffffff81a61180-ffffffff81a611ad: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab4f25)
Location: drivers/xen/grant-table.c:1048
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
```
**Symbols:**

```
ffffffff81ab39b0-ffffffff81ab39dd: gnttab_free_pages (STB_GLOBAL)
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
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082caf8)
Location: drivers/xen/grant-table.c:838
Inline: True
```
**Symbols:**

```
ffff80001082caf8-ffff80001082cb38: gnttab_free_pages (STB_GLOBAL)
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
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81628780)
Location: drivers/xen/grant-table.c:838
Inline: True
```
**Symbols:**

```
ffffffff81628780-ffffffff816287a9: gnttab_free_pages (STB_GLOBAL)
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
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81656750)
Location: drivers/xen/grant-table.c:838
Inline: True
```
**Symbols:**

```
ffffffff81656750-ffffffff81656779: gnttab_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void gnttab_free_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81670d30)
Location: drivers/xen/grant-table.c:838
Inline: True
```
**Symbols:**

```
ffffffff81670d30-ffffffff81670d59: gnttab_free_pages (STB_GLOBAL)
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
