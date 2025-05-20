# Function: <code>mctp_address_unicast</code>

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
In net/mctp/device.c (ffffffff81e381cd)
Location: include/net/mctp.h:41
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff81e3ab06)
Location: include/net/mctp.h:41
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_add
```
```
In net/mctp/neigh.c (ffffffff81e3b7ed)
Location: include/net/mctp.h:41
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_newneigh
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
In net/mctp/device.c (ffffffff8201141d)
Location: include/net/mctp.h:41
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff820140d6)
Location: include/net/mctp.h:41
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_add
```
```
In net/mctp/neigh.c (ffffffff82015096)
Location: include/net/mctp.h:41
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_newneigh
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
In net/mctp/device.c (ffffffff8208e1db)
Location: include/net/mctp.h:41
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff82090f56)
Location: include/net/mctp.h:41
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_add
```
```
In net/mctp/neigh.c (ffffffff82091eb3)
Location: include/net/mctp.h:41
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_newneigh
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
In net/mctp/device.c (ffffffff8216469b)
Location: include/net/mctp.h:41
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_rtm_newaddr
```
```
In net/mctp/route.c (ffffffff82167476)
Location: include/net/mctp.h:41
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_pkttype_receive
  - net/mctp/route.c:mctp_route_add
```
```
In net/mctp/neigh.c (ffffffff8216848b)
Location: include/net/mctp.h:41
Inline: True
Inline callers:
  - net/mctp/neigh.c:mctp_rtm_newneigh
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
