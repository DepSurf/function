# Function: <code>__net_timestamp</code>

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
In net/socket.c (ffffffff816fce18)
Location: include/linux/skbuff.h:2959
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff817195fa)
Location: include/linux/skbuff.h:2959
Inline: True
Inline callers:
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/unix/af_unix.c (ffffffff817c1d34)
Location: include/linux/skbuff.h:2959
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff817f32d2)
Location: include/linux/skbuff.h:2959
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff81763b28)
Location: include/linux/skbuff.h:3166
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff817830d9)
Location: include/linux/skbuff.h:3166
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff8182ed4d)
Location: include/linux/skbuff.h:3166
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff818621c9)
Location: include/linux/skbuff.h:3166
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff81790b54)
Location: include/linux/skbuff.h:3218
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff817b0979)
Location: include/linux/skbuff.h:3218
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff818607cd)
Location: include/linux/skbuff.h:3218
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81894029)
Location: include/linux/skbuff.h:3218
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff817ae1ea)
Location: include/linux/skbuff.h:3292
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff817d0ba2)
Location: include/linux/skbuff.h:3292
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff81884f48)
Location: include/linux/skbuff.h:3292
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff818ba751)
Location: include/linux/skbuff.h:3292
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff818262ba)
Location: include/linux/skbuff.h:3413
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff8184adfe)
Location: include/linux/skbuff.h:3413
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff81905e8c)
Location: include/linux/skbuff.h:3413
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff8193d731)
Location: include/linux/skbuff.h:3413
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff8186fb9a)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff81892110)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff8195cba8)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff8199665f)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff81890777)
Location: include/linux/skbuff.h:3502
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff818b80ff)
Location: include/linux/skbuff.h:3502
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff81991be0)
Location: include/linux/skbuff.h:3502
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff819ccf6c)
Location: include/linux/skbuff.h:3502
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff818da600)
Location: include/linux/skbuff.h:3611
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff81904370)
Location: include/linux/skbuff.h:3611
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff819fce37)
Location: include/linux/skbuff.h:3611
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a3ba28)
Location: include/linux/skbuff.h:3611
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff8190c750)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff81935485)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff81a33ac7)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a726a8)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff819df1e5)
Location: include/linux/skbuff.h:3704
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff81a0a190)
Location: include/linux/skbuff.h:3704
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff81b28d60)
Location: include/linux/skbuff.h:3704
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b6c387)
Location: include/linux/skbuff.h:3704
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff819deb85)
Location: include/linux/skbuff.h:3733
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff81a0b735)
Location: include/linux/skbuff.h:3733
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff81b36fd1)
Location: include/linux/skbuff.h:3733
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b7adf7)
Location: include/linux/skbuff.h:3733
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff819c4b45)
Location: include/linux/skbuff.h:3797
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff819f35e8)
Location: include/linux/skbuff.h:3797
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff81b24bb2)
Location: include/linux/skbuff.h:3797
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b69790)
Location: include/linux/skbuff.h:3797
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff81a73fce)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff81aa4f3f)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff81be9bf4)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81c311ba)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ioam6.c (ffffffff81c39298)
Location: include/linux/skbuff.h:3834
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
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
In net/socket.c (ffffffff81be6c5b)
Location: include/linux/skbuff.h:4207
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff81bf9fb9)
Location: include/linux/skbuff.h:4207
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/unix/af_unix.c (ffffffff81d82670)
Location: include/linux/skbuff.h:4207
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81dce545)
Location: include/linux/skbuff.h:4207
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff81d93bc6)
Location: include/linux/skbuff.h:4103
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff81da8e87)
Location: include/linux/skbuff.h:4103
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/unix/af_unix.c (ffffffff81f4fbcb)
Location: include/linux/skbuff.h:4103
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81f9f695)
Location: include/linux/skbuff.h:4103
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff81e01766)
Location: include/linux/skbuff.h:4135
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff81e19fa1)
Location: include/linux/skbuff.h:4135
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/unix/af_unix.c (ffffffff81faf46e)
Location: include/linux/skbuff.h:4135
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff82000204)
Location: include/linux/skbuff.h:4135
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff81ebe113)
Location: include/linux/skbuff.h:4172
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/skbuff.c (ffffffff81ed757a)
Location: include/linux/skbuff.h:4172
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/unix/af_unix.c (ffffffff8207ca1a)
Location: include/linux/skbuff.h:4172
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff820cef94)
Location: include/linux/skbuff.h:4172
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffff800010ba1628)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffff800010bd371c)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffff800010cf3a44)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffff800010d3afb4)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (c0cc467c)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (c0cee47c)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (c0dfacfc)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (c0e3d904)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (c000000000c75ba0)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (c000000000cb22cc)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (c000000000e19c4c)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (c000000000e6e840)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffe00073972c)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffe00075d952)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffe0008403bc)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffe000877d32)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff818ac750)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff818d5459)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff819d3157)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a11d38)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff818666a0)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff8188f2c9)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff8198ff17)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff819ceaf8)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff818fd750)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff81926485)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff81a3dbd7)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a7c7b8)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
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
In net/socket.c (ffffffff8191e7c0)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/dev.c (ffffffff81947a2f)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/unix/af_unix.c (ffffffff81a49690)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a89008)
Location: include/linux/skbuff.h:3678
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
</details>
</li>
</ul>

## Differences
