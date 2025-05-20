# Function: <code>tcp_v4_check</code>

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
In net/ipv4/tcp_ipv4.c (ffffffff8177e083)
Location: include/net/tcp.h:1131
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81783165)
Location: include/net/tcp.h:1131
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/tcp_ipv4.c (ffffffff817eb4d3)
Location: include/net/tcp.h:1139
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff817f06fc)
Location: include/net/tcp.h:1139
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/tcp_ipv4.c (ffffffff8181be43)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff8182146c)
Location: include/net/tcp.h:1194
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/tcp_ipv4.c (ffffffff8183c622)
Location: include/net/tcp.h:1229
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff8184214c)
Location: include/net/tcp.h:1229
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/tcp_ipv4.c (ffffffff818bbd52)
Location: include/net/tcp.h:1220
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1a2c)
Location: include/net/tcp.h:1220
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/route.c (ffffffff818e7215)
Location: include/net/tcp.h:1237
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911755)
Location: include/net/tcp.h:1237
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81917702)
Location: include/net/tcp.h:1237
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/route.c (ffffffff8191411d)
Location: include/net/tcp.h:1312
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193ff45)
Location: include/net/tcp.h:1312
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81945e3f)
Location: include/net/tcp.h:1312
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/route.c (ffffffff819764f3)
Location: include/net/tcp.h:1314
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4455)
Location: include/net/tcp.h:1314
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa475)
Location: include/net/tcp.h:1314
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/route.c (ffffffff819acf03)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db075)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1145)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/route.c (ffffffff81a923de)
Location: include/net/tcp.h:1350
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac6005)
Location: include/net/tcp.h:1350
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ace725)
Location: include/net/tcp.h:1350
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/route.c (ffffffff81a9c27e)
Location: include/net/tcp.h:1357
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1c85)
Location: include/net/tcp.h:1357
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ada75a)
Location: include/net/tcp.h:1357
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/core/selftests.c (ffffffff81a36347)
Location: include/net/tcp.h:1349
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81a8728d)
Location: include/net/tcp.h:1349
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abcf45)
Location: include/net/tcp.h:1349
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac57da)
Location: include/net/tcp.h:1349
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/core/selftests.c (ffffffff81aec025)
Location: include/net/tcp.h:1342
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81b41a4d)
Location: include/net/tcp.h:1342
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute_build_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b79dd5)
Location: include/net/tcp.h:1342
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81b83fea)
Location: include/net/tcp.h:1342
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/core/selftests.c (ffffffff81c6e9c7)
Location: include/net/tcp.h:1371
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81cd3914)
Location: include/net/tcp.h:1371
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d09c15)
Location: include/net/tcp.h:1371
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81d147a9)
Location: include/net/tcp.h:1371
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/core/selftests.c (ffffffff81e266f7)
Location: include/net/tcp.h:1387
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81e93b2d)
Location: include/net/tcp.h:1387
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecf2d5)
Location: include/net/tcp.h:1387
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81eda8d9)
Location: include/net/tcp.h:1387
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/core/selftests.c (ffffffff81e9bc98)
Location: include/net/tcp.h:1385
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81ef2330)
Location: include/net/tcp.h:1385
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2df95)
Location: include/net/tcp.h:1385
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81f399b9)
Location: include/net/tcp.h:1385
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/core/selftests.c (ffffffff81f5e3f8)
Location: include/net/tcp.h:1422
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ipv4/route.c (ffffffff81fb6495)
Location: include/net/tcp.h:1422
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2b45)
Location: include/net/tcp.h:1422
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffaa9)
Location: include/net/tcp.h:1422
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/route.c (ffff800010c5cf6c)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e43c)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffff800010c95188)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/route.c (c0d6c6fc)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (c0d998a8)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (c0da38c8)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/route.c (c000000000d5f628)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (c000000000d97a90)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (c000000000da6104)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/route.c (ffffffe0007c5d04)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee81e)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f439e)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/route.c (ffffffff8194cd73)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197aee5)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff81980fb5)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/route.c (ffffffff81906863)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819349a5)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff8193aa75)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/route.c (ffffffff819b7543)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e56b5)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819eb785)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
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
In net/ipv4/route.c (ffffffff819c0dd2)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef365)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5635)
Location: include/net/tcp.h:1335
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
```
</details>
</li>
</ul>

## Differences
