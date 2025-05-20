# Function: <code>skb_frag_off</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/tso.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:2898
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
In drivers/net/xen-netfront.c (ffffffff8189939d)
Location: include/linux/skbuff.h:2921
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819ea75f)
Location: include/linux/skbuff.h:2921
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff819f4d22)
Location: include/linux/skbuff.h:2921
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff819fdc1b)
Location: include/linux/skbuff.h:2921
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffffffff81a3475e)
Location: include/linux/skbuff.h:2921
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (ffffffff81a9d304)
Location: include/linux/skbuff.h:2921
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81aa912f)
Location: include/linux/skbuff.h:2921
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (ffffffff81b2eb75)
Location: include/linux/skbuff.h:2921
Inline: True
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
In drivers/net/xen-netfront.c (ffffffff818a789d)
Location: include/linux/skbuff.h:2947
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819ea49f)
Location: include/linux/skbuff.h:2947
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff819f4efd)
Location: include/linux/skbuff.h:2947
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff819fd76b)
Location: include/linux/skbuff.h:2947
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffffffff81a36ab6)
Location: include/linux/skbuff.h:2947
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (ffffffff81aa71c4)
Location: include/linux/skbuff.h:2947
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ab361f)
Location: include/linux/skbuff.h:2947
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81b3d5c5)
Location: include/linux/skbuff.h:2947
Inline: True
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
In drivers/net/xen-netfront.c (ffffffff8188b14f)
Location: include/linux/skbuff.h:3011
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff819d0a5f)
Location: include/linux/skbuff.h:3011
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff819db085)
Location: include/linux/skbuff.h:3011
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff819f2623)
Location: include/linux/skbuff.h:3011
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
```
In net/core/tso.c (ffffffff81a1dc31)
Location: include/linux/skbuff.h:3011
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (ffffffff81a9235f)
Location: include/linux/skbuff.h:3011
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81a9e79d)
Location: include/linux/skbuff.h:3011
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81b2aa5f)
Location: include/linux/skbuff.h:3011
Inline: True
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
In drivers/net/xen-netfront.c (ffffffff8191dcf9)
Location: include/linux/skbuff.h:3040
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81a7fc10)
Location: include/linux/skbuff.h:3040
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81a8b734)
Location: include/linux/skbuff.h:3040
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (ffffffff81aa44f3)
Location: include/linux/skbuff.h:3040
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
```
In net/core/tso.c (ffffffff81ad16d1)
Location: include/linux/skbuff.h:3040
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (ffffffff81b4d76c)
Location: include/linux/skbuff.h:3040
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81b5a55b)
Location: include/linux/skbuff.h:3040
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81bf0add)
Location: include/linux/skbuff.h:3040
Inline: True
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
In drivers/net/xen-netfront.c (ffffffff81a75435)
Location: include/linux/skbuff.h:3409
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81bf4110)
Location: include/linux/skbuff.h:3409
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81c00d6d)
Location: include/linux/skbuff.h:3409
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/filter.c (ffffffff81c3f635)
Location: include/linux/skbuff.h:3409
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
```
```
In net/core/tso.c (ffffffff81c4f047)
Location: include/linux/skbuff.h:3409
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81c51ce1)
Location: include/linux/skbuff.h:3409
Inline: True
```
```
In net/core/gro.c (ffffffff81c544c3)
Location: include/linux/skbuff.h:3409
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81cb35a7)
Location: include/linux/skbuff.h:3409
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81cdaec0)
Location: include/linux/skbuff.h:3409
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81ce9072)
Location: include/linux/skbuff.h:3409
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81d890ec)
Location: include/linux/skbuff.h:3409
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81e1f7a7)
Location: include/linux/skbuff.h:3409
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In drivers/net/xen-netfront.c (ffffffff81c06e8f)
Location: include/linux/skbuff.h:3302
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81da1f20)
Location: include/linux/skbuff.h:3302
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81db019b)
Location: include/linux/skbuff.h:3302
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/filter.c (ffffffff81df3b45)
Location: include/linux/skbuff.h:3302
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
```
```
In net/core/tso.c (ffffffff81e040f7)
Location: include/linux/skbuff.h:3302
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81e0708e)
Location: include/linux/skbuff.h:3302
Inline: True
```
```
In net/core/gro.c (ffffffff81e09c13)
Location: include/linux/skbuff.h:3302
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81e7172b)
Location: include/linux/skbuff.h:3302
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81e9b79a)
Location: include/linux/skbuff.h:3302
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81eac5f2)
Location: include/linux/skbuff.h:3302
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv6/ip6_output.c (ffffffff81f56feb)
Location: include/linux/skbuff.h:3302
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ff62ed)
Location: include/linux/skbuff.h:3302
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In drivers/net/virtio_net.c (ffffffff81c55a82)
Location: include/linux/skbuff.h:3356
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:__virtnet_xdp_xmit_one
```
```
In drivers/net/xen-netfront.c (ffffffff81c6c57e)
Location: include/linux/skbuff.h:3356
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81e10784)
Location: include/linux/skbuff.h:3356
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81e2048b)
Location: include/linux/skbuff.h:3356
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/filter.c (ffffffff81e63536)
Location: include/linux/skbuff.h:3356
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
```
```
In net/core/tso.c (ffffffff81e767f4)
Location: include/linux/skbuff.h:3356
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81e7937c)
Location: include/linux/skbuff.h:3356
Inline: True
```
```
In net/core/gro.c (ffffffff81e7c3d9)
Location: include/linux/skbuff.h:3356
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81ecd9eb)
Location: include/linux/skbuff.h:3356
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81efa34c)
Location: include/linux/skbuff.h:3356
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81f0acd5)
Location: include/linux/skbuff.h:3356
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81f2291d)
Location: include/linux/skbuff.h:3356
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv6/ip6_output.c (ffffffff81fb6c0e)
Location: include/linux/skbuff.h:3356
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff820723f1)
Location: include/linux/skbuff.h:3356
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In drivers/net/virtio_net.c (ffffffff81d0c127)
Location: include/linux/skbuff.h:3379
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:__virtnet_xdp_xmit_one
```
```
In drivers/net/xen-netfront.c (ffffffff81d20f2a)
Location: include/linux/skbuff.h:3379
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/skbuff.c (ffffffff81ecd2a4)
Location: include/linux/skbuff.h:3379
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (ffffffff81ede365)
Location: include/linux/skbuff.h:3379
Inline: True
Inline callers:
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/filter.c (ffffffff81f27c64)
Location: include/linux/skbuff.h:3379
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
```
```
In net/core/tso.c (ffffffff81f367b7)
Location: include/linux/skbuff.h:3379
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81f3940c)
Location: include/linux/skbuff.h:3379
Inline: True
```
```
In net/core/gro.c (ffffffff81f3c729)
Location: include/linux/skbuff.h:3379
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81f9121b)
Location: include/linux/skbuff.h:3379
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81fbe29b)
Location: include/linux/skbuff.h:3379
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (ffffffff81fd2ec7)
Location: include/linux/skbuff.h:3379
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:receive_fallback_to_copy
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81fe630d)
Location: include/linux/skbuff.h:3379
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_clone_payload
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204c846)
Location: include/linux/skbuff.h:3379
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_hash_skb_data
```
```
In net/ipv6/ip6_output.c (ffffffff82084398)
Location: include/linux/skbuff.h:3379
Inline: True
```
```
In net/xdp/xsk.c (ffffffff8213c763)
Location: include/linux/skbuff.h:3379
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_copy_xdp
```
```
In net/mptcp/protocol.c (ffffffff82146549)
Location: include/linux/skbuff.h:3379
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In drivers/net/ethernet/broadcom/bgmac.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/tso.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:2898
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
In drivers/net/ethernet/freescale/fec_main.c (c0acd3d4)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In net/core/skbuff.c (c0cd0e7c)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_append_pagefrags
  - net/core/skbuff.c:skb_seq_read
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:skb_store_bits
  - net/core/skbuff.c:skb_send_sock_locked
  - net/core/skbuff.c:__skb_splice_bits
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_dump
```
```
In net/core/datagram.c (c0cd8398)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:__skb_datagram_iter
```
```
In net/core/dev.c (c0ce49d8)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (c0d1df5c)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/ip_output.c (c0d736f4)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp.c (c0d7efe4)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_md5_hash_skb_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv6/ip6_output.c (c0e00bec)
Location: include/linux/skbuff.h:2898
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/tso.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:2898
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/tso.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:2898
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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/tso.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:2898
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/tso.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:2898
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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/tso.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:2898
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
In drivers/net/xen-netfront.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/core/tso.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/skbuff.h:2898
Inline: True
```
</details>
</li>
</ul>

## Differences
