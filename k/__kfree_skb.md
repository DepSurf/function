# Function: <code>__kfree_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81705ff0)
Location: net/core/skbuff.c:681
Inline: True
Inline callers:
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:consume_skb
Direct callers:
  - net/core/datagram.c:skb_free_datagram_locked
  - net/core/dev.c:net_tx_action
  - net/core/dev.c:napi_gro_receive
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81705ff0-ffffffff8170600d: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176e534)
Location: net/core/skbuff.c:682
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
Direct callers:
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff8176e060-ffffffff8176e07d: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179b9f4)
Location: net/core/skbuff.c:682
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
Direct callers:
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff8179b4a0-ffffffff8179b4bd: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bd8b4)
Location: net/core/skbuff.c:679
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff817bb4c0-ffffffff817bb4dd: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81833cd4)
Location: net/core/skbuff.c:639
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff81833550-ffffffff8183356d: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187d9f0)
Location: net/core/skbuff.c:639
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff8187d9f0-ffffffff8187da0d: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189e5c0)
Location: net/core/skbuff.c:643
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff8189e5c0-ffffffff8189e5dd: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e9564)
Location: net/core/skbuff.c:677
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff818e8e30-ffffffff818e8e4f: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191b6c4)
Location: net/core/skbuff.c:677
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff8191af90-ffffffff8191afaf: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed564)
Location: net/core/skbuff.c:676
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/mptcp/protocol.c:__mptcp_recvmsg_mskq
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff819edaa0-ffffffff819edad4: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed233)
Location: net/core/skbuff.c:690
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/mptcp/protocol.c:__mptcp_recvmsg_mskq
  - net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/subflow.c:mptcp_subflow_discard_data
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff819ed760-ffffffff819ed794: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d3607)
Location: net/core/skbuff.c:738
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff819d52c0-ffffffff819d52f4: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a83364)
Location: net/core/skbuff.c:754
Inline: True
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_ofo_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
```
**Symbols:**

```
ffffffff81a85050-ffffffff81a85084: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bffd93)
Location: net/core/skbuff.c:754
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_attempt_defer_free
Direct callers:
  - net/core/dev.c:net_tx_action
  - net/core/gro.c:napi_gro_receive
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
```
**Symbols:**

```
ffffffff81bfb050-ffffffff81bfb088: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81daf123)
Location: net/core/skbuff.c:928
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:kfree_skb_reason
Direct callers:
  - net/core/dev.c:net_tx_action
  - net/core/gro.c:napi_gro_receive
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
```
**Symbols:**

```
ffffffff81da9d80-ffffffff81da9dbf: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1f310)
Location: net/core/skbuff.c:1020
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
Direct callers:
  - net/core/dev.c:net_tx_action
  - net/core/gro.c:napi_gro_receive
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
```
**Symbols:**

```
ffffffff81e18b00-ffffffff81e18b43: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81edc970)
Location: net/core/skbuff.c:1106
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
Direct callers:
  - net/core/dev.c:net_tx_action
  - net/core/gro.c:napi_gro_receive
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_recvmsg_locked
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_done
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:tcp_remove_empty_skb
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:validate_data_csum
```
**Symbols:**

```
ffffffff81ed5f90-ffffffff81ed5fd3: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb5bc8)
Location: net/core/skbuff.c:677
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffff800010bb5360-ffff800010bb5394: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd2bd4)
Location: net/core/skbuff.c:677
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
c0cd2438-c0cd2460: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8d004)
Location: net/core/skbuff.c:677
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
Direct callers:
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
c000000000c8c3f0-c000000000c8c430: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000745ad6)
Location: net/core/skbuff.c:677
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffe0007453fa-ffffffe00074542e: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bb6c4)
Location: net/core/skbuff.c:677
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff818baf90-ffffffff818bafaf: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81875604)
Location: net/core/skbuff.c:677
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff81874ed0-ffffffff81874eef: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190c6c4)
Location: net/core/skbuff.c:677
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff8190bf90-ffffffff8190bfaf: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __kfree_skb(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192d7f8)
Location: net/core/skbuff.c:677
Inline: True
Inline callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
  - net/core/netpoll.c:zap_completion_queue
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_read_sock
  - net/ipv4/tcp.c:tcp_recv_skb
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_collapse_one
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/ipv4/tcp_input.c:tcp_drop
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/af_inet.c:inet_sock_destruct
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish2
```
**Symbols:**

```
ffffffff8192d0b0-ffffffff8192d0cf: __kfree_skb (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
