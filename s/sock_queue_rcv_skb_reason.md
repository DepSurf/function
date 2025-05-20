# Function: <code>sock_queue_rcv_skb_reason</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_queue_rcv_skb_reason(struct sock *sk, struct sk_buff *skb, enum skb_drop_reason *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bee7e0)
Location: net/core/sock.c:511
Inline: False
Direct callers:
  - net/ipv4/ping.c:__ping_queue_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff81bee7e0-ffffffff81bee84b: sock_queue_rcv_skb_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_queue_rcv_skb_reason(struct sock *sk, struct sk_buff *skb, enum skb_drop_reason *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9e2b0)
Location: net/core/sock.c:511
Inline: False
Direct callers:
  - net/ipv4/ping.c:__ping_queue_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff81d9e2b0-ffffffff81d9e314: sock_queue_rcv_skb_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_queue_rcv_skb_reason(struct sock *sk, struct sk_buff *skb, enum skb_drop_reason *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0cb30)
Location: net/core/sock.c:517
Inline: False
Direct callers:
  - net/ipv4/ping.c:__ping_queue_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff81e0cb30-ffffffff81e0cb94: sock_queue_rcv_skb_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_queue_rcv_skb_reason(struct sock *sk, struct sk_buff *skb, enum skb_drop_reason *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec94b0)
Location: net/core/sock.c:514
Inline: False
Direct callers:
  - net/ipv4/ping.c:__ping_queue_rcv_skb
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
```
**Symbols:**

```
ffffffff81ec94b0-ffffffff81ec9514: sock_queue_rcv_skb_reason (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
