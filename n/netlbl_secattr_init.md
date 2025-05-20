# Function: <code>netlbl_secattr_init</code>

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
In security/selinux/netlabel.c (ffffffff8135d482)
Location: include/net/netlabel.h:301
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
```
```
In security/smack/smack_lsm.c (ffffffff81360f36)
Location: include/net/netlabel.h:301
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffff81393a91)
Location: include/net/netlabel.h:361
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff813981de)
Location: include/net/netlabel.h:361
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffff813aa6b1)
Location: include/net/netlabel.h:361
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff813aedbe)
Location: include/net/netlabel.h:361
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffff813c109b)
Location: include/net/netlabel.h:361
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff813c5353)
Location: include/net/netlabel.h:361
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffff813e729b)
Location: include/net/netlabel.h:361
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff813eb423)
Location: include/net/netlabel.h:361
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffff81418204)
Location: include/net/netlabel.h:361
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff8141cd5c)
Location: include/net/netlabel.h:361
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffff8143478b)
Location: include/net/netlabel.h:361
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff81438693)
Location: include/net/netlabel.h:361
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffff8146223c)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff814662f6)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffff8147bfeb)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff814800d6)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffff814d163b)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff814d6733)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffff814eeb4b)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff814f0487)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
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
In security/selinux/netlabel.c (ffffffff814f58ab)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff814f7407)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
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
In security/selinux/netlabel.c (ffffffff815502ab)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff81551fa7)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
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
In security/selinux/netlabel.c (ffffffff815e9733)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff815eb997)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81699073)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff8169b5b7)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
**Symbols:**

```
ffffffff81698270-ffffffff81698280: netlbl_secattr_init.part.0 (STB_LOCAL)
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
In security/selinux/netlabel.c (ffffffff816d1523)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff816d3dc7)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
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
In security/selinux/netlabel.c (ffffffff8170db53)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff81711a75)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
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
In security/selinux/netlabel.c (ffff80001056cb70)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffff800010571874)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (c07203c0)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (c0724b08)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (c0000000006d10a8)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (c0000000006d864c)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffe0003c1546)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffe0003c59ce)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffff814745cb)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff814786b6)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffff81464feb)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff814690d6)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffff8147066b)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff81474756)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
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
In security/selinux/netlabel.c (ffffffff81487edb)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
```
In security/smack/smack_lsm.c (ffffffff8148c0a3)
Location: include/net/netlabel.h:347
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
</details>
</li>
</ul>

## Differences
