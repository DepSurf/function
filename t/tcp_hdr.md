# Function: <code>tcp_hdr</code>

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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:27
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/tcp.h:27
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/tcp.h:27
Inline: True
```
```
In net/core/tso.c (0)
Location: include/linux/tcp.h:27
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8175f6a3)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff81766c67)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff8176c6e6)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
```
```
In net/ipv4/tcp_output.c (ffffffff81774ce1)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177a9e6)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177f7a2)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_check_req
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/linux/tcp.h:27
Inline: True
```
```
In net/ipv4/tcp_offload.c (ffffffff81783308)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
```
```
In net/ipv4/syncookies.c (ffffffff817ab419)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817eedd0)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_sequence
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
```
In net/ipv6/syncookies.c (ffffffff817ff2c8)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/tcpv6_offload.c (ffffffff8180129b)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:27
Inline: True
```
```
In net/core/skbuff.c (ffffffff8176bf6c)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/dev.c (0)
Location: include/linux/tcp.h:27
Inline: True
```
```
In net/core/tso.c (ffffffff8179fd45)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffffffff817cb943)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff817d314f)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff817dc8c4)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ec048)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec781)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817f0089)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff817f0736)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff81818f09)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860bf0)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_sequence
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffffffff8186ec52)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81872adb)
Location: include/linux/tcp.h:27
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:28
Inline: True
```
```
In net/core/skbuff.c (ffffffff8179914c)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/dev.c (0)
Location: include/linux/tcp.h:28
Inline: True
```
```
In net/core/tso.c (ffffffff817ce715)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffffffff817fb5a5)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff81804a3e)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff8180c9c2)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c9d0)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181d071)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81820aa7)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff818214a6)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff8184a769)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892bbc)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_sequence
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffffffff818a1ba2)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818a70fb)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:28
Inline: True
```
```
In net/core/skbuff.c (ffffffff817b7722)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/dev.c (0)
Location: include/linux/tcp.h:28
Inline: True
```
```
In net/core/tso.c (ffffffff817edbc5)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffffffff8181b977)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff81824d76)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff8182cbf1)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183d1c5)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d88d)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818410ba)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81842186)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff8186e10d)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b91a9)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffffffff818c8169)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff818cdb6b)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:28
Inline: True
```
```
In net/core/skbuff.c (ffffffff8182fde2)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff81869e05)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffffffff8189a8b0)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff818a36df)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff818abaeb)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc9b0)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bcf9d)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0822)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff818c1a66)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff818eea9d)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193c0f5)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffffffff8194b719)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff8195296b)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:28
Inline: True
```
```
In net/core/skbuff.c (ffffffff8187a462)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff818b9ad5)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffffffff818eed79)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff818f8a42)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81900680)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819124ef)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912dfe)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819163e7)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81917702)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff819453b8)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819954e6)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffffffff819a49c9)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819abf25)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:28
Inline: True
```
```
In net/core/skbuff.c (ffffffff8189b072)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff818e0895)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffffffff8191c568)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff81926772)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff8192e7d8)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940cc9)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819415be)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944b87)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81945e3f)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff81975748)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbdcb)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffffffff819db4d9)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e2b02)
Location: include/linux/tcp.h:28
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffff818e5752)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff8192ef25)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffffffff8197e88e)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff81987632)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81991d91)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a52a3)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5bb8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a91ed)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff819aa475)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff819df268)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a8be)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffffffff81a4a149)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a51848)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffff819178a2)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff81961195)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffffffff819b522e)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff819bddf2)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff819c89a5)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbf99)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc978)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819dfd94)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff819e1145)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff81a162f8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a71461)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffffffff81a80d09)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a88448)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffff819e9ee2)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/tso.c (ffffffff81a346a8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffffffff81a9f489)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81ab3ed2)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac90dc)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9a48)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acd0dc)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81ace725)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff81b07326)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6ad6a)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffffffff81b7b98c)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b83914)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/mptcp/options.c (ffffffff81bb0ea5)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffff819e9c82)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/filter.c (ffffffff81a2c6ea)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/tso.c (ffffffff81a36a49)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (ffffffff81aa93c9)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81abe831)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_ecn_create_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_output.c (ffffffff81ac75a3)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad507c)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5998)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad90ec)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81ada75a)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff81b156f4)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b77032)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/syncookies.c (ffffffff81b8a9cc)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b92fd4)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/mptcp/options.c (ffffffff81bc4bf5)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffff819cfdc4)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/filter.c (ffffffff81a13c9a)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/tso.c (ffffffff81a1dbc4)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (ffffffff81a94592)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff81a9e636)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81aaab94)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_output.c (ffffffff81ab25c2)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac00fe)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac09f7)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3f4c)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81ac57da)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff81b03507)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b65b52)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/syncookies.c (ffffffff81b79839)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81b82124)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/mptcp/options.c (ffffffff81bb5265)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
```
```
In net/mptcp/syncookies.c (ffffffff81bbcc95)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffff81a7f7f4)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/filter.c (ffffffff81ac575a)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/tso.c (ffffffff81ad1664)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (ffffffff81b4fa12)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff81b5a3f6)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81b66f84)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f462)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7dd6e)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e3b7)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b825dc)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81b83fea)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff81bc5797)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2c583)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/syncookies.c (ffffffff81c444e3)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e1d4)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/mptcp/options.c (ffffffff81c83e45)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
```
```
In net/mptcp/syncookies.c (ffffffff81c8caf5)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffff81bf3c43)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/filter.c (ffffffff81c4128f)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/tso.c (ffffffff81c4ef69)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (ffffffff81cdd491)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff81ce7c73)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81cf65f5)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_output.c (ffffffff81cfeb12)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0dd7f)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e335)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d12b0f)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81d147a9)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff81d5a9a9)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc9845)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/syncookies.c (ffffffff81de34b3)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81deea92)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/mptcp/options.c (ffffffff81e29fe5)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
```
```
In net/mptcp/syncookies.c (ffffffff81e361a5)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffff81da19a3)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/filter.c (ffffffff81df69ef)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/tso.c (ffffffff81e04019)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (ffffffff81e9df50)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff81eab559)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81ebb005)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3a42)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed372b)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3de5)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed895e)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81eda8d9)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff81f24e19)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9a7c5)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/syncookies.c (ffffffff81fb5b33)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2ad2)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/mptcp/options.c (ffffffff82002105)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
```
```
In net/mptcp/syncookies.c (ffffffff8200f175)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e1b1b4)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/filter.c (ffffffff81e6869f)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/tso.c (ffffffff81e768b8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/gso.c (ffffffff81e7d463)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_transport_seglen
```
```
In net/ipv4/ip_output.c (ffffffff81efc71a)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff81f09c79)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81f19496)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_output.c (ffffffff81f21c82)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f32437)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32dd9)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f37a6e)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81f399b9)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff81f849a9)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffb325)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/syncookies.c (ffffffff82016244)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff82023a62)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/mptcp/options.c (ffffffff8207e2c5)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
```
```
In net/mptcp/syncookies.c (ffffffff8208bd65)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed8774)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup_ip
```
```
In net/core/filter.c (ffffffff81f2786f)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/tso.c (ffffffff81f3687b)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_start
```
```
In net/core/gso.c (ffffffff81f3e3e3)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_transport_seglen
```
```
In net/ipv4/ip_output.c (ffffffff81fc065a)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff81fcf451)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
  - net/ipv4/tcp.c:tcp_inbound_md5_hash
```
```
In net/ipv4/tcp_input.c (ffffffff81fddeaf)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5c22)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff8402)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8f29)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffdb3e)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/tcp_offload.c (ffffffff81fffaa9)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff8204b222)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c75d)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data
```
```
In net/ipv4/tcp_ao.c (ffffffff82058dab)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_finish_connect
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_inbound_ao_hash
  - net/ipv4/tcp_ao.c:tcp_ao_syncookie
  - net/ipv4/tcp_ao.c:tcp_ao_prepare_reset
  - net/ipv4/tcp_ao.c:tcp_ao_hash_skb
  - net/ipv4/tcp_ao.c:tcp_ao_hash_skb
  - net/ipv4/tcp_ao.c:tcp_ao_calc_key_skb
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c8c05)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
```
```
In net/ipv6/syncookies.c (ffffffff820e534c)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff820f2bc2)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
```
In net/ipv6/tcp_ao.c (ffffffff820f489a)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ao.c:tcp_v6_ao_calc_key_skb
```
```
In net/mptcp/options.c (ffffffff821537b5)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_options
  - net/mptcp/options.c:mptcp_parse_option
