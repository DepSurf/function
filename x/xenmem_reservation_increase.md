# Function: <code>xenmem_reservation_increase</code>

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
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff8160fd40)
Location: drivers/xen/mem-reservation.c:93
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff8160fd40-ffffffff8160fdb3: xenmem_reservation_increase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81643b70)
Location: drivers/xen/mem-reservation.c:93
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81643b70-ffffffff81643be4: xenmem_reservation_increase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81666120)
Location: drivers/xen/mem-reservation.c:93
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81666120-ffffffff81666194: xenmem_reservation_increase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81715860)
Location: drivers/xen/mem-reservation.c:93
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:increase_reservation
  - drivers/xen/balloon.c:increase_reservation
```
**Symbols:**

```
ffffffff81715860-ffffffff817158d4: xenmem_reservation_increase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff817321e0)
Location: drivers/xen/mem-reservation.c:93
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:increase_reservation
  - drivers/xen/balloon.c:increase_reservation
```
**Symbols:**

```
ffffffff817321e0-ffffffff81732254: xenmem_reservation_increase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81715cb0)
Location: drivers/xen/mem-reservation.c:93
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81715cb0-ffffffff81715d24: xenmem_reservation_increase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81792f10)
Location: drivers/xen/mem-reservation.c:93
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81792f10-ffffffff81792f84: xenmem_reservation_increase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff818cb870)
Location: drivers/xen/mem-reservation.c:86
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff818cb870-ffffffff818cb8f3: xenmem_reservation_increase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81a1cc10)
Location: drivers/xen/mem-reservation.c:86
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81a1cc10-ffffffff81a1cc93: xenmem_reservation_increase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81a65e10)
Location: drivers/xen/mem-reservation.c:86
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81a65e10-ffffffff81a65e93: xenmem_reservation_increase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81ab8670)
Location: drivers/xen/mem-reservation.c:86
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81ab8670-ffffffff81ab86e4: xenmem_reservation_increase (STB_GLOBAL)
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
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffff80001082fc50)
Location: drivers/xen/mem-reservation.c:93
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffff80001082fc50-ffff80001082fcc0: xenmem_reservation_increase (STB_GLOBAL)
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
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff8162be50)
Location: drivers/xen/mem-reservation.c:93
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff8162be50-ffffffff8162bec4: xenmem_reservation_increase (STB_GLOBAL)
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
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81659f60)
Location: drivers/xen/mem-reservation.c:93
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81659f60-ffffffff81659fd4: xenmem_reservation_increase (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xenmem_reservation_increase(int count, xen_pfn_t *frames);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/mem-reservation.c (ffffffff81674530)
Location: drivers/xen/mem-reservation.c:93
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_dma_free_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81674530-ffffffff816745a4: xenmem_reservation_increase (STB_GLOBAL)
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
