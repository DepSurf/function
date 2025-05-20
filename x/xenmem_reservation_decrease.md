# Function: <code>xenmem_reservation_decrease</code>

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
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff8160fdc0)
Location: drivers/xen/mem-reservation.c:109
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8160fdc0-ffffffff8160fe33: xenmem_reservation_decrease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81643bf0)
Location: drivers/xen/mem-reservation.c:109
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81643bf0-ffffffff81643c64: xenmem_reservation_decrease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff816661a0)
Location: drivers/xen/mem-reservation.c:109
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff816661a0-ffffffff81666214: xenmem_reservation_decrease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff817158e0)
Location: drivers/xen/mem-reservation.c:109
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff817158e0-ffffffff81715954: xenmem_reservation_decrease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81732260)
Location: drivers/xen/mem-reservation.c:109
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81732260-ffffffff817322d4: xenmem_reservation_decrease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81715d30)
Location: drivers/xen/mem-reservation.c:109
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81715d30-ffffffff81715da4: xenmem_reservation_decrease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81792f90)
Location: drivers/xen/mem-reservation.c:109
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81792f90-ffffffff81793004: xenmem_reservation_decrease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff818cb900)
Location: drivers/xen/mem-reservation.c:102
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff818cb900-ffffffff818cb983: xenmem_reservation_decrease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81a1ccb0)
Location: drivers/xen/mem-reservation.c:102
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81a1ccb0-ffffffff81a1cd33: xenmem_reservation_decrease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81a65eb0)
Location: drivers/xen/mem-reservation.c:102
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81a65eb0-ffffffff81a65f33: xenmem_reservation_decrease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81ab8700)
Location: drivers/xen/mem-reservation.c:102
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81ab8700-ffffffff81ab8774: xenmem_reservation_decrease (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffff80001082fcc0)
Location: drivers/xen/mem-reservation.c:109
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffff80001082fcc0-ffff80001082fd30: xenmem_reservation_decrease (STB_GLOBAL)
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
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff8162bed0)
Location: drivers/xen/mem-reservation.c:109
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8162bed0-ffffffff8162bf44: xenmem_reservation_decrease (STB_GLOBAL)
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
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81659fe0)
Location: drivers/xen/mem-reservation.c:109
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff81659fe0-ffffffff8165a054: xenmem_reservation_decrease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xenmem_reservation_decrease(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff816745b0)
Location: drivers/xen/mem-reservation.c:109
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff816745b0-ffffffff81674624: xenmem_reservation_decrease (STB_GLOBAL)
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
