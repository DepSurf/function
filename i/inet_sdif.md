# Function: <code>inet_sdif</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818bc041)
Location: include/net/ip.h:83
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff818c4320)
Location: include/net/ip.h:83
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff818c9c11)
Location: include/net/ip.h:83
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
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
In net/ipv4/tcp_ipv4.c (ffffffff81911a2b)
Location: include/net/ip.h:86
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81919fb6)
Location: include/net/ip.h:86
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8191fcdd)
Location: include/net/ip.h:86
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp4_lib_lookup_skb
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
In net/core/filter.c (ffffffff818d8e0e)
Location: include/net/ip.h:100
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_sk_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8194020b)
Location: include/net/ip.h:100
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81948823)
Location: include/net/ip.h:100
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff8194e94d)
Location: include/net/ip.h:100
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
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
In net/core/filter.c (ffffffff81926e15)
Location: include/net/ip.h:100
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a472a)
Location: include/net/ip.h:100
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff819acec7)
Location: include/net/ip.h:100
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819b312d)
Location: include/net/ip.h:100
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
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
In net/core/filter.c (ffffffff819594d5)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db42a)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff819e3b97)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819e9ead)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
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
In net/core/filter.c (ffffffff81a2e35a)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac84bb)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81ad1433)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ad7a8b)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
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
In net/core/filter.c (ffffffff81a2f8c0)
Location: include/net/ip.h:102
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad445b)
Location: include/net/ip.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81add4b3)
Location: include/net/ip.h:102
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ae40db)
Location: include/net/ip.h:102
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5b23)
Location: include/net/ip.h:102
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
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
In net/core/filter.c (ffffffff81a169a2)
Location: include/net/ip.h:103
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf528)
Location: include/net/ip.h:103
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81ac83a6)
Location: include/net/ip.h:103
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81acf2cb)
Location: include/net/ip.h:103
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0e13)
Location: include/net/ip.h:103
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
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
In net/core/filter.c (ffffffff81ac7fa2)
Location: include/net/ip.h:103
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d073)
Location: include/net/ip.h:103
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81b86c16)
Location: include/net/ip.h:103
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81b8dceb)
Location: include/net/ip.h:103
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f830)
Location: include/net/ip.h:103
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/ping.c (ffffffff81bb067e)
Location: include/net/ip.h:103
Inline: True
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
In net/core/filter.c (ffffffff81c45618)
Location: include/net/ip.h:105
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0cfc4)
Location: include/net/ip.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81d17847)
Location: include/net/ip.h:105
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81d1ee1b)
Location: include/net/ip.h:105
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81d20b2c)
Location: include/net/ip.h:105
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/ping.c (ffffffff81d43b81)
Location: include/net/ip.h:105
Inline: True
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
In net/core/filter.c (ffffffff81df9788)
Location: include/net/ip.h:105
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2a43)
Location: include/net/ip.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81ede107)
Location: include/net/ip.h:105
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81ee5f2b)
Location: include/net/ip.h:105
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7db3)
Location: include/net/ip.h:105
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/ping.c (ffffffff81f0cd09)
Location: include/net/ip.h:105
Inline: True
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
In net/core/filter.c (ffffffff81e6b10d)
Location: include/net/ip.h:107
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31723)
Location: include/net/ip.h:107
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81f3d407)
Location: include/net/ip.h:107
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff81f4572b)
Location: include/net/ip.h:107
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/ping.c (ffffffff81f6c983)
Location: include/net/ip.h:107
Inline: True
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
In net/core/filter.c (ffffffff81f2a09d)
Location: include/net/ip.h:108
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7914)
Location: include/net/ip.h:108
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff82003567)
Location: include/net/ip.h:108
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/udp.c (ffffffff8200b87b)
Location: include/net/ip.h:108
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_mcast_deliver
  - net/ipv4/udp.c:__udp4_lib_err
```
```
In net/ipv4/ping.c (ffffffff820330d3)
Location: include/net/ip.h:108
Inline: True
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
In net/core/filter.c (ffff800010bfa9b8)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e800)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffff800010c98578)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffff800010c9f6c4)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d144b0)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (c0d9d760)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (c0da63c0)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c0dac9dc)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce2de0)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d21c)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (c000000000da9c40)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (c000000000db2188)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077c604)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eeb24)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffe0007f67ae)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffe0007fc1fa)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
</details>
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
In net/core/filter.c (ffffffff818f94a5)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b29a)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff81983a07)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff81989d1d)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b32d5)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934d5a)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff8193d4c7)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819437dd)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194a4d5)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5a6a)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff819ee1d7)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819f44ed)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
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
In net/core/filter.c (ffffffff8196bde5)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef72a)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/raw.c (ffffffff819f8237)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/udp.c (ffffffff819fe6ad)
Location: include/net/ip.h:101
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_err
  - net/ipv4/udp.c:udp4_lib_lookup_skb
```
</details>
</li>
</ul>

## Differences
