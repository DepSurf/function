# Function: <code>unaccount_page_cache_page</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ca0b0)
Location: mm/filemap.c:185
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffffffff811ca0b0-ffffffff811ca2ea: unaccount_page_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:185
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffffffff811eb230-ffffffff811eb39d: unaccount_page_cache_page (STB_LOCAL)
ffffffff811f0c14-ffffffff811f0cbf: unaccount_page_cache_page.cold.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:153
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffffffff811fbda0-ffffffff811fbf0f: unaccount_page_cache_page (STB_LOCAL)
ffffffff81202a6e-ffffffff81202b1b: unaccount_page_cache_page.cold.58 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:155
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffffffff81213e80-ffffffff81213fec: unaccount_page_cache_page (STB_LOCAL)
ffffffff81219e9e-ffffffff81219f53: unaccount_page_cache_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:156
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffffffff81221690-ffffffff81221814: unaccount_page_cache_page (STB_LOCAL)
ffffffff8122780e-ffffffff812278c3: unaccount_page_cache_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:156
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache
```
**Symbols:**

```
ffffffff8124f520-ffffffff8124f76b: unaccount_page_cache_page (STB_LOCAL)
ffffffff8125414d-ffffffff81254202: unaccount_page_cache_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:157
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache
```
**Symbols:**

```
ffffffff81259880-ffffffff812599ed: unaccount_page_cache_page (STB_LOCAL)
ffffffff81be69ed-ffffffff81be6aa2: unaccount_page_cache_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:148
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffffffff8125da10-ffffffff8125db79: unaccount_page_cache_page (STB_LOCAL)
ffffffff81bd8783-ffffffff81bd8838: unaccount_page_cache_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:150
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffffffff81299ca0-ffffffff81299e09: unaccount_page_cache_page (STB_LOCAL)
ffffffff81cb9dda-ffffffff81cb9e92: unaccount_page_cache_page.cold (STB_LOCAL)
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
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102aeca8)
Location: mm/filemap.c:156
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffff8000102aeca8-ffff8000102aef0c: unaccount_page_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04da8f0)
Location: mm/filemap.c:156
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
c04da8f0-c04dab40: unaccount_page_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000362110)
Location: mm/filemap.c:156
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
c000000000362110-c000000000362468: unaccount_page_cache_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d428e)
Location: mm/filemap.c:156
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffffffe0001d428e-ffffffe0001d4446: unaccount_page_cache_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:156
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffffffff81219ce0-ffffffff81219e64: unaccount_page_cache_page (STB_LOCAL)
ffffffff8121fe5e-ffffffff8121ff13: unaccount_page_cache_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:156
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffffffff8120cef0-ffffffff8120d074: unaccount_page_cache_page (STB_LOCAL)
ffffffff8121300e-ffffffff812130c3: unaccount_page_cache_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:156
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffffffff81217a80-ffffffff81217c04: unaccount_page_cache_page (STB_LOCAL)
ffffffff8121dbfe-ffffffff8121dcb3: unaccount_page_cache_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void unaccount_page_cache_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:156
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
**Symbols:**

```
ffffffff81226b40-ffffffff81226cc4: unaccount_page_cache_page (STB_LOCAL)
ffffffff8122cc6e-ffffffff8122cd23: unaccount_page_cache_page.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
