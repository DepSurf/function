# Function: <code>smack_sock</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c1636)
Location: security/smack/smack.h:387
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_connect
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
```
```
In security/smack/smack_netfilter.c (ffffffff813c979b)
Location: security/smack/smack.h:387
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
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
In security/smack/smack_lsm.c (ffffffff813e7926)
Location: security/smack/smack.h:387
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff813efc2b)
Location: security/smack/smack.h:387
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
</details>
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
In security/smack/smack_lsm.c (ffffffff81434fc5)
Location: security/smack/smack.h:387
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff8143d0ab)
Location: security/smack/smack.h:387
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
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
In security/smack/smack_lsm.c (ffffffff814628c5)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff8146acab)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
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
In security/smack/smack_lsm.c (ffffffff8147c675)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff81484a8b)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
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
In security/smack/smack_lsm.c (ffffffff814d2085)
Location: security/smack/smack.h:368
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff814dab7b)
Location: security/smack/smack.h:368
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
In security/smack/smack_lsm.c (ffffffff814ef565)
Location: security/smack/smack.h:361
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff814f7ffb)
Location: security/smack/smack.h:361
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
In security/smack/smack_lsm.c (ffffffff814f65f5)
Location: security/smack/smack.h:367
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff814fed5b)
Location: security/smack/smack.h:367
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
In security/smack/smack_lsm.c (ffffffff81551185)
Location: security/smack/smack.h:367
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff81559dab)
Location: security/smack/smack.h:367
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
In security/smack/smack_lsm.c (ffffffff815ea835)
Location: security/smack/smack.h:367
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_from_netlbl
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff815f4a9b)
Location: security/smack/smack.h:367
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ip_output
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
In security/smack/smack_lsm.c (ffffffff8169a425)
Location: security/smack/smack.h:358
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_from_netlbl
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff816a553b)
Location: security/smack/smack.h:358
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ip_output
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
In security/smack/smack_lsm.c (ffffffff816d2c05)
Location: security/smack/smack.h:359
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_from_netlbl
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff816ddf1b)
Location: security/smack/smack.h:359
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ip_output
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
In security/smack/smack_lsm.c (ffffffff817113d5)
Location: security/smack/smack.h:358
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_from_netlbl
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smk_ipv4_check
  - security/smack/smack_lsm.c:smack_netlbl_add
  - security/smack/smack_lsm.c:smack_sk_clone_security
  - security/smack/smack_lsm.c:smack_sk_clone_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff8171ab36)
Location: security/smack/smack.h:358
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ip_output
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
In security/smack/smack_lsm.c (ffff80001056d4cc)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffff800010576ed8)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
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
In security/smack/smack_lsm.c (c0720be4)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (c0729cd0)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
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
In security/smack/smack_lsm.c (c0000000006d1dc8)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (c0000000006e0398)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
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
In security/smack/smack_lsm.c (ffffffe0003c1d14)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffe0003c9456)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv6_output
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
In security/smack/smack_lsm.c (ffffffff81474c55)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff8147d06b)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
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
In security/smack/smack_lsm.c (ffffffff81465675)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff8146da8b)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
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
In security/smack/smack_lsm.c (ffffffff81470cf5)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff8147910b)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
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
In security/smack/smack_lsm.c (ffffffff814885b5)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_csk_clone
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_may_send
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_unix_stream_connect
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_socket_socketpair
  - security/smack/smack_lsm.c:smack_inode_setsecurity
  - security/smack/smack_lsm.c:smack_netlabel_send
  - security/smack/smack_lsm.c:smack_netlabel
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_inode_getsecurity
```
```
In security/smack/smack_netfilter.c (ffffffff81490bbb)
Location: security/smack/smack.h:375
Inline: True
Inline callers:
  - security/smack/smack_netfilter.c:smack_ipv4_output
  - security/smack/smack_netfilter.c:smack_ipv6_output
```
</details>
</li>
</ul>

## Differences
