# Function: <code>xen_alloc_unpopulated_pages</code>

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
int xen_alloc_unpopulated_pages(unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff81743900)
Location: drivers/xen/unpopulated-alloc.c:109
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81743900-ffffffff81743a08: xen_alloc_unpopulated_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xen_alloc_unpopulated_pages(unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff817272f0)
Location: drivers/xen/unpopulated-alloc.c:111
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff817272f0-ffffffff817273f8: xen_alloc_unpopulated_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xen_alloc_unpopulated_pages(unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff817a6370)
Location: drivers/xen/unpopulated-alloc.c:111
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff817a6370-ffffffff817a6478: xen_alloc_unpopulated_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xen_alloc_unpopulated_pages(unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff818e0490)
Location: drivers/xen/unpopulated-alloc.c:158
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_get
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff818e0490-ffffffff818e05c7: xen_alloc_unpopulated_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xen_alloc_unpopulated_pages(unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff81a349c0)
Location: drivers/xen/unpopulated-alloc.c:158
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_get
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81a349c0-ffffffff81a34af7: xen_alloc_unpopulated_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xen_alloc_unpopulated_pages(unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff81a7e3d0)
Location: drivers/xen/unpopulated-alloc.c:158
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_get
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81a7e3d0-ffffffff81a7e505: xen_alloc_unpopulated_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xen_alloc_unpopulated_pages(unsigned int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/unpopulated-alloc.c (ffffffff81ad0940)
Location: drivers/xen/unpopulated-alloc.c:158
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_page_cache_get
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81ad0940-ffffffff81ad0a75: xen_alloc_unpopulated_pages (STB_GLOBAL)
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
