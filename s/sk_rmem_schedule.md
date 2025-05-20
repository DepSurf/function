# Function: <code>sk_rmem_schedule</code>

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
In net/core/sock.c (ffffffff81702ece)
Location: include/net/sock.h:1391
Inline: True
Inline callers:
  - net/core/sock.c:sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8176e859)
Location: include/net/sock.h:1391
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
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
In net/core/sock.c (ffffffff8176838c)
Location: include/net/sock.h:1298
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff817da829)
Location: include/net/sock.h:1298
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
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
In net/core/sock.c (ffffffff817953cc)
Location: include/net/sock.h:1354
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8180b42e)
Location: include/net/sock.h:1354
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
In net/core/sock.c (ffffffff817b3988)
Location: include/net/sock.h:1357
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8182bc9e)
Location: include/net/sock.h:1357
Inline: True
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
In net/core/sock.c (ffffffff8182cff8)
Location: include/net/sock.h:1361
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff818ae46e)
Location: include/net/sock.h:1361
Inline: True
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
In kernel/bpf/sockmap.c (ffffffff811ccd77)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_tx_work
```
```
In net/core/sock.c (ffffffff81876df9)
Location: include/net/sock.h:1376
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81903b1e)
Location: include/net/sock.h:1376
Inline: True
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
In net/core/sock.c (ffffffff81897599)
Location: include/net/sock.h:1414
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff818e63f7)
Location: include/net/sock.h:1414
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff81931cee)
Location: include/net/sock.h:1414
Inline: True
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
In net/core/sock.c (ffffffff818e19d9)
Location: include/net/sock.h:1417
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81935d72)
Location: include/net/sock.h:1417
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff819953ee)
Location: include/net/sock.h:1417
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
In net/core/sock.c (ffffffff81913bc9)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81968a92)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff819cbf3e)
Location: include/net/sock.h:1427
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
In net/core/sock.c (ffffffff819e5cd9)
Location: include/net/sock.h:1475
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81a3bc69)
Location: include/net/sock.h:1475
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress
```
```
In net/ipv4/tcp_input.c (ffffffff81ab29f5)
Location: include/net/sock.h:1475
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b22670)
Location: include/net/sock.h:1475
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
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
In net/core/sock.c (ffffffff819e57a9)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81a3f833)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff81abdd35)
Location: include/net/sock.h:1491
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b31070)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/mptcp/protocol.c (ffffffff81bbd19c)
Location: include/net/sock.h:1491
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/sock.c (ffffffff819cb8b9)
Location: include/net/sock.h:1507
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81a4ea01)
Location: include/net/sock.h:1507
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff81aa8e9e)
Location: include/net/sock.h:1507
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81b1eda0)
Location: include/net/sock.h:1507
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/mptcp/protocol.c (ffffffff81bac9ec)
Location: include/net/sock.h:1507
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/sock.c (ffffffff81a7af49)
Location: include/net/sock.h:1517
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81b07572)
Location: include/net/sock.h:1517
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff81b64bee)
Location: include/net/sock.h:1517
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff81be3d88)
Location: include/net/sock.h:1517
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
```
In net/mptcp/protocol.c (ffffffff81c7936c)
Location: include/net/sock.h:1517
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/sock.c (ffffffff81bee5a9)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81c8ccde)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff81cf3a7e)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/xfrm/espintcp.c (ffffffff81d7ab60)
Location: include/net/sock.h:1592
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
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
In net/core/sock.c (ffffffff81d9e069)
Location: include/net/sock.h:1638
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81e47b76)
Location: include/net/sock.h:1638
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff81eb847e)
Location: include/net/sock.h:1638
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/xfrm/espintcp.c (ffffffff81f47b30)
Location: include/net/sock.h:1638
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c5f0)
Location: include/net/sock.h:1638
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/core/sock.c (ffffffff81e0c8dd)
Location: include/net/sock.h:1629
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81ea32f4)
Location: include/net/sock.h:1629
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff81f168ee)
Location: include/net/sock.h:1629
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/xfrm/espintcp.c (ffffffff81fa7630)
Location: include/net/sock.h:1629
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffd040)
Location: include/net/sock.h:1629
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/core/sock.c (ffffffff81ec924d)
Location: include/net/sock.h:1604
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81f65636)
Location: include/net/sock.h:1604
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff81fdb75e)
Location: include/net/sock.h:1604
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/xfrm/espintcp.c (ffffffff820748e0)
Location: include/net/sock.h:1604
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:handle_nonesp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc155)
Location: include/net/sock.h:1604
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/core/sock.c (ffff800010bacf8c)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffff800010c0f904)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffff800010c7eba0)
Location: include/net/sock.h:1427
Inline: True
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
In net/core/sock.c (c0cca2d4)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (c0d26244)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (c0d8dbd4)
Location: include/net/sock.h:1427
Inline: True
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
In net/core/sock.c (c000000000c823a4)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (c000000000cfa72c)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (c000000000d89208)
Location: include/net/sock.h:1427
Inline: True
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
In net/core/sock.c (ffffffe00073efbe)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffe00078b446)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0e14)
Location: include/net/sock.h:1427
Inline: True
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
In net/core/sock.c (ffffffff818b3bc9)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81908a62)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff8196bdae)
Location: include/net/sock.h:1427
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
In net/core/sock.c (ffffffff8186db19)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff818c2872)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff8192589e)
Location: include/net/sock.h:1427
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
In net/core/sock.c (ffffffff81904bc9)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff81959a92)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff819d657e)
Location: include/net/sock.h:1427
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
In net/core/sock.c (ffffffff81925c69)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/core/skmsg.c (ffffffff8197bcb2)
Location: include/net/sock.h:1427
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_input.c (ffffffff819e019e)
Location: include/net/sock.h:1427
Inline: True
```
</details>
</li>
</ul>

## Differences
