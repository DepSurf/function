# Function: <code>tcp_in_initial_slowstart</code>

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
In net/ipv4/tcp_input.c (0)
Location: include/net/tcp.h:1009
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/net/tcp.h:1009
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177b46c)
Location: include/net/tcp.h:1009
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffffffff8178201c)
Location: include/net/tcp.h:1009
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817ef4da)
Location: include/net/tcp.h:1009
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_input.c (0)
Location: include/net/tcp.h:1028
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/net/tcp.h:1028
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817e8cdc)
Location: include/net/tcp.h:1028
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ef4f2)
Location: include/net/tcp.h:1028
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185e0c2)
Location: include/net/tcp.h:1028
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_input.c (0)
Location: include/net/tcp.h:1083
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/net/tcp.h:1083
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81818ec9)
Location: include/net/tcp.h:1083
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181fd42)
Location: include/net/tcp.h:1083
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818901ff)
Location: include/net/tcp.h:1083
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_timer.c (0)
Location: include/net/tcp.h:1118
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183966b)
Location: include/net/tcp.h:1118
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffffffff818404b3)
Location: include/net/tcp.h:1118
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b67c1)
Location: include/net/tcp.h:1118
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_timer.c (0)
Location: include/net/tcp.h:1109
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b8dfb)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bfc45)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819395f1)
Location: include/net/tcp.h:1109
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_timer.c (ffffffff8190d452)
Location: include/net/tcp.h:1126
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190e211)
Location: include/net/tcp.h:1126
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915806)
Location: include/net/tcp.h:1126
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819918bb)
Location: include/net/tcp.h:1126
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_timer.c (ffffffff8193b838)
Location: include/net/tcp.h:1166
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193c601)
Location: include/net/tcp.h:1166
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffffffff81943fb6)
Location: include/net/tcp.h:1166
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c80fb)
Location: include/net/tcp.h:1166
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_timer.c (ffffffff8199fbf3)
Location: include/net/tcp.h:1168
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a0a42)
Location: include/net/tcp.h:1168
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a859f)
Location: include/net/tcp.h:1168
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a36b8d)
Location: include/net/tcp.h:1168
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_timer.c (ffffffff819d67ca)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d7610)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df26f)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6d73f)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_timer.c (ffffffff81ac3403)
Location: include/net/tcp.h:1209
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac45cd)
Location: include/net/tcp.h:1209
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acc7f2)
Location: include/net/tcp.h:1209
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66d79)
Location: include/net/tcp.h:1209
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp_timer.c (ffffffff81acee78)
Location: include/net/tcp.h:1214
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81acff0d)
Location: include/net/tcp.h:1214
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad87c2)
Location: include/net/tcp.h:1214
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b752d9)
Location: include/net/tcp.h:1214
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp_timer.c (ffffffff81ab9fe1)
Location: include/net/tcp.h:1206
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abaf6d)
Location: include/net/tcp.h:1206
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac36cf)
Location: include/net/tcp.h:1206
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b63b89)
Location: include/net/tcp.h:1206
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp_timer.c (ffffffff81b77420)
Location: include/net/tcp.h:1199
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b782bd)
Location: include/net/tcp.h:1199
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b81bdf)
Location: include/net/tcp.h:1199
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2b649)
Location: include/net/tcp.h:1199
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp_timer.c (ffffffff81d06d37)
Location: include/net/tcp.h:1228
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d07f51)
Location: include/net/tcp.h:1228
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d1204c)
Location: include/net/tcp.h:1228
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc8bc6)
Location: include/net/tcp.h:1228
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp_timer.c (ffffffff81ecbf99)
Location: include/net/tcp.h:1241
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecca11)
Location: include/net/tcp.h:1241
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed7e2c)
Location: include/net/tcp.h:1241
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f998c6)
Location: include/net/tcp.h:1241
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp_timer.c (ffffffff81f2abbb)
Location: include/net/tcp.h:1239
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2b6f1)
Location: include/net/tcp.h:1239
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f36ecb)
Location: include/net/tcp.h:1239
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffa296)
Location: include/net/tcp.h:1239
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp_timer.c (ffffffff81fef7da)
Location: include/net/tcp.h:1276
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff0421)
Location: include/net/tcp.h:1276
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffcfbb)
Location: include/net/tcp.h:1276
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c7f06)
Location: include/net/tcp.h:1276
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp_timer.c (ffff800010c896d0)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8a580)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92b74)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d36100)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_timer.c (c0d98784)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c0d9a6d8)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (c0da1554)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (c0e38fdc)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_timer.c (c000000000d96a14)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d98cfc)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (c000000000da2d00)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (c000000000e68504)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_timer.c (ffffffe0007ea5a4)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb906)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f2370)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087378a)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_timer.c (ffffffff8197663a)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81977480)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197f0df)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0cdcf)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_timer.c (ffffffff819300fa)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81930f40)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938b9f)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c9b8f)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_timer.c (ffffffff819e0e0a)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e1c50)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e98af)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7784f)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp_timer.c (ffffffff819eaaca)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb9a0)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f365a)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_update_metrics
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a83fbf)
Location: include/net/tcp.h:1189
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
</ul>

## Differences
