# Function: <code>page_cache_free_page</code>

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
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff811cb7f0)
Location: mm/filemap.c:269
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
**Symbols:**

```
ffffffff811cb7f0-ffffffff811cb879: page_cache_free_page.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff811ec290)
Location: mm/filemap.c:269
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
**Symbols:**

```
ffffffff811ec290-ffffffff811ec31f: page_cache_free_page.isra.31 (STB_LOCAL)
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
In mm/filemap.c (ffffffff811fce90)
Location: mm/filemap.c:237
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
**Symbols:**

```
ffffffff811fce90-ffffffff811fcf21: page_cache_free_page.isra.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff81215310)
Location: mm/filemap.c:239
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
**Symbols:**

```
ffffffff81215310-ffffffff812153ad: page_cache_free_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff812226a0)
Location: mm/filemap.c:241
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
**Symbols:**

```
ffffffff812226a0-ffffffff8122273d: page_cache_free_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8124fce0)
Location: mm/filemap.c:241
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache
```
**Symbols:**

```
ffffffff8124fce0-ffffffff8124fd87: page_cache_free_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff81259b40)
Location: mm/filemap.c:242
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache
```
**Symbols:**

```
ffffffff81259b40-ffffffff81259bf9: page_cache_free_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8125de40)
Location: mm/filemap.c:233
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache
```
**Symbols:**

```
ffffffff8125de40-ffffffff8125def9: page_cache_free_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8129a560)
Location: mm/filemap.c:235
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache
```
**Symbols:**

```
ffffffff8129a560-ffffffff8129a616: page_cache_free_page.isra.0 (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffff8000102afc98)
Location: mm/filemap.c:241
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
**Symbols:**

```
ffff8000102afc98-ffff8000102afd60: page_cache_free_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e0220)
Location: mm/filemap.c:241
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void page_cache_free_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000365290)
Location: mm/filemap.c:241
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:delete_from_page_cache
```
**Symbols:**

```
c000000000365290-c000000000365400: page_cache_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d87b8)
Location: mm/filemap.c:241
Inline: True
Inline callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8121acf0)
Location: mm/filemap.c:241
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
**Symbols:**

```
ffffffff8121acf0-ffffffff8121ad8d: page_cache_free_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8120def0)
Location: mm/filemap.c:241
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
**Symbols:**

```
ffffffff8120def0-ffffffff8120df8d: page_cache_free_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff81218a90)
Location: mm/filemap.c:241
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
**Symbols:**

```
ffffffff81218a90-ffffffff81218b2d: page_cache_free_page.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff81227b80)
Location: mm/filemap.c:241
Inline: True
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
```
**Symbols:**

```
ffffffff81227b80-ffffffff81227c1d: page_cache_free_page.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
