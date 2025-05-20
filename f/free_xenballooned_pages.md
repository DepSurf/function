# Function: <code>free_xenballooned_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff814c67a0)
Location: drivers/xen/balloon.c:670
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:xen_pvh_gnttab_setup
  - drivers/xen/grant-table.c:gnttab_free_pages
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff814c67a0-ffffffff814c683e: free_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81516ef0)
Location: drivers/xen/balloon.c:692
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81516ef0-ffffffff81516f95: free_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81543360)
Location: drivers/xen/balloon.c:690
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81543360-ffffffff815433e8: free_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff815571f0)
Location: drivers/xen/balloon.c:691
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff815571f0-ffffffff81557278: free_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff815bb200)
Location: drivers/xen/balloon.c:738
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff815bb200-ffffffff815bb288: free_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff815f38a0)
Location: drivers/xen/balloon.c:738
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_free_pages
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff815f38a0-ffffffff815f3928: free_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff8160e8c0)
Location: drivers/xen/balloon.c:633
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff8160e8c0-ffffffff8160e948: free_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81642650)
Location: drivers/xen/balloon.c:649
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81642650-ffffffff816426e3: free_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81664c20)
Location: drivers/xen/balloon.c:644
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81664c20-ffffffff81664ca9: free_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff817143e0)
Location: drivers/xen/balloon.c:650
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff817143e0-ffffffff817144ad: free_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81731620)
Location: drivers/xen/balloon.c:635
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
**Symbols:**

```
ffffffff81731620-ffffffff817316ed: free_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81715020)
Location: drivers/xen/balloon.c:635
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
**Symbols:**

```
ffffffff81715020-ffffffff817150ed: free_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81792030)
Location: drivers/xen/balloon.c:669
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
**Symbols:**

```
ffffffff81792030-ffffffff817920fb: free_xenballooned_pages (STB_GLOBAL)
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
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffff80001082e938)
Location: drivers/xen/balloon.c:644
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffff80001082e938-ffff80001082e9e8: free_xenballooned_pages (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff8162ae00)
Location: drivers/xen/balloon.c:644
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff8162ae00-ffffffff8162ae89: free_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81658a60)
Location: drivers/xen/balloon.c:644
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81658a60-ffffffff81658ae9: free_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81673070)
Location: drivers/xen/balloon.c:644
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81673070-ffffffff816730f9: free_xenballooned_pages (STB_GLOBAL)
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
