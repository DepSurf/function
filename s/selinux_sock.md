# Function: <code>selinux_sock</code>

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
In security/selinux/hooks.c (ffffffff813a7881)
Location: security/selinux/include/objsec.h:225
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:sock_has_perm
```
```
In security/selinux/netlabel.c (ffffffff813c1163)
Location: security/selinux/include/objsec.h:225
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff813cd051)
Location: security/selinux/include/objsec.h:229
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:sock_has_perm
```
```
In security/selinux/netlabel.c (ffffffff813e7373)
Location: security/selinux/include/objsec.h:229
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff81417223)
Location: security/selinux/include/objsec.h:191
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:sock_has_perm
```
```
In security/selinux/netlabel.c (ffffffff8143489e)
Location: security/selinux/include/objsec.h:191
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff81444df3)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:sock_has_perm
```
```
In security/selinux/netlabel.c (ffffffff8146234f)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff8145e963)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:sock_has_perm
```
```
In security/selinux/netlabel.c (ffffffff8147c0ff)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff814b1a5e)
Location: security/selinux/include/objsec.h:192
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In security/selinux/netlabel.c (ffffffff814d1725)
Location: security/selinux/include/objsec.h:192
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff814cee4e)
Location: security/selinux/include/objsec.h:191
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In security/selinux/netlabel.c (ffffffff814eec35)
Location: security/selinux/include/objsec.h:191
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff814d564e)
Location: security/selinux/include/objsec.h:197
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In security/selinux/netlabel.c (ffffffff814f5995)
Location: security/selinux/include/objsec.h:197
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff8152e28e)
Location: security/selinux/include/objsec.h:197
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In security/selinux/netlabel.c (ffffffff81550395)
Location: security/selinux/include/objsec.h:197
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff815c4ea5)
Location: security/selinux/include/objsec.h:197
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_output
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_established
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In security/selinux/netlabel.c (ffffffff815e9815)
Location: security/selinux/include/objsec.h:197
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff816719d5)
Location: security/selinux/include/objsec.h:197
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_output
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_established
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In security/selinux/netlabel.c (ffffffff81699165)
Location: security/selinux/include/objsec.h:197
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff816aa1b5)
Location: security/selinux/include/objsec.h:197
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_output
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_established
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_shutdown
  - security/selinux/hooks.c:selinux_socket_getsockopt
  - security/selinux/hooks.c:selinux_socket_getsockname
  - security/selinux/hooks.c:selinux_socket_recvmsg
  - security/selinux/hooks.c:selinux_socket_sendmsg
  - security/selinux/hooks.c:selinux_socket_listen
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
```
```
In security/selinux/netlabel.c (ffffffff816d1615)
Location: security/selinux/include/objsec.h:197
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff816e6fb5)
Location: security/selinux/include/objsec.h:205
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_ip_output
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_established
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sctp_process_new_assoc
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:sock_has_perm
```
```
In security/selinux/netlabel.c (ffffffff8170dc45)
Location: security/selinux/include/objsec.h:205
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffff80001054ba74)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:sock_has_perm
```
```
In security/selinux/netlabel.c (ffff80001056ccb8)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (c0701dd8)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_connect_helper
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:sock_has_perm
```
```
In security/selinux/netlabel.c (c0720514)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (c0000000006a3f74)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_connect_helper
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:sock_has_perm
```
```
In security/selinux/netlabel.c (c0000000006d1278)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffe0003a63f0)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_connect_helper
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:sock_has_perm
```
```
In security/selinux/netlabel.c (ffffffe0003c1672)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff81456f43)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:sock_has_perm
```
```
In security/selinux/netlabel.c (ffffffff814746df)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff81447983)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:sock_has_perm
```
```
In security/selinux/netlabel.c (ffffffff814650ff)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff81452fe3)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:sock_has_perm
```
```
In security/selinux/netlabel.c (ffffffff8147077f)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
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
In security/selinux/hooks.c (ffffffff8146aae3)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_ip_postroute_compat
  - security/selinux/hooks.c:selinux_tun_dev_attach
  - security/selinux/hooks.c:selinux_inet_conn_established
  - security/selinux/hooks.c:selinux_inet_csk_clone
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_sk_clone
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_sock_graft
  - security/selinux/hooks.c:selinux_sk_getsecid
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_clone_security
  - security/selinux/hooks.c:selinux_sk_free_security
  - security/selinux/hooks.c:selinux_sk_alloc_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_sock_rcv_skb_compat
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_may_send
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_socketpair
  - security/selinux/hooks.c:selinux_socket_post_create
  - security/selinux/hooks.c:sock_has_perm
```
```
In security/selinux/netlabel.c (ffffffff81487fef)
Location: security/selinux/include/objsec.h:188
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_socket_post_create
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_sk_clone
  - security/selinux/netlabel.c:selinux_netlbl_inet_csk_clone
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
</details>
</li>
</ul>

## Differences
