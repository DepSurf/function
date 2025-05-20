# Function: <code>xen_free_unpopulated_pages</code>

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
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff81743650)
Location: drivers/xen/unpopulated-alloc.c:157
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81743650-ffffffff817436c3: xen_free_unpopulated_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff81727040)
Location: drivers/xen/unpopulated-alloc.c:159
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81727040-ffffffff817270b3: xen_free_unpopulated_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff817a60c0)
Location: drivers/xen/unpopulated-alloc.c:159
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff817a60c0-ffffffff817a6133: xen_free_unpopulated_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff818e00b0)
Location: drivers/xen/unpopulated-alloc.c:214
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff818e00b0-ffffffff818e014f: xen_free_unpopulated_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff81a34560)
Location: drivers/xen/unpopulated-alloc.c:214
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81a34560-ffffffff81a345ff: xen_free_unpopulated_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff81a7df70)
Location: drivers/xen/unpopulated-alloc.c:214
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81a7df70-ffffffff81a7e00f: xen_free_unpopulated_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xen_free_unpopulated_pages(unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff81ad0450)
Location: drivers/xen/unpopulated-alloc.c:214
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/grant-table.c:gnttab_page_cache_shrink
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81ad0450-ffffffff81ad04ef: xen_free_unpopulated_pages (STB_GLOBAL)
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
