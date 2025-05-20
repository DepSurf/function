# Function: <code>l3mdev_fib_oif</code>

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
In net/ipv4/xfrm4_policy.c (ffffffff817af6e9)
Location: include/net/l3mdev.h:63
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv6/ip6_output.c (ffffffff817c4725)
Location: include/net/l3mdev.h:63
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
```
In net/ipv6/route.c (ffffffff817d703a)
Location: include/net/l3mdev.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff817deb92)
Location: include/net/l3mdev.h:63
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
```
In net/ipv6/icmp.c (ffffffff817e8112)
Location: include/net/l3mdev.h:63
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fc2ee)
Location: include/net/l3mdev.h:63
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
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
In net/ipv4/xfrm4_policy.c (ffffffff8181c624)
Location: include/net/l3mdev.h:116
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:_decode_session4
```
```
In net/ipv6/ip6_output.c (ffffffff81831895)
Location: include/net/l3mdev.h:116
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_flow
```
```
In net/ipv6/route.c (ffffffff8184574a)
Location: include/net/l3mdev.h:116
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/ndisc.c (ffffffff8184f5aa)
Location: include/net/l3mdev.h:116
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186bbed)
Location: include/net/l3mdev.h:116
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:_decode_session6
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
