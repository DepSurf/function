# Function: <code>__xenmem_reservation_va_mapping_reset</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff8160ff30)
Location: drivers/xen/mem-reservation.c:63
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8160ff30-ffffffff8160ffcf: __xenmem_reservation_va_mapping_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81643d40)
Location: drivers/xen/mem-reservation.c:63
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81643d40-ffffffff81643daf: __xenmem_reservation_va_mapping_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff816662f0)
Location: drivers/xen/mem-reservation.c:63
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff816662f0-ffffffff8166635f: __xenmem_reservation_va_mapping_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81715a40)
Location: drivers/xen/mem-reservation.c:63
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81715a40-ffffffff81715aaf: __xenmem_reservation_va_mapping_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff817323c0)
Location: drivers/xen/mem-reservation.c:63
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff817323c0-ffffffff8173242f: __xenmem_reservation_va_mapping_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81715e80)
Location: drivers/xen/mem-reservation.c:63
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81715e80-ffffffff81715eef: __xenmem_reservation_va_mapping_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff817930e0)
Location: drivers/xen/mem-reservation.c:63
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff817930e0-ffffffff8179314f: __xenmem_reservation_va_mapping_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff818cba70)
Location: drivers/xen/mem-reservation.c:58
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff818cba70-ffffffff818cbb07: __xenmem_reservation_va_mapping_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81a1ce40)
Location: drivers/xen/mem-reservation.c:58
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81a1ce40-ffffffff81a1ced7: __xenmem_reservation_va_mapping_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81a66040)
Location: drivers/xen/mem-reservation.c:58
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81a66040-ffffffff81a660d7: __xenmem_reservation_va_mapping_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81ab8880)
Location: drivers/xen/mem-reservation.c:58
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81ab8880-ffffffff81ab8917: __xenmem_reservation_va_mapping_reset (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff8162c020)
Location: drivers/xen/mem-reservation.c:63
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8162c020-ffffffff8162c08f: __xenmem_reservation_va_mapping_reset (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff8165a130)
Location: drivers/xen/mem-reservation.c:63
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8165a130-ffffffff8165a19f: __xenmem_reservation_va_mapping_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __xenmem_reservation_va_mapping_reset(long unsigned int count, struct page **pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81674700)
Location: drivers/xen/mem-reservation.c:63
Inline: True
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81674700-ffffffff8167476f: __xenmem_reservation_va_mapping_reset (STB_GLOBAL)
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
