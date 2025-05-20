# Function: <code>ipv6_addr_hash</code>

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
In net/core/flow_dissector.c (ffffffff81711c08)
Location: include/net/ipv6.h:551
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81780f01)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
```
```
In net/ipv6/addrconf.c (ffffffff817c937a)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
```
```
In net/ipv6/reassembly.c (ffffffff817eda26)
Location: include/net/ipv6.h:551
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/reassembly.c:inet6_hash_frag
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
In net/core/flow_dissector.c (ffffffff81779558)
Location: include/net/ipv6.h:583
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ef970)
Location: include/net/ipv6.h:583
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/addrconf.c (ffffffff8183ec1a)
Location: include/net/ipv6.h:583
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
```
```
In net/ipv6/reassembly.c (ffffffff8185c266)
Location: include/net/ipv6.h:583
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/reassembly.c:inet6_hash_frag
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
In net/core/flow_dissector.c (ffffffff817a66a8)
Location: include/net/ipv6.h:583
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81820380)
Location: include/net/ipv6.h:583
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_tw_remember_stamp
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/addrconf.c (ffffffff8187082a)
Location: include/net/ipv6.h:583
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
```
```
In net/ipv6/reassembly.c (ffffffff8188e176)
Location: include/net/ipv6.h:583
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/reassembly.c:inet6_hash_frag
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
In net/core/flow_dissector.c (ffffffff817c48b8)
Location: include/net/ipv6.h:584
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff818407ce)
Location: include/net/ipv6.h:584
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/addrconf.c (ffffffff818955fa)
Location: include/net/ipv6.h:584
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/reassembly.c (ffffffff818b4816)
Location: include/net/ipv6.h:584
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/reassembly.c:inet6_hash_frag
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
In net/core/flow_dissector.c (ffffffff8183e1c8)
Location: include/net/ipv6.h:625
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bff3e)
Location: include/net/ipv6.h:625
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/addrconf.c (ffffffff81916aa6)
Location: include/net/ipv6.h:625
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/reassembly.c (ffffffff8193756e)
Location: include/net/ipv6.h:625
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:inet6_hash_frag
  - net/ipv6/reassembly.c:inet6_hash_frag
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
In net/core/flow_dissector.c (ffffffff81888a28)
Location: include/net/ipv6.h:597
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915ad3)
Location: include/net/ipv6.h:597
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/addrconf.c (ffffffff8196e155)
Location: include/net/ipv6.h:597
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffffffff818a9608)
Location: include/net/ipv6.h:589
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81944283)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffffffff81993ff9)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff819a3cd5)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffffffff818f4dc8)
Location: include/net/ipv6.h:647
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a8853)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffffffff81a0025a)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a10025)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffffffff81926c98)
Location: include/net/ipv6.h:647
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df523)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffffffff81a36e3a)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a46d65)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffffffff819fab20)
Location: include/net/ipv6.h:647
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc62b)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics_req
```
```
In net/ipv6/anycast.c (ffffffff81b2c0d7)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b3dc43)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
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
In net/core/flow_dissector.c (ffffffff819fa730)
Location: include/net/ipv6.h:647
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad85fb)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
  - net/ipv4/tcp_metrics.c:__tcp_get_metrics_req
```
```
In net/ipv6/anycast.c (ffffffff81b3aafc)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b4c7c3)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr_hash
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
In net/core/flow_dissector.c (ffffffff819e0918)
Location: include/net/ipv6.h:648
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac39cb)
Location: include/net/ipv6.h:648
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffffffff81b287dc)
Location: include/net/ipv6.h:648
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b3a496)
Location: include/net/ipv6.h:648
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffffffff81a90c88)
Location: include/net/ipv6.h:651
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b81ef2)
Location: include/net/ipv6.h:651
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffffffff81bee7b1)
Location: include/net/ipv6.h:651
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81c00c36)
Location: include/net/ipv6.h:651
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffffffff81c06d48)
Location: include/net/ipv6.h:705
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d12391)
Location: include/net/ipv6.h:705
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffffffff81d86d25)
Location: include/net/ipv6.h:705
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81d9a8c0)
Location: include/net/ipv6.h:705
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffffffff81db67f8)
Location: include/net/ipv6.h:738
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed8191)
Location: include/net/ipv6.h:738
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffffffff81f548e5)
Location: include/net/ipv6.h:738
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81f69710)
Location: include/net/ipv6.h:738
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffffffff81e26ae8)
Location: include/net/ipv6.h:739
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f37436)
Location: include/net/ipv6.h:739
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffffffff81fb42f5)
Location: include/net/ipv6.h:739
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81fc9780)
Location: include/net/ipv6.h:739
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffffffff81ee4a78)
Location: include/net/ipv6.h:739
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffd506)
Location: include/net/ipv6.h:739
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffffffff82081ba5)
Location: include/net/ipv6.h:739
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff82096f20)
Location: include/net/ipv6.h:739
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_rpl_srh_loop
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:__ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffff800010bc3044)
Location: include/net/ipv6.h:647
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92e3c)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffff800010cf7bb4)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffff800010d0991c)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (c0cde374)
Location: include/net/ipv6.h:647
Inline: True
```
```
In net/ipv4/tcp_metrics.c (c0da05e4)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:__parse_nl_addr
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (c0dfe10c)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (c0e0ff98)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (c000000000c9d100)
Location: include/net/ipv6.h:647
Inline: True
```
```
In net/ipv4/tcp_metrics.c (c000000000da30f8)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (c000000000e1e5b0)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (c000000000e34180)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffffffe00074fc60)
Location: include/net/ipv6.h:647
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f25ba)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffffffe000842e32)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffe000851570)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffffffff818c6c98)
Location: include/net/ipv6.h:647
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197f393)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffffffff819d64ca)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff819e63f5)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffffffff81880bd8)
Location: include/net/ipv6.h:647
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938e53)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffffffff8199328a)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff819a31b5)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffffffff81917c98)
Location: include/net/ipv6.h:647
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9b63)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffffffff81a40f4a)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a50e75)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
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
In net/core/flow_dissector.c (ffffffff81938ea8)
Location: include/net/ipv6.h:647
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f3925)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_peer_is_proven
  - net/ipv4/tcp_metrics.c:tcp_get_metrics
```
```
In net/ipv6/anycast.c (ffffffff81a4cb58)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a5cda5)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_home_addr
  - net/ipv6/addrconf.c:ipv6_get_ifaddr
  - net/ipv6/addrconf.c:ipv6_chk_addr_and_flags
  - net/ipv6/addrconf.c:ipv6_add_addr
```
</details>
</li>
</ul>

## Differences
