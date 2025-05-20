# Function: <code>alloc_xenballooned_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff814c6da0)
Location: drivers/xen/balloon.c:625
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:xen_pvh_gnttab_setup
  - drivers/xen/grant-table.c:gnttab_alloc_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff814c6da0-ffffffff814c6f53: alloc_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81517620)
Location: drivers/xen/balloon.c:647
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_alloc_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81517620-ffffffff815177d6: alloc_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81543a90)
Location: drivers/xen/balloon.c:645
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_alloc_pages
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81543a90-ffffffff81543c7c: alloc_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81557930)
Location: drivers/xen/balloon.c:646
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81557930-ffffffff81557b07: alloc_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff815bba70)
Location: drivers/xen/balloon.c:691
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff815bba70-ffffffff815bbc67: alloc_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff815f4020)
Location: drivers/xen/balloon.c:691
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff815f4020-ffffffff815f4200: alloc_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff8160eed0)
Location: drivers/xen/balloon.c:586
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff8160eed0-ffffffff8160f0b0: alloc_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81642cb0)
Location: drivers/xen/balloon.c:601
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81642cb0-ffffffff81642ea4: alloc_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81665260)
Location: drivers/xen/balloon.c:597
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81665260-ffffffff81665451: alloc_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81714a90)
Location: drivers/xen/balloon.c:597
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff81714a90-ffffffff81714bd1: alloc_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff817316f0)
Location: drivers/xen/balloon.c:582
Inline: False
```
**Symbols:**

```
ffffffff817316f0-ffffffff81731831: alloc_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff817150f0)
Location: drivers/xen/balloon.c:582
Inline: False
```
**Symbols:**

```
ffffffff817150f0-ffffffff81715325: alloc_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81792100)
Location: drivers/xen/balloon.c:616
Inline: False
```
**Symbols:**

```
ffffffff81792100-ffffffff81792335: alloc_xenballooned_pages (STB_GLOBAL)
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
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffff80001082efd0)
Location: drivers/xen/balloon.c:597
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffff80001082efd0-ffff80001082f16c: alloc_xenballooned_pages (STB_GLOBAL)
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
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff8162ae90)
Location: drivers/xen/balloon.c:597
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff8162ae90-ffffffff8162aff5: alloc_xenballooned_pages (STB_GLOBAL)
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
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff816590a0)
Location: drivers/xen/balloon.c:597
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff816590a0-ffffffff81659291: alloc_xenballooned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int alloc_xenballooned_pages(int nr_pages, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff816736a0)
Location: drivers/xen/balloon.c:597
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xlate_mmu.c:xen_xlate_map_ballooned_pages
```
**Symbols:**

```
ffffffff816736a0-ffffffff8167388c: alloc_xenballooned_pages (STB_GLOBAL)
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
