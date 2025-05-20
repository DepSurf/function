# Function: <code>pgmap_altmap</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a91317)
Location: include/linux/memremap.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
```
In mm/memremap.c (ffffffff812c276a)
Location: include/linux/memremap.h:119
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages_release
  - mm/memremap.c:devm_memremap_pages_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ac865a)
Location: include/linux/memremap.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
```
In mm/memremap.c (ffffffff812d468d)
Location: include/linux/memremap.h:118
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81bc105a)
Location: include/linux/memremap.h:120
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
```
In mm/memremap.c (ffffffff8130a13b)
Location: include/linux/memremap.h:120
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c3a0ea)
Location: include/linux/memremap.h:126
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
```
In mm/memremap.c (ffffffff81316544)
Location: include/linux/memremap.h:126
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pageunmap_range
  - mm/memremap.c:pageunmap_range
  - mm/memremap.c:pgmap_pfn_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c2c6aa)
Location: include/linux/memremap.h:126
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
```
In mm/memremap.c (ffffffff8131c794)
Location: include/linux/memremap.h:126
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pgmap_pfn_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81d4adba)
Location: include/linux/memremap.h:126
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
```
In mm/memremap.c (ffffffff81369ad4)
Location: include/linux/memremap.h:126
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pgmap_pfn_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81f1a6f5)
Location: include/linux/memremap.h:122
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
```
In mm/memremap.c (ffffffff813e7894)
Location: include/linux/memremap.h:122
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pfn_len
  - mm/memremap.c:pgmap_pfn_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff820c2581)
Location: include/linux/memremap.h:147
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
```
In mm/memremap.c (ffffffff8146f524)
Location: include/linux/memremap.h:147
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pfn_len
  - mm/memremap.c:pgmap_pfn_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff821461c1)
Location: include/linux/memremap.h:147
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_zone_device
```
```
In mm/memremap.c (ffffffff814a3d14)
Location: include/linux/memremap.h:147
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pfn_len
  - mm/memremap.c:pgmap_pfn_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff822288e1)
Location: include/linux/memremap.h:148
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_zone_device
```
```
In mm/memremap.c (ffffffff814d4bb4)
Location: include/linux/memremap.h:148
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:pfn_len
  - mm/memremap.c:pgmap_pfn_valid
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ee858)
Location: include/linux/memremap.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
```
In mm/memremap.c (c00000000046debc)
Location: include/linux/memremap.h:118
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a674ca)
Location: include/linux/memremap.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
```
In mm/memremap.c (ffffffff812ccc6d)
Location: include/linux/memremap.h:118
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a23f8a)
Location: include/linux/memremap.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
```
In mm/memremap.c (ffffffff812bdadd)
Location: include/linux/memremap.h:118
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ad38da)
Location: include/linux/memremap.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
```
In mm/memremap.c (ffffffff812caa7d)
Location: include/linux/memremap.h:118
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81adfdda)
Location: include/linux/memremap.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
```
```
In mm/memremap.c (ffffffff812db79d)
Location: include/linux/memremap.h:118
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:memunmap_pages
```
</details>
</li>
</ul>

## Differences
