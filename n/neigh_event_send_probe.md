# Function: <code>neigh_event_send_probe</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81c29ed1)
Location: include/net/neighbour.h:464
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_managed_work
```
```
In net/ipv4/route.c (ffffffff81cced35)
Location: include/net/neighbour.h:464
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/core/neighbour.c (ffffffff81ddcdf2)
Location: include/net/neighbour.h:461
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_managed_work
```
```
In net/ipv4/route.c (ffffffff81e8efa0)
Location: include/net/neighbour.h:461
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/core/neighbour.c (ffffffff81e4db3c)
Location: include/net/neighbour.h:459
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_managed_work
```
```
In net/ipv4/route.c (ffffffff81eed6a8)
Location: include/net/neighbour.h:459
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
In net/core/neighbour.c (ffffffff81f0c890)
Location: include/net/neighbour.h:457
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_managed_work
```
```
In net/ipv4/route.c (ffffffff81fb171c)
Location: include/net/neighbour.h:457
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
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
