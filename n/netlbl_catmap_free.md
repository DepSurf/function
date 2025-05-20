# Function: <code>netlbl_catmap_free</code>

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
In security/selinux/ss/ebitmap.c (ffffffff8134d839)
Location: include/net/netlabel.h:282
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff8135d2e9)
Location: include/net/netlabel.h:282
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
In security/smack/smack_lsm.c (ffffffff81360f75)
Location: include/net/netlabel.h:282
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffff81362b63)
Location: include/net/netlabel.h:282
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffffffff813657a0)
Location: include/net/netlabel.h:282
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff817aeda3)
Location: include/net/netlabel.h:282
Inline: True
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
In security/selinux/ss/ebitmap.c (ffffffff81383819)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff81393ae5)
Location: include/net/netlabel.h:342
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
In security/smack/smack_lsm.c (ffffffff81398234)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffff81398d21)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffffffff8139ab30)
Location: include/net/netlabel.h:342
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8181bb30)
Location: include/net/netlabel.h:342
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81870998)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff8139a299)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff813aa705)
Location: include/net/netlabel.h:342
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
In security/smack/smack_lsm.c (ffffffff813aee14)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffff813af901)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffffffff813b1820)
Location: include/net/netlabel.h:342
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8184d3f0)
Location: include/net/netlabel.h:342
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff818a3908)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff813b08d7)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff813c10ed)
Location: include/net/netlabel.h:342
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
In security/smack/smack_lsm.c (ffffffff813c53a9)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffff813c64d4)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffffffff813c80e0)
Location: include/net/netlabel.h:342
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81870e5a)
Location: include/net/netlabel.h:342
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff818c9ee6)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff813d6977)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff813e72ed)
Location: include/net/netlabel.h:342
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
In security/smack/smack_lsm.c (ffffffff813eb479)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffff813ec7c4)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffffffff813ee570)
Location: include/net/netlabel.h:342
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f1846)
Location: include/net/netlabel.h:342
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff8194d5d1)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff81406f89)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff81418256)
Location: include/net/netlabel.h:342
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
In security/smack/smack_lsm.c (ffffffff8141cdb2)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffff8141d600)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffffffff8141f63f)
Location: include/net/netlabel.h:342
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81948166)
Location: include/net/netlabel.h:342
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff819a5d5f)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff81422ad9)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff814347dd)
Location: include/net/netlabel.h:342
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
In security/smack/smack_lsm.c (ffffffff814386e9)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffff81439bf0)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffffffff8143c30f)
Location: include/net/netlabel.h:342
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81979e47)
Location: include/net/netlabel.h:342
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff819dcf29)
Location: include/net/netlabel.h:342
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff81450769)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff81462290)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffff8146634c)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffff814677a5)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffffffff81469ec3)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e3b2f)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81a4bb80)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff8146a549)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff8147c03f)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffff8148012c)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffff81481585)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffffffff81483ca3)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a1ab1f)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81a82750)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff814be919)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff814d168f)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffff814d6789)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffff814d76b2)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_import_entry
```
```
In security/smack/smackfs.c (ffffffff814d994d)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0a4f8)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_parsetag_rng
  - net/ipv4/cipso_ipv4.c:cipso_v4_parsetag_rbm
```
```
In net/ipv6/calipso.c (ffffffff81b7d663)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff814dc339)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff814eeb9f)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffff814f04ea)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/smack/smack_access.c (ffffffff814f4ae4)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/smack/smackfs.c (ffffffff814f6edd)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b188b8)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_parsetag_rng
  - net/ipv4/cipso_ipv4.c:cipso_v4_parsetag_rbm
```
```
In net/ipv6/calipso.c (ffffffff81b8c78b)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff814e2c79)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff814f58ff)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffff814f746a)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/smack/smack_access.c (ffffffff814fba56)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/smack/smackfs.c (ffffffff814fdb26)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b064a5)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_parsetag_rbm
```
```
In net/ipv6/calipso.c (ffffffff81b7b8cb)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff8153be67)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff815502ff)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffff8155200a)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/smack/smack_access.c (ffffffff815566c6)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/smack/smackfs.c (ffffffff8155888a)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc9195)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_parsetag_rbm
```
```
In net/ipv6/calipso.c (ffffffff81c4622b)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff815d3727)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff815e9787)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffff815eba05)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/smack/smack_access.c (ffffffff815f0ab1)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/smack/smackfs.c (ffffffff815f2a43)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d601c6)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81de5654)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff816817a7)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff816990c7)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffff8169b625)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/smack/smack_access.c (ffffffff816a0ee1)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/smack/smackfs.c (ffffffff816a32a3)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f2a93f)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81fb7e44)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff816b9967)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff816d1577)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffff816d3e35)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/smack/smack_access.c (ffffffff816d981e)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/smack/smackfs.c (ffffffff816dc0f0)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f8a61a)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff820185d4)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff816f63f7)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff8170dba7)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffff81711acf)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_from_netlbl
```
```
In security/smack/smack_access.c (ffffffff81716299)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/smack/smackfs.c (ffffffff8171939e)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82051d3a)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff820e75a4)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffff800010559140)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffff80001056cbc0)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffff8000105718b0)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffff800010572f14)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffff800010575a78)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd6b84)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv6/calipso.c (ffff800010d4eaf0)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (c070d9ec)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (c0720428)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (c0724b68)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (c07260c4)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (c0728a54)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (c0de0914)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv6/calipso.c (c0e4f37c)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (c0000000006b70f0)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (c0000000006d1100)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (c0000000006d86ac)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (c0000000006db0f4)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (c0000000006ded80)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (c000000000df67a4)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv6/calipso.c (c000000000e85390)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffe0003b027a)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffe0003c15aa)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffe0003c5a1e)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffe0003c6466)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffffffe0003c89c6)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffe00082752c)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv6/calipso.c (ffffffe0008871b0)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff81462b29)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff8147461f)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffff8147870c)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffff81479b65)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffffffff8147c283)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819ba1af)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81a21de0)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff81453559)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff8146503f)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffff8146912c)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffff8146a585)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffffffff8146cca3)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81976f9f)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff819deba0)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff8145ebc9)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff814706bf)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffff814747ac)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffff81475c05)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffffffff81478323)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a24c2f)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81a8c860)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
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
In security/selinux/ss/ebitmap.c (ffffffff814763d9)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
  - security/selinux/ss/ebitmap.c:ebitmap_netlbl_export
```
```
In security/selinux/netlabel.c (ffffffff81487f2f)
Location: include/net/netlabel.h:328
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
In security/smack/smack_lsm.c (ffffffff8148c0f9)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/smack/smack_access.c (ffffffff8148d655)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_netlbl_mls
```
```
In security/smack/smackfs.c (ffffffff8148fdd3)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a300a8)
Location: include/net/netlabel.h:328
Inline: True
```
```
In net/ipv6/calipso.c (ffffffff81a99600)
Location: include/net/netlabel.h:328
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_opt_getattr
```
</details>
</li>
</ul>

## Differences
