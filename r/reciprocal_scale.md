# Function: <code>reciprocal_scale</code>

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
In net/core/dev.c (0)
Location: include/linux/kernel.h:240
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/linux/kernel.h:240
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/kernel.h:240
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/kernel.h:240
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/linux/kernel.h:240
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81804aa0)
Location: include/linux/kernel.h:240
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffffffff8177d2dd)
Location: include/linux/kernel.h:246
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
```
```
In net/core/sock_reuseport.c (ffffffff817a0005)
Location: include/linux/kernel.h:246
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/inet_hashtables.c (ffffffff817ce45e)
Location: include/linux/kernel.h:246
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff817f696b)
Location: include/linux/kernel.h:246
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/udp.c (ffffffff81851e05)
Location: include/linux/kernel.h:246
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8187348f)
Location: include/linux/kernel.h:246
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:246
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
In net/core/dev.c (ffffffff817aa80d)
Location: include/linux/kernel.h:251
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
```
```
In net/core/sock_reuseport.c (ffffffff817ce9d5)
Location: include/linux/kernel.h:251
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/inet_hashtables.c (ffffffff817fe269)
Location: include/linux/kernel.h:251
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff818278cb)
Location: include/linux/kernel.h:251
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/udp.c (ffffffff81883bc5)
Location: include/linux/kernel.h:251
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7aee)
Location: include/linux/kernel.h:251
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:251
Inline: True
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
In net/core/dev.c (ffffffff817c8e75)
Location: include/linux/kernel.h:255
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
```
```
In net/core/sock_reuseport.c (ffffffff817ede82)
Location: include/linux/kernel.h:255
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/inet_hashtables.c (ffffffff8181e5f6)
Location: include/linux/kernel.h:255
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81849183)
Location: include/linux/kernel.h:255
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/udp.c (ffffffff818a9f9e)
Location: include/linux/kernel.h:255
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce346)
Location: include/linux/kernel.h:255
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/packet/af_packet.c (ffffffff818d0845)
Location: include/linux/kernel.h:255
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffffffff81842b11)
Location: include/linux/kernel.h:277
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
```
```
In net/core/sock_reuseport.c (ffffffff8186a0c2)
Location: include/linux/kernel.h:277
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189d514)
Location: include/linux/kernel.h:277
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff818c8bf1)
Location: include/linux/kernel.h:277
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv6/udp.c (ffffffff8192c9a8)
Location: include/linux/kernel.h:277
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819531b9)
Location: include/linux/kernel.h:277
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
```
In net/packet/af_packet.c (ffffffff81955774)
Location: include/linux/kernel.h:277
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffffffff8188cf52)
Location: include/linux/kernel.h:278
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__netdev_pick_tx
```
```
In net/core/sock_reuseport.c (ffffffff818b9da7)
Location: include/linux/kernel.h:278
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (ffffffff8191e581)
Location: include/linux/kernel.h:278
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff819ae404)
Location: include/linux/kernel.h:278
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffffffff818ae19b)
Location: include/linux/kernel.h:311
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff818e0c1d)
Location: include/linux/kernel.h:311
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (ffffffff8194d381)
Location: include/linux/kernel.h:311
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff819e4db0)
Location: include/linux/kernel.h:311
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffffffff818f9ac9)
Location: include/linux/kernel.h:285
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff8192f2c9)
Location: include/linux/kernel.h:285
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (ffffffff819b1b39)
Location: include/linux/kernel.h:285
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:285
Inline: True
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
In net/core/dev.c (ffffffff8192bc29)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff81961539)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (ffffffff819e88b9)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:306
Inline: True
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
In net/core/dev.c (ffffffff81a0639d)
Location: include/linux/kernel.h:304
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff81a34c28)
Location: include/linux/kernel.h:304
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (ffffffff81ad6c40)
Location: include/linux/kernel.h:304
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81b865dc)
Location: include/linux/kernel.h:304
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffffffff81a0794b)
Location: include/linux/math.h:160
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff81a36f7f)
Location: include/linux/math.h:160
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (ffffffff81ae3220)
Location: include/linux/math.h:160
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81b95ef3)
Location: include/linux/math.h:160
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffffffff819ebcd7)
Location: include/linux/math.h:160
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff81a1e0df)
Location: include/linux/math.h:160
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (ffffffff81ace127)
Location: include/linux/math.h:160
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81b84dd3)
Location: include/linux/math.h:160
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffffffff81a9cbd7)
Location: include/linux/math.h:160
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff81ad1b97)
Location: include/linux/math.h:160
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (ffffffff81b8cae7)
Location: include/linux/math.h:160
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81c51284)
Location: include/linux/math.h:160
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffffffff81c152e8)
Location: include/linux/math.h:172
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff81c4f404)
Location: include/linux/math.h:172
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (ffffffff81d1b1a8)
Location: include/linux/math.h:172
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81df274b)
Location: include/linux/math.h:172
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffffffff81dc6648)
Location: include/linux/math.h:172
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff81e04215)
Location: include/linux/math.h:172
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock_by_hash
```
```
In net/ipv4/udp.c (ffffffff81ee1b80)
Location: include/linux/math.h:172
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81fc686b)
Location: include/linux/math.h:172
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffffffff81e359eb)
Location: include/linux/math.h:172
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff81e76a65)
Location: include/linux/math.h:172
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock_by_hash
```
```
In net/ipv4/udp.c (ffffffff81f4159f)
Location: include/linux/math.h:172
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff82027625)
Location: include/linux/math.h:172
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffffffff81ef3cab)
Location: include/linux/math.h:191
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff81f36a25)
Location: include/linux/math.h:191
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock_by_hash
```
```
In net/ipv4/udp.c (ffffffff820071ff)
Location: include/linux/math.h:191
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff820f6e85)
Location: include/linux/math.h:191
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffff800010bc82cc)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffff800010c04db8)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (ffff800010c9bda8)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffff800010d5abe4)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (c0ce3b50)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (c0d1e28c)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (c0da8524)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (c0e5a43c)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (c000000000ca41dc)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (c000000000ceef90)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (c000000000dade3c)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (c000000000e936d8)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffffffe0007547f4)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffe000783a0c)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (ffffffe0007fae58)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffe00088f6ae)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv_fanout
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
In net/core/dev.c (ffffffff818cbc29)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff81901509)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (ffffffff81988729)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:306
Inline: True
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
In net/core/dev.c (ffffffff81885b69)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff818bb339)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (ffffffff819421e9)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:306
Inline: True
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
In net/core/dev.c (ffffffff8191cc29)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff81952539)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a078f)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_resize
  - net/netfilter/nf_conntrack_core.c:early_drop
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_tuple_taken
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
  - net/netfilter/nf_conntrack_core.c:nf_ct_delete_from_lists
  - net/netfilter/nf_conntrack_core.c:nf_ct_delete_from_lists
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a2648)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_dst_hash
```
```
In net/ipv4/udp.c (ffffffff819f2ef9)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:306
Inline: True
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
In net/core/dev.c (ffffffff8193e0f9)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/sock_reuseport.c (ffffffff81973f98)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/udp.c (ffffffff819fb7c9)
Location: include/linux/kernel.h:306
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (0)
Location: include/linux/kernel.h:306
Inline: True
```
</details>
</li>
</ul>

## Differences
