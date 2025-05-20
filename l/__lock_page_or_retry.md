# Function: <code>__lock_page_or_retry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118f6c0)
Location: mm/filemap.c:903
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/memory.c:handle_mm_fault
  - fs/dax.c:__dax_fault
```
**Symbols:**

```
ffffffff8118f6c0-ffffffff8118f758: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a3480)
Location: mm/filemap.c:946
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff811a3480-ffffffff811a3557: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b3440)
Location: mm/filemap.c:1048
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff811b3440-ffffffff811b3739: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ba270)
Location: mm/filemap.c:1174
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff811ba270-ffffffff811ba554: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cdae0)
Location: mm/filemap.c:1296
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff811cdae0-ffffffff811cddbb: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ef610)
Location: mm/filemap.c:1296
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff811ef610-ffffffff811ef8f9: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81201680)
Location: mm/filemap.c:1351
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81201680-ffffffff81201b46: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219260)
Location: mm/filemap.c:1399
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81219260-ffffffff812196f8: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226b50)
Location: mm/filemap.c:1408
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81226b50-ffffffff81226fe8: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812518e0)
Location: mm/filemap.c:1383
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812518e0-ffffffff81251acb: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125d020)
Location: mm/filemap.c:1573
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8125d020-ffffffff8125d215: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81262860)
Location: mm/filemap.c:1644
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81262860-ffffffff81262a4b: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129eeb0)
Location: mm/filemap.c:1699
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:remove_device_exclusive_entry
```
**Symbols:**

```
ffffffff8129eeb0-ffffffff8129f096: __lock_page_or_retry (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b3cd8)
Location: mm/filemap.c:1408
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffff8000102b3cd8-ffff8000102b3e0c: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e1168)
Location: mm/filemap.c:1408
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
c04e1168-c04e1644: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c00000000036ae30)
Location: mm/filemap.c:1408
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
c00000000036ae30-c00000000036b4e4: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d9398)
Location: mm/filemap.c:1408
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffe0001d9398-ffffffe0001d97d4: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121f1a0)
Location: mm/filemap.c:1408
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8121f1a0-ffffffff8121f638: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81212360)
Location: mm/filemap.c:1408
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81212360-ffffffff812127ec: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121cf40)
Location: mm/filemap.c:1408
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8121cf40-ffffffff8121d3d8: __lock_page_or_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __lock_page_or_retry(struct page *page, struct mm_struct *mm, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122bfc0)
Location: mm/filemap.c:1408
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8122bfc0-ffffffff8122c451: __lock_page_or_retry (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
