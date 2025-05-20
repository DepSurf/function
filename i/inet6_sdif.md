# Function: <code>inet6_sdif</code>

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
In net/ipv6/udp.c (ffffffff8192cbf1)
Location: include/linux/ipv6.h:164
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81930206)
Location: include/linux/ipv6.h:164
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b7c1)
Location: include/linux/ipv6.h:164
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/ipv6/udp.c (ffffffff819852fa)
Location: include/linux/ipv6.h:164
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81988e8c)
Location: include/linux/ipv6.h:164
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994a2b)
Location: include/linux/ipv6.h:164
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/filter.c (ffffffff818d8d67)
Location: include/linux/ipv6.h:164
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_sk_lookup
```
```
In net/ipv6/ip6_input.c (ffffffff81999fc8)
Location: include/linux/ipv6.h:164
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819bba7a)
Location: include/linux/ipv6.h:164
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff819bf7ec)
Location: include/linux/ipv6.h:164
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb32b)
Location: include/linux/ipv6.h:164
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/filter.c (ffffffff81926d75)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv6/ip6_input.c (ffffffff81a05f18)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a2a6ba)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a2e48b)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39d6a)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/filter.c (ffffffff81959435)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv6/ip6_input.c (ffffffff81a3ca88)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a6120a)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a64ffb)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a708fa)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/filter.c (ffffffff81a2e2b5)
Location: include/linux/ipv6.h:171
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv6/ip6_input.c (ffffffff81b32128)
Location: include/linux/ipv6.h:171
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b5a65a)
Location: include/linux/ipv6.h:171
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b5d9bc)
Location: include/linux/ipv6.h:171
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a098)
Location: include/linux/ipv6.h:171
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/filter.c (ffffffff81a2f815)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv6/ip6_input.c (ffffffff81b40d48)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b68d5a)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b6c19f)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78b78)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/udp_offload.c (ffffffff81b80947)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
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
In net/core/filter.c (ffffffff81a168f9)
Location: include/linux/ipv6.h:171
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv6/ip6_input.c (ffffffff81b2ec68)
Location: include/linux/ipv6.h:171
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b56dee)
Location: include/linux/ipv6.h:171
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81b5a4da)
Location: include/linux/ipv6.h:171
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b676c8)
Location: include/linux/ipv6.h:171
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/udp_offload.c (ffffffff81b6f566)
Location: include/linux/ipv6.h:171
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
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
In net/core/filter.c (ffffffff81ac7ef9)
Location: include/linux/ipv6.h:176
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/ping.c (ffffffff81bb050f)
Location: include/linux/ipv6.h:176
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4f98)
Location: include/linux/ipv6.h:176
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81c1d00e)
Location: include/linux/ipv6.h:176
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81c21b5a)
Location: include/linux/ipv6.h:176
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f2f8)
Location: include/linux/ipv6.h:176
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/udp_offload.c (ffffffff81c37623)
Location: include/linux/ipv6.h:176
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
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
In net/core/filter.c (ffffffff81c45598)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/ping.c (ffffffff81d43b24)
Location: include/linux/ipv6.h:179
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81d8dde9)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81dbbb5e)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81dbe9c7)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd645)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/udp_offload.c (ffffffff81dd51bd)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
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
In net/core/filter.c (ffffffff81df9708)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/ping.c (ffffffff81f0cb73)
Location: include/linux/ipv6.h:179
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81f5bf59)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81f8bc7e)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81f8eeb7)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e754)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/udp_offload.c (ffffffff81fa68d6)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_receive
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
In net/core/filter.c (ffffffff81e6b132)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/ping.c (ffffffff81f6c7e7)
Location: include/linux/ipv6.h:179
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81fbbd09)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81fec41e)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff81fef6a7)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81fff210)
Location: include/linux/ipv6.h:179
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/filter.c (ffffffff81f2a0c2)
Location: include/linux/ipv6.h:182
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv4/ping.c (ffffffff82032f37)
Location: include/linux/ipv6.h:182
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff82089139)
Location: include/linux/ipv6.h:182
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff820ba02e)
Location: include/linux/ipv6.h:182
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
```
```
In net/ipv6/raw.c (ffffffff820bd277)
Location: include/linux/ipv6.h:182
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cdf20)
Location: include/linux/ipv6.h:182
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/filter.c (ffff800010bfa910)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv6/ip6_input.c (ffff800010cfddd8)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffff800010d24474)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffff800010d2af04)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38dd0)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/filter.c (c0d14400)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv6/ip6_input.c (c0e05840)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (c0e2b2d0)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (c0e2ef04)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (c0e3b980)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/filter.c (c000000000ce2d34)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv6/ip6_input.c (c000000000e2607c)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (c000000000e56cec)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (c000000000e5c1e8)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c29c)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/filter.c (ffffffe00077c60a)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv6/ip6_input.c (ffffffe000848242)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffe000867fae)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_mcast_deliver
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffe00086b496)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008761cc)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/filter.c (ffffffff818f9405)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv6/ip6_input.c (ffffffff819dc118)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a0089a)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a0468b)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ff8a)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/filter.c (ffffffff818b3235)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv6/ip6_input.c (ffffffff81998ed8)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819bd65a)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff819c144b)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ccd4a)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/filter.c (ffffffff8194a435)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv6/ip6_input.c (ffffffff81a46b98)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a6b31a)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a6f10b)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7aa0a)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
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
In net/core/filter.c (ffffffff8196bd45)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
```
```
In net/ipv6/ip6_input.c (ffffffff81a52909)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_mc_input
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a7792a)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/udp.c:udp6_lib_lookup_skb
```
```
In net/ipv6/raw.c (ffffffff81a7b73b)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a8724a)
Location: include/linux/ipv6.h:170
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
</details>
</li>
</ul>

## Differences
