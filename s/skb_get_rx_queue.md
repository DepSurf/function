# Function: <code>skb_get_rx_queue</code>

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
In drivers/net/tun.c (ffffffff815edeee)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/dev.c (ffffffff817151cf)
Location: include/linux/skbuff.h:3423
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
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
In drivers/net/tun.c (ffffffff8164cec5)
Location: include/linux/skbuff.h:3630
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/dev.c (ffffffff8177d21f)
Location: include/linux/skbuff.h:3630
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__skb_tx_hash
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
In drivers/net/tun.c (ffffffff8167ec05)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/dev.c (ffffffff817aa74f)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__skb_tx_hash
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
In drivers/net/tun.c (ffffffff81693dc1)
Location: include/linux/skbuff.h:3736
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/dev.c (ffffffff817c8daf)
Location: include/linux/skbuff.h:3736
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__skb_tx_hash
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
In drivers/net/tun.c (ffffffff816fdc2a)
Location: include/linux/skbuff.h:3927
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/dev.c (ffffffff81842a4f)
Location: include/linux/skbuff.h:3927
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__skb_tx_hash
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
In drivers/net/tun.c (ffffffff8173c729)
Location: include/linux/skbuff.h:3937
Inline: True
```
```
In net/core/dev.c (ffffffff8188ce8f)
Location: include/linux/skbuff.h:3937
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
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
In net/core/dev.c (ffffffff818ae0dc)
Location: include/linux/skbuff.h:4100
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff8192e99e)
Location: include/linux/skbuff.h:4100
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f306)
Location: include/linux/skbuff.h:4100
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81941590)
Location: include/linux/skbuff.h:4100
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff8194cf13)
Location: include/linux/skbuff.h:4100
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff819bb268)
Location: include/linux/skbuff.h:4100
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca917)
Location: include/linux/skbuff.h:4100
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (ffffffff818fab96)
Location: include/linux/skbuff.h:4207
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff8199221c)
Location: include/linux/skbuff.h:4207
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a380e)
Location: include/linux/skbuff.h:4207
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5b86)
Location: include/linux/skbuff.h:4207
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff819b16ce)
Location: include/linux/skbuff.h:4207
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a29e7b)
Location: include/linux/skbuff.h:4207
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3953e)
Location: include/linux/skbuff.h:4207
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (ffffffff8192ccba)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff819c8d48)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da42e)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc946)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff819e8432)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a6099b)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a700ce)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (ffffffff81a066f6)
Location: include/linux/skbuff.h:4331
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff81ab42f0)
Location: include/linux/skbuff.h:4331
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac76aa)
Location: include/linux/skbuff.h:4331
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9a16)
Location: include/linux/skbuff.h:4331
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81ad6377)
Location: include/linux/skbuff.h:4331
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81b574a3)
Location: include/linux/skbuff.h:4331
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69cde)
Location: include/linux/skbuff.h:4331
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (ffffffff81a07caa)
Location: include/linux/skbuff.h:4360
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff81abeb54)
Location: include/linux/skbuff.h:4360
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad2fea)
Location: include/linux/skbuff.h:4360
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5966)
Location: include/linux/skbuff.h:4360
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81ae26c4)
Location: include/linux/skbuff.h:4360
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_queue_rcv_skb
```
```
In net/ipv6/udp.c (ffffffff81b659c3)
Location: include/linux/skbuff.h:4360
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udpv6_queue_rcv_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b787be)
Location: include/linux/skbuff.h:4360
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (ffffffff819ea5dc)
Location: include/linux/skbuff.h:4424
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff81aaaec5)
Location: include/linux/skbuff.h:4424
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abdc22)
Location: include/linux/skbuff.h:4424
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac09c6)
Location: include/linux/skbuff.h:4424
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81acd87f)
Location: include/linux/skbuff.h:4424
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81b56160)
Location: include/linux/skbuff.h:4424
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66abe)
Location: include/linux/skbuff.h:4424
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (ffffffff81aa1bde)
Location: include/linux/skbuff.h:4463
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff81b67268)
Location: include/linux/skbuff.h:4463
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7b0f7)
Location: include/linux/skbuff.h:4463
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e386)
Location: include/linux/skbuff.h:4463
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81b8c25c)
Location: include/linux/skbuff.h:4463
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81c1c7dd)
Location: include/linux/skbuff.h:4463
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e66e)
Location: include/linux/skbuff.h:4463
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (ffffffff81c19dbc)
Location: include/linux/skbuff.h:4885
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff81cf622c)
Location: include/linux/skbuff.h:4885
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0baa8)
Location: include/linux/skbuff.h:4885
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e303)
Location: include/linux/skbuff.h:4885
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81d1c85b)
Location: include/linux/skbuff.h:4885
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81db906b)
Location: include/linux/skbuff.h:4885
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb30d)
Location: include/linux/skbuff.h:4885
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (ffffffff81dcae3c)
Location: include/linux/skbuff.h:4781
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff81ebac3c)
Location: include/linux/skbuff.h:4781
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed1a08)
Location: include/linux/skbuff.h:4781
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3db3)
Location: include/linux/skbuff.h:4781
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81ee3864)
Location: include/linux/skbuff.h:4781
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81f88fdc)
Location: include/linux/skbuff.h:4781
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c39d)
Location: include/linux/skbuff.h:4781
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In drivers/net/net_failover.c (ffffffff81c6f204)
Location: include/linux/skbuff.h:4813
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_select_queue
```
```
In net/core/dev.c (ffffffff81e3b9be)
Location: include/linux/skbuff.h:4813
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff81f190d0)
Location: include/linux/skbuff.h:4813
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f3017c)
Location: include/linux/skbuff.h:4813
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32da7)
Location: include/linux/skbuff.h:4813
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81f430d7)
Location: include/linux/skbuff.h:4813
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81fe839d)
Location: include/linux/skbuff.h:4813
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffcdef)
Location: include/linux/skbuff.h:4813
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In drivers/net/net_failover.c (ffffffff81d23ace)
Location: include/linux/skbuff.h:4853
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_select_queue
```
```
In net/core/dev.c (ffffffff81ef9efe)
Location: include/linux/skbuff.h:4853
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff81fdd997)
Location: include/linux/skbuff.h:4853
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff600c)
Location: include/linux/skbuff.h:4853
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8ef7)
Location: include/linux/skbuff.h:4853
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff82009040)
Location: include/linux/skbuff.h:4853
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff820b6ef1)
Location: include/linux/skbuff.h:4853
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cbf0f)
Location: include/linux/skbuff.h:4853
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (ffff800010bcf5b0)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffff800010c7a87c)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8d4dc)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f8b0)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffff800010c9d86c)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffff800010d26584)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d389f4)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (c0ce5974)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (c0d88480)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (c0d9c5bc)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (c0d9e978)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (c0dab2bc)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (c0e29b88)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (c0e3ada8)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (c000000000ca63e0)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (c000000000d854d0)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9c630)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e8c4)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (c000000000daf144)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (c000000000e561e4)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b348)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (ffffffe000755acc)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffe0007de816)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ed91a)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efbe0)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffe0007fa864)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffe000866c14)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875c48)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (ffffffff818cccba)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff81968bb8)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a29e)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c7b6)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff819882a2)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a0002b)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0f75e)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (ffffffff81886d4a)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff819226a8)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81933d5e)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936276)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff81941d62)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff819bcdeb)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cc51e)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (ffffffff8191dcba)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff819d3388)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e4a6e)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6f86)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff819f2a72)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a6aaab)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a1de)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/dev.c (ffffffff8193f32a)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
```
```
In net/ipv4/tcp_input.c (ffffffff819dcf2e)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_finish_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eebae)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0c56)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/udp.c (ffffffff819fcf72)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv6/udp.c (ffffffff81a770bb)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86a1e)
Location: include/linux/skbuff.h:4291
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
</details>
</li>
</ul>

## Differences
