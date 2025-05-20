# Function: <code>skb_set_inner_protocol</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff818319b8)
Location: include/linux/skbuff.h:2056
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a411a)
Location: include/linux/skbuff.h:2056
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6818)
Location: include/linux/skbuff.h:2056
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/ipv4/af_inet.c (ffffffff81852f44)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca715)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd272)
Location: include/linux/skbuff.h:2095
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/ipv4/af_inet.c (ffffffff818d2d88)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e56e)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81952056)
Location: include/linux/skbuff.h:2182
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/ipv4/af_inet.c (ffffffff81929341)
Location: include/linux/skbuff.h:2193
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a77a6)
Location: include/linux/skbuff.h:2193
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab5cf)
Location: include/linux/skbuff.h:2193
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/ipv4/af_inet.c (ffffffff81958f7e)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de313)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff819e208f)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff818ea418)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (ffffffff81928121)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/lwt_bpf.c (ffffffff8194364e)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffff819bda4e)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4ce73)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81a50d1f)
Location: include/linux/skbuff.h:2359
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff8191c594)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (ffffffff8195a751)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/lwt_bpf.c (ffffffff8197862a)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffff819f465a)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83a43)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81a8793b)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff819f06f2)
Location: include/linux/skbuff.h:2396
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (ffffffff81a2c301)
Location: include/linux/skbuff.h:2396
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/lwt_bpf.c (ffffffff81a4d533)
Location: include/linux/skbuff.h:2396
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffff81ae236a)
Location: include/linux/skbuff.h:2396
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e823)
Location: include/linux/skbuff.h:2396
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81b82dfe)
Location: include/linux/skbuff.h:2396
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff819f0447)
Location: include/linux/skbuff.h:2417
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (ffffffff81a2d881)
Location: include/linux/skbuff.h:2417
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/lwt_bpf.c (ffffffff81a531f5)
Location: include/linux/skbuff.h:2417
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffff81aef1f0)
Location: include/linux/skbuff.h:2417
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d833)
Location: include/linux/skbuff.h:2417
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92484)
Location: include/linux/skbuff.h:2417
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff819d4d8b)
Location: include/linux/skbuff.h:2433
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (ffffffff81a150f3)
Location: include/linux/skbuff.h:2433
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/lwt_bpf.c (ffffffff81a38a23)
Location: include/linux/skbuff.h:2433
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffff81ada950)
Location: include/linux/skbuff.h:2433
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c6e3)
Location: include/linux/skbuff.h:2433
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81b815d4)
Location: include/linux/skbuff.h:2433
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff81a84b1b)
Location: include/linux/skbuff.h:2462
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (ffffffff81ac66a3)
Location: include/linux/skbuff.h:2462
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/lwt_bpf.c (ffffffff81aee903)
Location: include/linux/skbuff.h:2462
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffff81b99b90)
Location: include/linux/skbuff.h:2462
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c476b7)
Location: include/linux/skbuff.h:2462
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4d5f4)
Location: include/linux/skbuff.h:2462
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff81bfaa24)
Location: include/linux/skbuff.h:2830
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (0)
Location: include/linux/skbuff.h:2830
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/lwt_bpf.c (ffffffff81c7187f)
Location: include/linux/skbuff.h:2830
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffff81d2bb2a)
Location: include/linux/skbuff.h:2830
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6a93)
Location: include/linux/skbuff.h:2830
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81dedb9f)
Location: include/linux/skbuff.h:2830
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff81da98b4)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (0)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/lwt_bpf.c (ffffffff81e2996f)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffff81ef373a)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb98bb)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc1abf)
Location: include/linux/skbuff.h:2722
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff81e183b4)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (0)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/lwt_bpf.c (ffffffff81e9efaf)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffff81f531c5)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019f4b)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff82022a3f)
Location: include/linux/skbuff.h:2776
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff81ed5854)
Location: include/linux/skbuff.h:2783
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (0)
Location: include/linux/skbuff.h:2783
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_net_grow
```
```
In net/core/lwt_bpf.c (ffffffff81f6171f)
Location: include/linux/skbuff.h:2783
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffff82019575)
Location: include/linux/skbuff.h:2783
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8f1b)
Location: include/linux/skbuff.h:2783
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff820f1b5f)
Location: include/linux/skbuff.h:2783
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffff800010bb6af4)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (ffff800010bfbe58)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/lwt_bpf.c (ffff800010c1f2f0)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffff800010caa000)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f738)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffff800010d5452c)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (c0cd39d4)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (c0d16e28)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/lwt_bpf.c (c0d36e78)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (c0db68bc)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (c0e50494)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (c0e54b20)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (c000000000c8e4d8)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (c000000000ce7348)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/lwt_bpf.c (c000000000d11174)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (c000000000dbf870)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86e40)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (c000000000e8cf14)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffe000746790)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (ffffffe00077e8ce)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/lwt_bpf.c (ffffffe000798a36)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffe000804b36)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe00088800a)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffe00088bedc)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff818bc594)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (ffffffff818fa721)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/lwt_bpf.c (ffffffff8191849a)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffff819943fa)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a230d3)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81a26fcb)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In drivers/net/vxlan.c (ffffffff8176beb2)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_build_skb
```
```
In net/core/skbuff.c (ffffffff818764d4)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (ffffffff818b4551)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/lwt_bpf.c (ffffffff818d224a)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffff8194deba)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfe93)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff819e3d8b)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff8190d594)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (ffffffff8194b751)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/lwt_bpf.c (ffffffff8196962a)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffff819fec9a)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8db53)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81a92b7b)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
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
In net/core/skbuff.c (ffffffff8192e6c4)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_mpls_push
```
```
In net/core/filter.c (ffffffff8196d061)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/core/lwt_bpf.c (ffffffff8198ba0a)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/af_inet.c (ffffffff81a08d39)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_complete
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a853)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9ec8a)
Location: include/linux/skbuff.h:2373
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_complete
```
</details>
</li>
</ul>

## Differences
