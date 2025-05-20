# Function: <code>gnttab_count_grant</code>

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
In drivers/block/xen-blkfront.c (0)
Location: include/xen/grant_table.h:278
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/xen/grant_table.h:278
Inline: True
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
In drivers/block/xen-blkfront.c (ffffffff815cbe9c)
Location: include/xen/grant_table.h:278
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/net/xen-netfront.c (ffffffff8165aac7)
Location: include/xen/grant_table.h:278
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff815f8a9b)
Location: include/xen/grant_table.h:278
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/net/xen-netfront.c (ffffffff8168881f)
Location: include/xen/grant_table.h:278
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff8160b2fb)
Location: include/xen/grant_table.h:278
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/net/xen-netfront.c (ffffffff8169dfe1)
Location: include/xen/grant_table.h:278
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff81673bcb)
Location: include/xen/grant_table.h:281
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/net/xen-netfront.c (ffffffff81709181)
Location: include/xen/grant_table.h:281
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff816afbde)
Location: include/xen/grant_table.h:281
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/net/xen-netfront.c (ffffffff81747cc5)
Location: include/xen/grant_table.h:281
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff816cfd2b)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
```
In drivers/net/xen-netfront.c (ffffffff8176bda8)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff8170b6a4)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff817a9ba2)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff8172f9a4)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff817cd612)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff817ee4a1)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff818990f2)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff81802da1)
Location: include/xen/grant_table.h:320
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff818a75f2)
Location: include/xen/grant_table.h:320
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff817e7421)
Location: include/xen/grant_table.h:327
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff8188aea4)
Location: include/xen/grant_table.h:327
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff81873467)
Location: include/xen/grant_table.h:342
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff8191da0d)
Location: include/xen/grant_table.h:342
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff819bd3dd)
Location: include/xen/grant_table.h:335
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff81a7508a)
Location: include/xen/grant_table.h:335
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff81b32aad)
Location: include/xen/grant_table.h:335
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff81c06a10)
Location: include/xen/grant_table.h:335
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff81b85f7f)
Location: include/xen/grant_table.h:335
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff81c6c11f)
Location: include/xen/grant_table.h:335
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff81bd9e77)
Location: include/xen/grant_table.h:335
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff81d20acc)
Location: include/xen/grant_table.h:335
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffff800010926700)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffff800010a09388)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff816f5914)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff81792232)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff81722e64)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff817c2492)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
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
In drivers/block/xen-blkfront.c (ffffffff8173e2a4)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
```
In drivers/net/xen-netfront.c (ffffffff817dc752)
Location: include/xen/grant_table.h:302
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
</details>
</li>
</ul>

## Differences