```
```
In net/mptcp/syncookies.c (ffffffff82162225)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_join_entry_hash
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffff800010bb0c44)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffff800010c04a60)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffff800010c659f8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffff800010c6fa78)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffff800010c7a630)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8f244)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f8dc)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c9393c)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffff800010c95180)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffff800010cd1ffc)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39868)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffff800010d4c574)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffff800010d54fd8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (c0ccdfcc)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (c0d1decc)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (c0d75670)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (c0d7ee98)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (c0d88090)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (c0d9e184)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (c0d9e99c)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (c0da22b8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (c0da38c8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (c0ddbe90)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (c0e3c378)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (c0e4d834)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (c0e55598)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (c000000000c86e58)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (c000000000ceea08)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (c000000000d6a16c)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (c000000000d765a0)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (c000000000d851c0)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9dec8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e8f4)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (c000000000da3de0)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (c000000000da6104)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (c000000000df03c0)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6cf48)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (c000000000e82c20)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (c000000000e8dcd4)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffe000741df6)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffe000783636)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffffffe0007cd120)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffe0007d4d6c)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffe0007de2b4)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ef3d2)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efc04)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2fa4)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f4398)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffe0008233d8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876af8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffffffe0008852f4)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffe00088c848)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffff818b78a2)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff81901165)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffffffff8195509e)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff8195dc62)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81968815)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197be09)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c7e8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197fc04)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff81980fb5)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff819b5988)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10af1)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffffffff81a20399)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a27ad8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffff818717f2)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff818baf95)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffffffff8190eb8e)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff81917752)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff81922305)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819358c9)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819362a8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819396c4)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff8193aa75)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff81972778)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd8b1)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffffffff819dd159)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff819e4898)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffff819088a2)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff81952195)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffffffff819bf86e)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff819c8432)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff819d2fe5)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e65d9)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6fb8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819ea3d4)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff819eb785)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff81a20228)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7b571)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffffffff81a8ae19)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a93688)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
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
In security/lsm_audit.c (0)
Location: include/linux/tcp.h:24
Inline: True
```
```
In net/core/skbuff.c (ffffffff81929952)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff81973bd5)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/ip_output.c (ffffffff819c91ed)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
```
```
In net/ipv4/tcp.c (ffffffff819d1f82)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
```
```
In net/ipv4/tcp_input.c (ffffffff819dcb86)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_parse_options
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_oow_rate_limited
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819f0299)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_do_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_inbound_md5_hash
  - net/ipv4/tcp_ipv4.c:tcp_v4_md5_hash_skb
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:__tcp_v4_send_check
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_seq
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0c88)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f4212)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/tcp_offload.c (ffffffff819f5635)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp_gro_receive
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/syncookies.c (ffffffff81a2b728)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:cookie_v4_init_sequence
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87db1)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_inbound_md5_hash
  - net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_init_seq
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/syncookies.c (ffffffff81a97a79)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
  - net/ipv6/syncookies.c:cookie_v6_init_sequence
```
```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f7d8)
Location: include/linux/tcp.h:24
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
```
</details>
</li>
</ul>

## Differences
