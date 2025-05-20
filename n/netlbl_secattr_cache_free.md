# Function: <code>netlbl_secattr_cache_free</code>

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
In security/selinux/netlabel.c (ffffffff8135d30d)
Location: include/net/netlabel.h:250
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In security/smack/smack_lsm.c (ffffffff81360fc5)
Location: include/net/netlabel.h:250
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817ad158)
Location: include/net/netlabel.h:250
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff81393b10)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff813983e0)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181a138)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff8186f428)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff813aa730)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff813aefc0)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184b9f8)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff818a2398)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff813c111a)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff813c553d)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8186f408)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff818c8a18)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff813e731a)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff813eb60d)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818efd88)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff8194bfe8)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff81418283)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff8141cf3d)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819466c8)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff819a5338)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff8143480a)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff81438867)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81978228)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff819dbdc8)
Location: include/net/netlabel.h:310
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff814622bb)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff814664c6)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e1d19)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff81a4aa49)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff8147c06a)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff814802a6)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a18d09)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff81a81619)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff814d16ba)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff814d691f)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b09ec9)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff81b7c249)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff814eebca)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff814f0543)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b18289)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff81b8b289)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff814f592a)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff814f74c3)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b05fd9)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff81b7a0d9)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff8155032a)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff81552063)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc8cc9)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff81c44d99)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff815e97b2)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff815eba6a)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5e468)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff81de3df8)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff816990f2)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff8169b68a)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f28b68)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff81fb64d8)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff816d15a2)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff816d3e9a)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f886d8)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff82016be8)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff8170dbd2)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff81711b74)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8204fd98)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff820e5b88)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffff80001056cbe8)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffff800010571a08)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd4970)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffff800010d4cd70)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (c0720464)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (c0724cb4)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (c0dde980)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (c0e4e040)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (c0000000006d1164)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (c0000000006d8868)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (c000000000df3bf8)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (c000000000e83728)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffe0003c15c8)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffe0003c5b56)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffe000825738)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffe000885a68)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff8147464a)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff81478886)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b8399)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff81a20ca9)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff8146506a)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff814692a6)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81975189)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff819dda69)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff814706ea)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff81474926)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a22e19)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff81a8b729)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
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
In security/selinux/netlabel.c (ffffffff81487f5a)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffff8148c25a)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2e1f9)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv6/calipso.c (ffffffff81a98239)
Location: include/net/netlabel.h:296
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_entry_free
```
</details>
</li>
</ul>

## Differences
