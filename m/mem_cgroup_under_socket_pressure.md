# Function: <code>mem_cgroup_under_socket_pressure</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81768171)
Location: include/linux/memcontrol.h:768
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/ipv4/tcp.c (ffffffff817d58af)
Location: include/linux/memcontrol.h:768
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff817dbdd2)
Location: include/linux/memcontrol.h:768
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/tcp_output.c (ffffffff817e6321)
Location: include/linux/memcontrol.h:768
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff817e6f06)
Location: include/linux/memcontrol.h:768
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (ffffffff81795166)
Location: include/linux/memcontrol.h:803
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81805893)
Location: include/linux/memcontrol.h:803
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8180bea8)
Location: include/linux/memcontrol.h:803
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81816a41)
Location: include/linux/memcontrol.h:803
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff8181764c)
Location: include/linux/memcontrol.h:803
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (ffffffff817b38c3)
Location: include/linux/memcontrol.h:1066
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81825d36)
Location: include/linux/memcontrol.h:1066
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81828004)
Location: include/linux/memcontrol.h:1066
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff81836d9b)
Location: include/linux/memcontrol.h:1066
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81837ac0)
Location: include/linux/memcontrol.h:1066
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (ffffffff8182bce9)
Location: include/linux/memcontrol.h:1078
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff818a3df2)
Location: include/linux/memcontrol.h:1078
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff818a751f)
Location: include/linux/memcontrol.h:1078
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff818b63b8)
Location: include/linux/memcontrol.h:1078
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff818b723c)
Location: include/linux/memcontrol.h:1078
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (ffffffff81875827)
Location: include/linux/memcontrol.h:1170
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff818f9b51)
Location: include/linux/memcontrol.h:1170
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819003d5)
Location: include/linux/memcontrol.h:1170
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff8190bbf8)
Location: include/linux/memcontrol.h:1170
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff8190cc60)
Location: include/linux/memcontrol.h:1170
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (ffffffff8189615d)
Location: include/linux/memcontrol.h:1254
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81927a81)
Location: include/linux/memcontrol.h:1254
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8192a7e5)
Location: include/linux/memcontrol.h:1254
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff81939ec5)
Location: include/linux/memcontrol.h:1254
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff8193af6f)
Location: include/linux/memcontrol.h:1254
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (ffffffff818e0669)
Location: include/linux/memcontrol.h:1265
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff8198a966)
Location: include/linux/memcontrol.h:1265
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8198da54)
Location: include/linux/memcontrol.h:1265
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff8199e17c)
Location: include/linux/memcontrol.h:1265
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f288)
Location: include/linux/memcontrol.h:1265
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (ffffffff81912833)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff819c112a)
Location: include/linux/memcontrol.h:1341
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819c4606)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819d4c46)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5e3a)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (ffffffff819e5b3d)
Location: include/linux/memcontrol.h:1314
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81aac85a)
Location: include/linux/memcontrol.h:1314
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81ab3346)
Location: include/linux/memcontrol.h:1314
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1606)
Location: include/linux/memcontrol.h:1314
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2cfc)
Location: include/linux/memcontrol.h:1314
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (ffffffff819e560d)
Location: include/linux/memcontrol.h:1571
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81ab41a9)
Location: include/linux/memcontrol.h:1571
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81abe29c)
Location: include/linux/memcontrol.h:1571
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81acd076)
Location: include/linux/memcontrol.h:1571
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace78c)
Location: include/linux/memcontrol.h:1571
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81bbeb5d)
Location: include/linux/memcontrol.h:1571
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_wmem_reserve
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
In net/core/sock.c (ffffffff819cb71d)
Location: include/linux/memcontrol.h:1604
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81a9f319)
Location: include/linux/memcontrol.h:1604
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81aa937c)
Location: include/linux/memcontrol.h:1604
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81ab8246)
Location: include/linux/memcontrol.h:1604
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab992c)
Location: include/linux/memcontrol.h:1604
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81bafb1c)
Location: include/linux/memcontrol.h:1604
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In net/core/sock.c (ffffffff81a7ada7)
Location: include/linux/memcontrol.h:1612
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81b5b0c9)
Location: include/linux/memcontrol.h:1612
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81b6526c)
Location: include/linux/memcontrol.h:1612
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81b75430)
Location: include/linux/memcontrol.h:1612
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76d62)
Location: include/linux/memcontrol.h:1612
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81c7d68c)
Location: include/linux/memcontrol.h:1612
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In net/core/sock.c (ffffffff81beeccc)
Location: include/linux/memcontrol.h:1682
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81ce9b24)
Location: include/linux/memcontrol.h:1682
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81cf35d0)
Location: include/linux/memcontrol.h:1682
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81d04c9d)
Location: include/linux/memcontrol.h:1682
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06619)
Location: include/linux/memcontrol.h:1682
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81e1f233)
Location: include/linux/memcontrol.h:1682
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In net/core/sock.c (ffffffff81d9e406)
Location: include/linux/memcontrol.h:1716
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81ead3e1)
Location: include/linux/memcontrol.h:1716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81eb7bf4)
Location: include/linux/memcontrol.h:1716
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81ec9ced)
Location: include/linux/memcontrol.h:1716
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/core/sock.c (ffffffff81e0c7a1)
Location: include/linux/memcontrol.h:1733
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81f0baf0)
Location: include/linux/memcontrol.h:1733
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81f15a24)
Location: include/linux/memcontrol.h:1733
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81f2883d)
Location: include/linux/memcontrol.h:1733
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp.c (ffffffff81fcfba5)
Location: include/linux/memcontrol.h:1771
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81fda6a4)
Location: include/linux/memcontrol.h:1771
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81fed2d5)
Location: include/linux/memcontrol.h:1771
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/mptcp/protocol.c (ffffffff82145744)
Location: include/linux/memcontrol.h:1771
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/sockopt.c (ffffffff821602c6)
Location: include/linux/memcontrol.h:1771
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_set_rcvlowat
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
In net/core/sock.c (ffff800010bace90)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffff800010c74048)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffff800010c77024)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffff800010c87884)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffff800010c88d8c)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (c0cc8a48)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (c0d826c4)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (c0d8558c)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (c0d96c2c)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (c0d97f20)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (c000000000c7fd2c)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (c000000000d7b010)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (c000000000d7f2cc)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (c000000000d9443c)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (c000000000d95ebc)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (ffffffe00073d776)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffe0007d7622)
Location: include/linux/memcontrol.h:1341
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffe0007da26e)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffe0007e8be6)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9da4)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (ffffffff818b2833)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81960f9a)
Location: include/linux/memcontrol.h:1341
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81964476)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff81974ab6)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81975caa)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (ffffffff8186c783)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff8191aa8a)
Location: include/linux/memcontrol.h:1341
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8191df66)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff8192e576)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f76a)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (ffffffff81903833)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff819cb76a)
Location: include/linux/memcontrol.h:1341
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819cec46)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819df286)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff819e047a)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/sock.c (ffffffff81924827)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff819d52fa)
Location: include/linux/memcontrol.h:1341
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819d87d6)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819e8f26)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea13a)
Location: include/linux/memcontrol.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
</details>
</li>
</ul>

## Differences
