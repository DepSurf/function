# Function: <code>xen_page_to_gfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff814c65b5)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff81574ca9)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff815fb19f)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81516ce5)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff815cc6fa)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8165b0ec)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff8154315f)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff815f92ce)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81688e46)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81556fe9)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff8160d44d)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8169e64e)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff815baff5)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff81675ccd)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81709819)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff815f36f1)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff816b1213)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817482f8)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160ccdc)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8160e750)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff816d1553)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8176c3b8)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8164198a)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff816424d9)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff8170cfe3)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817aa1d9)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In drivers/xen/grant-table.c (ffffffff81662f9a)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81664aa2)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff817312e3)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817cdc39)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In drivers/xen/grant-table.c (ffffffff817134ca)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81714667)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff817edabd)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/block/xen-blkfront.c:get_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8189814b)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In drivers/xen/grant-table.c (ffffffff817303ba)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81730d47)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff818023ed)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:get_indirect_grant
  - drivers/block/xen-blkfront.c:get_grant
```
```
In drivers/net/xen-netfront.c (ffffffff818a6510)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In drivers/xen/grant-table.c (ffffffff81713f57)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff817148d3)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff817e87db)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81889920)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In drivers/xen/grant-table.c (ffffffff8179099d)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81791720)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff81874d6b)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff8191c42d)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In drivers/xen/grant-table.c (ffffffff818c9881)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff818ca208)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/xen/grant-dma-ops.c (0)
Location: include/xen/page.h:31
Inline: False
```
```
In drivers/block/xen-blkfront.c (ffffffff819bd02f)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81a719bb)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In drivers/xen/grant-table.c (ffffffff81a1a660)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81a1adc8)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff81b326ef)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81c076fb)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In drivers/xen/grant-table.c (ffffffff81a634e0)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81a63f78)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff81b85b94)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81c6ce22)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In drivers/xen/grant-table.c (ffffffff81ab5d00)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81ab67b8)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd9aa4)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:get_indirect_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81d21757)
Location: include/xen/page.h:31
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082ccfc)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffff80001082e820)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffff800010926ebc)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffff800010a06e68)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81628e0a)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff8162a912)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff816f71c3)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff81792859)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81656dda)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff816588e2)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff817247a3)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817c2ab9)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
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
In drivers/xen/grant-table.c (ffffffff816713ba)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_dma_alloc_pages
```
```
In drivers/xen/balloon.c (ffffffff81672ef6)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
```
```
In drivers/block/xen-blkfront.c (ffffffff81740457)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
```
In drivers/net/xen-netfront.c (ffffffff817dcd79)
Location: include/xen/page.h:32
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
</details>
</li>
</ul>

## Differences
