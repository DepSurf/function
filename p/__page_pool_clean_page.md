# Function: <code>__page_pool_clean_page</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (ffffffff818bda15)
Location: net/core/page_pool.c:175
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_return_page
Direct callers:
  - net/core/page_pool.c:__page_pool_return_page
```
**Symbols:**

```
ffffffff818bd820-ffffffff818bd88a: __page_pool_clean_page.isra.6.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/page_pool.c (ffffffff818e4df5)
Location: net/core/page_pool.c:175
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_return_page
Direct callers:
  - net/core/page_pool.c:__page_pool_return_page
```
**Symbols:**

```
ffffffff818e4d60-ffffffff818e4de1: __page_pool_clean_page.isra.9.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __page_pool_clean_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81934190)
Location: net/core/page_pool.c:222
Inline: False
Direct callers:
  - net/core/page_pool.c:__page_pool_request_shutdown
  - net/core/page_pool.c:__page_pool_request_shutdown
  - net/core/page_pool.c:page_pool_unmap_page
```
**Symbols:**

```
ffffffff81934190-ffffffff81934284: __page_pool_clean_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __page_pool_clean_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81966dc0)
Location: net/core/page_pool.c:210
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_unmap_page
```
**Symbols:**

```
ffffffff81966dc0-ffffffff81966eb7: __page_pool_clean_page (STB_LOCAL)
```
</details>
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
void __page_pool_clean_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffff800010c0c888)
Location: net/core/page_pool.c:210
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_unmap_page
```
**Symbols:**

```
ffff800010c0c888-ffff800010c0c9c4: __page_pool_clean_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __page_pool_clean_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c0d24a70)
Location: net/core/page_pool.c:210
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_unmap_page
```
**Symbols:**

```
c0d24a70-c0d24bbc: __page_pool_clean_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __page_pool_clean_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c000000000cf79b0)
Location: net/core/page_pool.c:210
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_unmap_page
```
**Symbols:**

```
c000000000cf79b0-c000000000cf7b50: __page_pool_clean_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __page_pool_clean_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffe000789862)
Location: net/core/page_pool.c:210
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_unmap_page
```
**Symbols:**

```
ffffffe000789862-ffffffe000789944: __page_pool_clean_page (STB_LOCAL)
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
void __page_pool_clean_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81906d90)
Location: net/core/page_pool.c:210
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_unmap_page
```
**Symbols:**

```
ffffffff81906d90-ffffffff81906e87: __page_pool_clean_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __page_pool_clean_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818c0ba0)
Location: net/core/page_pool.c:210
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_unmap_page
```
**Symbols:**

```
ffffffff818c0ba0-ffffffff818c0c97: __page_pool_clean_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __page_pool_clean_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81957dc0)
Location: net/core/page_pool.c:210
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_unmap_page
```
**Symbols:**

```
ffffffff81957dc0-ffffffff81957eb7: __page_pool_clean_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __page_pool_clean_page(struct page_pool *pool, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81979ea0)
Location: net/core/page_pool.c:210
Inline: False
Direct callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_unmap_page
```
**Symbols:**

```
ffffffff81979ea0-ffffffff81979fa5: __page_pool_clean_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
