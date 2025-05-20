# Function: <code>skb_reset_inner_headers</code>

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
In net/ipv4/udp_offload.c (ffffffff8178afcc)
Location: include/linux/skbuff.h:1928
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81794b7b)
Location: include/linux/skbuff.h:1928
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a4a21)
Location: include/linux/skbuff.h:1928
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/ipv4/gre_offload.c (ffffffff817a533e)
Location: include/linux/skbuff.h:1928
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/ip6_offload.c (ffffffff818010f4)
Location: include/linux/skbuff.h:1928
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff817f8aae)
Location: include/linux/skbuff.h:2053
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff818024f1)
Location: include/linux/skbuff.h:2053
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81812720)
Location: include/linux/skbuff.h:2053
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff81812cc0)
Location: include/linux/skbuff.h:2053
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/ip6_offload.c (ffffffff81872944)
Location: include/linux/skbuff.h:2053
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff8182998a)
Location: include/linux/skbuff.h:2070
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8183349c)
Location: include/linux/skbuff.h:2070
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843c20)
Location: include/linux/skbuff.h:2070
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff818441d2)
Location: include/linux/skbuff.h:2070
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a40a7)
Location: include/linux/skbuff.h:2070
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6f68)
Location: include/linux/skbuff.h:2070
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff8184a813)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81854818)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818654b0)
Location: include/linux/skbuff.h:2109
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff818659e2)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca6a2)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd9c3)
Location: include/linux/skbuff.h:2109
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/ipv4/udp_offload.c (ffffffff818ca495)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff818d46bc)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e5600)
Location: include/linux/skbuff.h:2196
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff818e5b2e)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff8194f5dd)
Location: include/linux/skbuff.h:2196
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff819527c5)
Location: include/linux/skbuff.h:2196
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff818b2245)
Location: include/linux/skbuff.h:2207
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/ipv4/udp_offload.c (ffffffff819207cc)
Location: include/linux/skbuff.h:2207
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8192ad8d)
Location: include/linux/skbuff.h:2207
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193beb0)
Location: include/linux/skbuff.h:2207
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff8193c338)
Location: include/linux/skbuff.h:2207
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff819a91c6)
Location: include/linux/skbuff.h:2207
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff819abd99)
Location: include/linux/skbuff.h:2207
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff818d6daf)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/ipv4/udp_offload.c (ffffffff8194f603)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8195a50b)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bbd0)
Location: include/linux/skbuff.h:2285
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff8196c039)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff819dfab6)
Location: include/linux/skbuff.h:2285
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff819e294d)
Location: include/linux/skbuff.h:2285
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff8192462e)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffff81943634)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffff819b3e39)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819bf092)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d291d)
Location: include/linux/skbuff.h:2373
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff819d2d89)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e56b)
Location: include/linux/skbuff.h:2373
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a515eb)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff8195693e)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffff8197860a)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffff819eab69)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff819f5cd2)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a0948d)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff81a098f8)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff81a851db)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a8820b)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff81a2f5b0)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffff81a4d519)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81ad8775)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ae41c2)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8dad)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/ipv4/gre_offload.c (ffffffff81afa068)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff81b804f2)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81b836db)
Location: include/linux/skbuff.h:2410
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff81a318c0)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffff81a531db)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4ca8)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81af10f2)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05b7d)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/ipv4/gre_offload.c (ffffffff81b07831)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff81b8fd72)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92d9b)
Location: include/linux/skbuff.h:2431
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff81a18720)
Location: include/linux/skbuff.h:2447
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffff81a38a09)
Location: include/linux/skbuff.h:2447
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81acfec5)
Location: include/linux/skbuff.h:2447
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81adc8b2)
Location: include/linux/skbuff.h:2447
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af13fd)
Location: include/linux/skbuff.h:2447
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/ipv4/gre_offload.c (ffffffff81af2fd9)
Location: include/linux/skbuff.h:2447
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ed63)
Location: include/linux/skbuff.h:2447
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81eec)
Location: include/linux/skbuff.h:2447
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff81ac9c10)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffff81aee8e9)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e8e5)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81b9bc8c)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb190d)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/ipv4/gre_offload.c (ffffffff81bb34e9)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a503)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4df6c)
Location: include/linux/skbuff.h:2476
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff81c46749)
Location: include/linux/skbuff.h:2844
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffff81c71857)
Location: include/linux/skbuff.h:2844
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81d20043)
Location: include/linux/skbuff.h:2844
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81d2da53)
Location: include/linux/skbuff.h:2844
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44fad)
Location: include/linux/skbuff.h:2844
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/ipv4/gre_offload.c (ffffffff81d46d0c)
Location: include/linux/skbuff.h:2844
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff81de9e00)
Location: include/linux/skbuff.h:2844
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee674)
Location: include/linux/skbuff.h:2844
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff81dfac49)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffff81e29947)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7240)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81ef5953)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e43d)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/ipv4/gre_offload.c (ffffffff81f1055c)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff81fbd560)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2294)
Location: include/linux/skbuff.h:2736
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff81e6be49)
Location: include/linux/skbuff.h:2790
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffff81e9ef87)
Location: include/linux/skbuff.h:2790
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81f46ae2)
Location: include/linux/skbuff.h:2790
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81f55306)
Location: include/linux/skbuff.h:2790
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6e0ed)
Location: include/linux/skbuff.h:2790
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/ipv4/gre_offload.c (ffffffff81f70248)
Location: include/linux/skbuff.h:2790
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff8201e300)
Location: include/linux/skbuff.h:2790
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff82023214)
Location: include/linux/skbuff.h:2790
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff81f2b739)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffff81f616f7)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffff8200cc22)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8201b576)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820347fd)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_handle_offloads
```
```
In net/ipv4/gre_offload.c (ffffffff82036978)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff820ed2e0)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
```
```
In net/ipv6/ip6_offload.c (ffffffff820f225f)
Location: include/linux/skbuff.h:2797
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffff800010bf822c)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffff800010c1f2bc)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffff800010ca0638)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffff800010cab918)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc2814)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv4/gre_offload.c (ffff800010cc2cdc)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffff800010d51358)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffff800010d54d88)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (c0d11cd0)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (c0d36e68)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (c0dad9b0)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c0db8818)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (c0dcdf60)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv4/gre_offload.c (c0dce494)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (c0e51e20)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
```
```
In net/ipv6/ip6_offload.c (c0e55394)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (c000000000cdeca0)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (c000000000d1115c)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (c000000000db2e40)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (c000000000dc22f4)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dde030)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv4/gre_offload.c (c000000000ddeb48)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (c000000000e89264)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv6/ip6_offload.c (c000000000e8d9bc)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffe000779ef8)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffe000798a2e)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffe0007fcd14)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffe000806588)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817bd8)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffe00081815e)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffe00088959e)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c686)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff818f690e)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffff8191847a)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffff8198a9d9)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81995a72)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a922d)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff819a9698)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff81a2486b)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a2789b)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff818b073e)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffff818d222a)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffff81944499)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff8194f532)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962ced)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff81963158)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff819e162b)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff819e465b)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff8194793e)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffff8196960a)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffff819f51a9)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81a00312)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13acd)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff81a13f38)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f2eb)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9344b)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
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
In net/core/filter.c (ffffffff8196924e)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/filter.c:bpf_push_seg6_encap
```
```
In net/core/lwt_bpf.c (ffffffff8198b9ea)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/udp_offload.c (ffffffff819ff3a4)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/af_inet.c (ffffffff81a0a362)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gso_segment
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e4ad)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e928)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c06b)
Location: include/linux/skbuff.h:2387
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f59b)
Location: include/linux/skbuff.h:2387
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
</details>
</li>
</ul>

## Differences
