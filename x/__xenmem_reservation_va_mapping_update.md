# Function: <code>__xenmem_reservation_va_mapping_update</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_update(long unsigned int count, struct page **pages, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff8160fe40)
Location: drivers/xen/mem-reservation.c:29
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff8160fe40-ffffffff8160ff2d: __xenmem_reservation_va_mapping_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_update(long unsigned int count, struct page **pages, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81643c70)
Location: drivers/xen/mem-reservation.c:29
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81643c70-ffffffff81643d40: __xenmem_reservation_va_mapping_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_update(long unsigned int count, struct page **pages, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81666220)
Location: drivers/xen/mem-reservation.c:29
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81666220-ffffffff816662f0: __xenmem_reservation_va_mapping_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_update(long unsigned int count, struct page **pages, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81715960)
Location: drivers/xen/mem-reservation.c:29
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:increase_reservation
```
**Symbols:**

```
ffffffff81715960-ffffffff81715a36: __xenmem_reservation_va_mapping_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_update(long unsigned int count, struct page **pages, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff817322e0)
Location: drivers/xen/mem-reservation.c:29
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:increase_reservation
```
**Symbols:**

```
ffffffff817322e0-ffffffff817323b6: __xenmem_reservation_va_mapping_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_update(long unsigned int count, struct page **pages, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81715db0)
Location: drivers/xen/mem-reservation.c:29
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81715db0-ffffffff81715e80: __xenmem_reservation_va_mapping_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_update(long unsigned int count, struct page **pages, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81793010)
Location: drivers/xen/mem-reservation.c:29
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81793010-ffffffff817930e0: __xenmem_reservation_va_mapping_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_update(long unsigned int count, struct page **pages, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff818cb990)
Location: drivers/xen/mem-reservation.c:29
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff818cb990-ffffffff818cba70: __xenmem_reservation_va_mapping_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_update(long unsigned int count, struct page **pages, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81a1cd50)
Location: drivers/xen/mem-reservation.c:29
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81a1cd50-ffffffff81a1ce30: __xenmem_reservation_va_mapping_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_update(long unsigned int count, struct page **pages, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81a65f50)
Location: drivers/xen/mem-reservation.c:29
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81a65f50-ffffffff81a66030: __xenmem_reservation_va_mapping_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_update(long unsigned int count, struct page **pages, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81ab8790)
Location: drivers/xen/mem-reservation.c:29
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81ab8790-ffffffff81ab8870: __xenmem_reservation_va_mapping_update (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_update(long unsigned int count, struct page **pages, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff8162bf50)
Location: drivers/xen/mem-reservation.c:29
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff8162bf50-ffffffff8162c020: __xenmem_reservation_va_mapping_update (STB_GLOBAL)
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
void __xenmem_reservation_va_mapping_update(long unsigned int count, struct page **pages, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff8165a060)
Location: drivers/xen/mem-reservation.c:29
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff8165a060-ffffffff8165a130: __xenmem_reservation_va_mapping_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_update(long unsigned int count, struct page **pages, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81674630)
Location: drivers/xen/mem-reservation.c:29
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81674630-ffffffff81674700: __xenmem_reservation_va_mapping_update (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Arch</b>
<ul>
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
