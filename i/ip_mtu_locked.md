# Function: <code>ip_mtu_locked</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e3a35)
Location: include/net/ip.h:341
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff818ea097)
Location: include/net/ip.h:341
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff818eea52)
Location: include/net/ip.h:341
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190f888)
Location: include/net/ip.h:341
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff819498ee)
Location: include/net/ip.h:341
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/route.c (ffffffff819108f3)
Location: include/net/ip.h:365
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819174cc)
Location: include/net/ip.h:365
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8191c1e9)
Location: include/net/ip.h:365
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193dca8)
Location: include/net/ip.h:365
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bacf)
Location: include/net/ip.h:365
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b5ab)
Location: include/net/ip.h:365
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/route.c (ffffffff81972b43)
Location: include/net/ip.h:403
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81979416)
Location: include/net/ip.h:403
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8197e515)
Location: include/net/ip.h:403
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a20c3)
Location: include/net/ip.h:403
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d27f3)
Location: include/net/ip.h:403
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4ae1)
Location: include/net/ip.h:403
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/route.c (ffffffff819a94b3)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819afc79)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819b4ec1)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d7af3)
Location: include/net/ip.h:404
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a091f3)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1bb01)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/route.c (ffffffff81a931eb)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81a99c56)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a9f0be)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac51b3)
Location: include/net/ip.h:404
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8c85)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fa4e)
Location: include/net/ip.h:404
Inline: True
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
In net/ipv4/route.c (ffffffff81a9d065)
Location: include/net/ip.h:401
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3ba6)
Location: include/net/ip.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81aa8ffe)
Location: include/net/ip.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0b43)
Location: include/net/ip.h:401
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05a55)
Location: include/net/ip.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e32a)
Location: include/net/ip.h:401
Inline: True
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
In net/ipv4/route.c (ffffffff81a86328)
Location: include/net/ip.h:402
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_mtu
  - net/ipv4/route.c:ipv4_mtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81a8eb7e)
Location: include/net/ip.h:402
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a94174)
Location: include/net/ip.h:402
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abd06c)
Location: include/net/ip.h:402
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af12d8)
Location: include/net/ip.h:402
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1bd77)
Location: include/net/ip.h:402
Inline: True
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
In net/ipv4/route.c (ffffffff81b42658)
Location: include/net/ip.h:402
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81b49d9b)
Location: include/net/ip.h:402
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81b4f5dd)
Location: include/net/ip.h:402
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b79f0b)
Location: include/net/ip.h:402
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1511)
Location: include/net/ip.h:402
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81be00d0)
Location: include/net/ip.h:402
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
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
In net/ipv4/route.c (ffffffff81ccf5b2)
Location: include/net/ip.h:408
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81cd72d2)
Location: include/net/ip.h:408
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81cdcf78)
Location: include/net/ip.h:408
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0a1dd)
Location: include/net/ip.h:408
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d44bca)
Location: include/net/ip.h:408
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81d774d6)
Location: include/net/ip.h:408
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
In net/ipv4/route.c (ffffffff81e8f7a2)
Location: include/net/ip.h:408
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81e978f3)
Location: include/net/ip.h:408
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81e9d9e8)
Location: include/net/ip.h:408
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecf63d)
Location: include/net/ip.h:408
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0de6a)
Location: include/net/ip.h:408
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43d66)
Location: include/net/ip.h:408
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
In net/ipv4/route.c (ffffffff81eedea2)
Location: include/net/ip.h:417
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6133)
Location: include/net/ip.h:417
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81efc15c)
Location: include/net/ip.h:417
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2e2f9)
Location: include/net/ip.h:417
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6db1a)
Location: include/net/ip.h:417
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3544)
Location: include/net/ip.h:417
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
In net/ipv4/route.c (ffffffff81fb1fff)
Location: include/net/ip.h:424
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81fba0cf)
Location: include/net/ip.h:424
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81fc00bc)
Location: include/net/ip.h:424
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff3158)
Location: include/net/ip.h:424
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8203426a)
Location: include/net/ip.h:424
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/xfrm/xfrm_output.c (ffffffff820704c4)
Location: include/net/ip.h:424
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
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
In net/ipv4/route.c (ffff800010c58eb8)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffff800010c60328)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffff800010c6561c)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8a9f4)
Location: include/net/ip.h:404
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc2510)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7d9c)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/route.c (c0d68c08)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (c0d6fe00)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c0d75288)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (c0d9bacc)
Location: include/net/ip.h:404
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (c0dcddfc)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (c0de1864)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/route.c (c000000000d5ad08)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (c000000000d63244)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c000000000d69a3c)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (c000000000d99220)
Location: include/net/ip.h:404
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dddc38)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (c000000000df7e30)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/route.c (ffffffe0007c2e8e)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffe0007c85c0)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffe0007cce32)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ebbcc)
Location: include/net/ip.h:404
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe00081797e)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffe000828376)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/route.c (ffffffff81949323)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff8194fae9)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81954d31)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81977963)
Location: include/net/ip.h:404
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8f93)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb191)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/route.c (ffffffff81902e13)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819095d9)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8190e821)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81931423)
Location: include/net/ip.h:404
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962a53)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff81977f81)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/route.c (ffffffff819b3af3)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819ba2b9)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819bf501)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e2133)
Location: include/net/ip.h:404
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13833)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25c11)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/route.c (ffffffff819bd1c3)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff819c3ba9)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819c8e81)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
  - net/ipv4/ip_output.c:ip_build_and_send_pkt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ebe83)
Location: include/net/ip.h:404
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e203)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a310b1)
Location: include/net/ip.h:404
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
</details>
</li>
</ul>

## Differences
