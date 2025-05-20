# Function: <code>sk_psock</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818e5e15)
Location: include/linux/skmsg.h:274
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/sock_map.c (ffffffff818f25ca)
Location: include/linux/skmsg.h:274
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81978097)
Location: include/linux/skmsg.h:274
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
  - net/ipv4/tcp_bpf.c:tcp_bpf_reinit
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_stream_read
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
In net/core/skmsg.c (ffffffff8193555f)
Location: include/linux/skmsg.h:274
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/sock_map.c (ffffffff819446fc)
Location: include/linux/skmsg.h:274
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e1b72)
Location: include/linux/skmsg.h:274
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
  - net/ipv4/tcp_bpf.c:tcp_bpf_reinit
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_stream_read
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
In net/core/skmsg.c (ffffffff8196831c)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/sock_map.c (ffffffff819796fc)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a18b62)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
  - net/ipv4/tcp_bpf.c:tcp_bpf_reinit
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_stream_read
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
In net/core/skmsg.c (ffffffff81a3c54c)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_skb_redirect
```
```
In net/core/sock_map.c (ffffffff81a4eb2b)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_unhash
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link_no_progs
  - net/core/sock_map.c:sock_map_link
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b092c1)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_stream_read
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/core/skmsg.c (ffffffff81a3ec0c)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_skb_redirect
```
```
In net/core/sock_map.c (ffffffff81a54b0b)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_unhash
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link_no_progs
  - net/core/sock_map.c:sock_map_link
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17ad8)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_stream_read
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/core/skmsg.c (ffffffff81a4e5c9)
Location: include/linux/skmsg.h:285
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_skb_redirect
```
```
In net/core/sock_map.c (ffffffff81a5154f)
Location: include/linux/skmsg.h:285
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_unhash
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b056a4)
Location: include/linux/skmsg.h:285
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_stream_read
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81b05cb2)
Location: include/linux/skmsg.h:285
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
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
In net/core/skmsg.c (ffffffff81b07309)
Location: include/linux/skmsg.h:284
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_msg_is_readable
```
```
In net/core/sock_map.c (ffffffff81b094cf)
Location: include/linux/skmsg.h:284
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc81f4)
Location: include/linux/skmsg.h:284
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81bc89b3)
Location: include/linux/skmsg.h:284
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/unix/unix_bpf.c (ffffffff81beb736)
Location: include/linux/skmsg.h:284
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
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
In net/core/skmsg.c (ffffffff81c8bd6f)
Location: include/linux/skmsg.h:278
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_msg_is_readable
```
```
In net/core/sock_map.c (ffffffff81c8f5d9)
Location: include/linux/skmsg.h:278
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5da69)
Location: include/linux/skmsg.h:278
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81d5df54)
Location: include/linux/skmsg.h:278
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/unix/unix_bpf.c (ffffffff81d838f6)
Location: include/linux/skmsg.h:278
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
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
In net/core/skmsg.c (ffffffff81e482bc)
Location: include/linux/skmsg.h:280
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_msg_is_readable
```
```
In net/core/sock_map.c (ffffffff81e4a9f9)
Location: include/linux/skmsg.h:280
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_map_unhash
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27719)
Location: include/linux/skmsg.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81f28755)
Location: include/linux/skmsg.h:280
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
```
In net/unix/unix_bpf.c (ffffffff81f510f6)
Location: include/linux/skmsg.h:280
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
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
In net/core/skmsg.c (ffffffff81ea3a75)
Location: include/linux/skmsg.h:280
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_msg_is_readable
```
```
In net/core/sock_map.c (ffffffff81ea60f9)
Location: include/linux/skmsg.h:280
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_map_unhash
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f873f1)
Location: include/linux/skmsg.h:280
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff81f882bc)
Location: include/linux/skmsg.h:280
Inline: True
```
```
In net/unix/unix_bpf.c (ffffffff81fb0a57)
Location: include/linux/skmsg.h:280
Inline: True
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
In net/core/skmsg.c (ffffffff81f66375)
Location: include/linux/skmsg.h:286
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_msg_is_readable
```
```
In net/core/sock_map.c (ffffffff81f68bb9)
Location: include/linux/skmsg.h:286
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_map_unhash
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204ea71)
Location: include/linux/skmsg.h:286
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
```
In net/ipv4/udp_bpf.c (ffffffff8204f9dc)
Location: include/linux/skmsg.h:286
Inline: True
```
```
In net/unix/unix_bpf.c (ffffffff8207e0f7)
Location: include/linux/skmsg.h:286
Inline: True
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
In net/core/skmsg.c (ffff800010c0e228)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/sock_map.c (ffff800010c20b30)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd4678)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
  - net/ipv4/tcp_bpf.c:tcp_bpf_reinit
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_stream_read
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
In net/core/skmsg.c (c0d2656c)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/sock_map.c (c0d3848c)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (c0dde7cc)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
  - net/ipv4/tcp_bpf.c:tcp_bpf_reinit
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_stream_read
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
In net/core/skmsg.c (c000000000cf9a78)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/sock_map.c (c000000000d12d20)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (c000000000df3980)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
  - net/ipv4/tcp_bpf.c:tcp_bpf_reinit
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_stream_read
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
In net/core/skmsg.c (ffffffe00078ac9c)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/sock_map.c (ffffffe00079998e)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffe00082555e)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
  - net/ipv4/tcp_bpf.c:tcp_bpf_reinit
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_stream_read
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
In net/core/skmsg.c (ffffffff819082ec)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/sock_map.c (ffffffff8191956c)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b81f2)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
  - net/ipv4/tcp_bpf.c:tcp_bpf_reinit
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_stream_read
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
In net/core/skmsg.c (ffffffff818c20fc)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/sock_map.c (ffffffff818d331c)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974fe2)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
  - net/ipv4/tcp_bpf.c:tcp_bpf_reinit
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_stream_read
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
In net/core/skmsg.c (ffffffff8195931c)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/sock_map.c (ffffffff8196a6fc)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a22c72)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
  - net/ipv4/tcp_bpf.c:tcp_bpf_reinit
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_stream_read
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
In net/core/skmsg.c (ffffffff8197b664)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_data_ready
  - net/core/skmsg.c:sk_psock_strp_read
```
```
In net/core/sock_map.c (ffffffff8198cb6c)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2e04a)
Location: include/linux/skmsg.h:277
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_init
  - net/ipv4/tcp_bpf.c:tcp_bpf_reinit
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_stream_read
```
</details>
</li>
</ul>

## Differences
