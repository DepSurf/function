# Function: <code>skb_put_zero</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814856f5)
Location: include/linux/skbuff.h:1945
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv6/mcast.c (ffffffff818b1194)
Location: include/linux/skbuff.h:1945
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff818e6b7d)
Location: include/linux/skbuff.h:1945
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff814c1885)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv6/mcast.c (ffffffff819337e4)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff8196bf0d)
Location: include/linux/skbuff.h:2032
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff814f25b5)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff818e71b2)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (ffffffff8198c17b)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819c5995)
Location: include/linux/skbuff.h:2043
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff815062e5)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff81914090)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (ffffffff819c2c02)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819fcf22)
Location: include/linux/skbuff.h:2121
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff81534cb4)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff81976459)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (ffffffff81a31a19)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81a6c1a3)
Location: include/linux/skbuff.h:2209
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff81555ae4)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff819ace69)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (ffffffff81a68569)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aa2b63)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff815de874)
Location: include/linux/skbuff.h:2246
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff81a9242f)
Location: include/linux/skbuff.h:2246
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv6/mcast.c (ffffffff81b61839)
Location: include/linux/skbuff.h:2246
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81b9e663)
Location: include/linux/skbuff.h:2246
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff815fbf14)
Location: include/linux/skbuff.h:2267
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff81a9c2cf)
Location: include/linux/skbuff.h:2267
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv6/mcast.c (ffffffff81b6ffbb)
Location: include/linux/skbuff.h:2267
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81bae063)
Location: include/linux/skbuff.h:2267
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff815deb54)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff81a872be)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv6/mcast.c (ffffffff81b5e280)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81b9d0e3)
Location: include/linux/skbuff.h:2283
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
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
In lib/nlattr.c (ffffffff8164a6d4)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff81b41a7e)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv6/mcast.c (ffffffff81c2572b)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81c6a608)
Location: include/linux/skbuff.h:2312
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
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
In lib/nlattr.c (ffffffff81760df4)
Location: include/linux/skbuff.h:2671
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff81cd387b)
Location: include/linux/skbuff.h:2671
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (ffffffff81dc2ec7)
Location: include/linux/skbuff.h:2671
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81e0dcc8)
Location: include/linux/skbuff.h:2671
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff8188fb54)
Location: include/linux/skbuff.h:2568
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff81e93a94)
Location: include/linux/skbuff.h:2568
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (ffffffff81f93917)
Location: include/linux/skbuff.h:2568
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81fe4028)
Location: include/linux/skbuff.h:2568
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff818d1fc4)
Location: include/linux/skbuff.h:2611
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff81ef21fd)
Location: include/linux/skbuff.h:2611
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (ffffffff81ff4267)
Location: include/linux/skbuff.h:2611
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82060338)
Location: include/linux/skbuff.h:2611
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff81923f94)
Location: include/linux/skbuff.h:2618
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff81fb6362)
Location: include/linux/skbuff.h:2618
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (ffffffff820c11b8)
Location: include/linux/skbuff.h:2618
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff82133258)
Location: include/linux/skbuff.h:2618
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffff800010661fac)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffff800010c5cee8)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (ffff800010d2fff0)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffff800010d74acc)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (c080b030)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (c0d6c660)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (c0e33810)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (c0e711dc)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (c0000000008162b0)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (c000000000d5f590)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (c000000000e6127c)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (c000000000eb3d7c)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffe00048e8da)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffe0007c5c9a)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (ffffffe00086f778)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffe0008a460c)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff8154e0c4)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff8194ccd9)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (ffffffff81a07bf9)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81a41ef3)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff8153e3a4)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In drivers/net/vxlan.c (ffffffff8177384a)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - drivers/net/vxlan.c:neigh_reduce
```
```
In net/ipv4/route.c (ffffffff819067c9)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (ffffffff819c49b9)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff819feae3)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff81549e04)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff819b74a9)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (ffffffff81a72679)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aadda3)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
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
In lib/nlattr.c (ffffffff81563c54)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - lib/nlattr.c:__nla_put_nohdr
  - lib/nlattr.c:nla_reserve_nohdr
```
```
In net/ipv4/route.c (ffffffff819c0d38)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/mcast.c (ffffffff81a7ecfa)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ncsi/ncsi-cmd.c (ffffffff81aba153)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_oem
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_snfc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_egmf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ebf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sma
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ev
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_svf
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sl
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_ae
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_rc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_dc
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_sp
  - net/ncsi/ncsi-cmd.c:ncsi_cmd_handler_default
```
</details>
</li>
</ul>

## Differences
