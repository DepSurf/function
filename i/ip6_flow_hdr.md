# Function: <code>ip6_flow_hdr</code>

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
In net/ipv6/ip6_output.c (ffffffff817c4d7a)
Location: include/net/ipv6.h:799
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ndisc.c (ffffffff817dea8e)
Location: include/net/ipv6.h:799
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff817ea145)
Location: include/net/ipv6.h:799
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_newpack
  - net/ipv6/mcast.c:igmp6_send
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
In net/ipv6/ip6_output.c (ffffffff8183519e)
Location: include/net/ipv6.h:831
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff8184c9cb)
Location: include/net/ipv6.h:831
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff8185823b)
Location: include/net/ipv6.h:831
Inline: True
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
In net/ipv6/ip6_output.c (ffffffff81866cdc)
Location: include/net/ipv6.h:836
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff8187e88c)
Location: include/net/ipv6.h:836
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff8188a63b)
Location: include/net/ipv6.h:836
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a4216)
Location: include/net/ipv6.h:836
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/ipv6/ip6_output.c (ffffffff8188b38b)
Location: include/net/ipv6.h:837
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff818a4924)
Location: include/net/ipv6.h:837
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff818b06ad)
Location: include/net/ipv6.h:837
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca861)
Location: include/net/ipv6.h:837
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/ipv6/ip6_output.c (ffffffff8190c5bb)
Location: include/net/ipv6.h:878
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff819272e8)
Location: include/net/ipv6.h:878
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff8193334d)
Location: include/net/ipv6.h:878
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194df68)
Location: include/net/ipv6.h:878
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff81963a65)
Location: include/net/ipv6.h:877
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff8197f6cb)
Location: include/net/ipv6.h:877
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff8198befb)
Location: include/net/ipv6.h:877
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a74c8)
Location: include/net/ipv6.h:877
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff81998a07)
Location: include/net/ipv6.h:876
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff819b5cc2)
Location: include/net/ipv6.h:876
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff819c280b)
Location: include/net/ipv6.h:876
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff819cf1ab)
Location: include/net/ipv6.h:876
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de01f)
Location: include/net/ipv6.h:876
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff81a04873)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81a247a1)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff81a314fb)
Location: include/net/ipv6.h:934
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a3dee0)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4cb8e)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff81a3b466)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81a5b221)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff81a6804b)
Location: include/net/ipv6.h:934
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a74b50)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8375e)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff81b30a25)
Location: include/net/ipv6.h:938
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81b53e21)
Location: include/net/ipv6.h:938
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff81b6041b)
Location: include/net/ipv6.h:938
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b6edaa)
Location: include/net/ipv6.h:938
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e553)
Location: include/net/ipv6.h:938
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff81b3f655)
Location: include/net/ipv6.h:938
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81b62416)
Location: include/net/ipv6.h:938
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff81b6eb8b)
Location: include/net/ipv6.h:938
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b7d8da)
Location: include/net/ipv6.h:938
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d56a)
Location: include/net/ipv6.h:938
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff81b2d4f3)
Location: include/net/ipv6.h:939
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81b50766)
Location: include/net/ipv6.h:939
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff81b5cf9b)
Location: include/net/ipv6.h:939
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81b6c4b5)
Location: include/net/ipv6.h:939
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c41a)
Location: include/net/ipv6.h:939
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff81bf36a2)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81c17b0e)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff81c249f3)
Location: include/net/ipv6.h:950
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81c34376)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c4731a)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff81d8c258)
Location: include/net/ipv6.h:1004
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81db38ed)
Location: include/net/ipv6.h:1004
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff81dc1c73)
Location: include/net/ipv6.h:1004
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81dd1c6b)
Location: include/net/ipv6.h:1004
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6689)
Location: include/net/ipv6.h:1004
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff81f5a218)
Location: include/net/ipv6.h:1037
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81f8328d)
Location: include/net/ipv6.h:1037
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff81f925c3)
Location: include/net/ipv6.h:1037
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81fa30ab)
Location: include/net/ipv6.h:1037
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9386)
Location: include/net/ipv6.h:1037
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff81fb9ecb)
Location: include/net/ipv6.h:1034
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81fe358f)
Location: include/net/ipv6.h:1034
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff81ff2f2f)
Location: include/net/ipv6.h:1034
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff82003964)
Location: include/net/ipv6.h:1034
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019ae6)
Location: include/net/ipv6.h:1034
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff8208745c)
Location: include/net/ipv6.h:1035
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff820b14ab)
Location: include/net/ipv6.h:1035
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff820c0bdf)
Location: include/net/ipv6.h:1035
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff820d2710)
Location: include/net/ipv6.h:1035
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8ab6)
Location: include/net/ipv6.h:1035
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffff800010cfc580)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffff800010d20a2c)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffff800010d2ff88)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffff800010d3d56c)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f518)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (c0e03988)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (c0e250c0)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (c0e32744)
Location: include/net/ipv6.h:934
Inline: True
```
```
In net/ipv6/datagram.c (c0e40778)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (c0e50264)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (c000000000e24070)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (c000000000e4ee84)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (c000000000e60bb8)
Location: include/net/ipv6.h:934
Inline: True
```
```
In net/ipv6/datagram.c (c000000000e71868)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86704)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffe000846e18)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffe000862a78)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffe00086f6fc)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_newpack
```
```
In net/ipv6/datagram.c (ffffffe000879cf4)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887a82)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff819daaf6)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff819fa8b1)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff81a076db)
Location: include/net/ipv6.h:934
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a141e0)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22dee)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff819978b6)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff819b7671)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff819c449b)
Location: include/net/ipv6.h:934
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff819d0fa0)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfbae)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/ip6_udp_tunnel.c (ffffffff819e5ac8)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ip6_udp_tunnel.c:udp_tunnel6_xmit_skb
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
In net/ipv6/ip6_output.c (ffffffff81a45576)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81a65331)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff81a7215b)
Location: include/net/ipv6.h:934
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a7ec60)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d86e)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/ipv6/ip6_output.c (ffffffff81a51246)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/ndisc.c (ffffffff81a7189e)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/mcast.c (ffffffff81a7e78b)
Location: include/net/ipv6.h:934
Inline: True
```
```
In net/ipv6/datagram.c (ffffffff81a8b520)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_local_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a568)
Location: include/net/ipv6.h:934
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
</ul>

## Differences
