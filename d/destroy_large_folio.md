# Function: <code>destroy_large_folio</code>

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
void destroy_large_folio(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e6fa0)
Location: mm/page_alloc.c:806
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:__folio_put
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:shrink_folio_list
```
**Symbols:**

```
ffffffff813e6fa0-ffffffff813e6fea: destroy_large_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void destroy_large_folio(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141c0f0)
Location: mm/page_alloc.c:622
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:__folio_put
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:shrink_folio_list
```
**Symbols:**

```
ffffffff8141c0f0-ffffffff8141c13a: destroy_large_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void destroy_large_folio(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144bb50)
Location: mm/page_alloc.c:592
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:put_pages_list
  - mm/swap.c:__folio_put
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:shrink_folio_list
```
**Symbols:**

```
ffffffff8144bb50-ffffffff8144bbf0: destroy_large_folio (STB_GLOBAL)
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
