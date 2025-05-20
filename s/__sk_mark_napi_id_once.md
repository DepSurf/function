# Function: <code>__sk_mark_napi_id_once</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ae26f8)
Location: include/net/busy_poll.h:138
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81b659ee)
Location: include/net/busy_poll.h:138
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/xdp/xsk.c (ffffffff81bb7e3f)
Location: include/net/busy_poll.h:138
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
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
In net/ipv4/udp.c (ffffffff81acd8c9)
Location: include/net/busy_poll.h:138
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81b561a6)
Location: include/net/busy_poll.h:138
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/xdp/xsk.c (ffffffff81ba7007)
Location: include/net/busy_poll.h:138
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
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
In net/ipv4/udp.c (ffffffff81b8c2a6)
Location: include/net/busy_poll.h:138
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81c1c823)
Location: include/net/busy_poll.h:138
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/xdp/xsk.c (ffffffff81c74c87)
Location: include/net/busy_poll.h:138
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
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
In net/ipv4/udp.c (ffffffff81d1c8be)
Location: include/net/busy_poll.h:152
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81db90ca)
Location: include/net/busy_poll.h:152
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/xdp/xsk.c (ffffffff81e18d3b)
Location: include/net/busy_poll.h:152
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
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
In net/ipv4/udp.c (ffffffff81ee3938)
Location: include/net/busy_poll.h:152
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81f890af)
Location: include/net/busy_poll.h:152
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/xdp/xsk.c (ffffffff81feffdb)
Location: include/net/busy_poll.h:152
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
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
In net/ipv4/udp.c (ffffffff81f431ab)
Location: include/net/busy_poll.h:152
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81fe8471)
Location: include/net/busy_poll.h:152
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/xdp/xsk.c (ffffffff8206c17b)
Location: include/net/busy_poll.h:152
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
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
In net/ipv4/udp.c (ffffffff82009116)
Location: include/net/busy_poll.h:153
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff820b6fc7)
Location: include/net/busy_poll.h:153
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/xdp/xsk.c (ffffffff8213d2da)
Location: include/net/busy_poll.h:153
Inline: True
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
