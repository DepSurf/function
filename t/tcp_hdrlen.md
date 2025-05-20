# Function: <code>tcp_hdrlen</code>

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
In net/core/skbuff.c (ffffffff8170539a)
Location: include/linux/tcp.h:32
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/dev.c (ffffffff8171ce8b)
Location: include/linux/tcp.h:32
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff817340cd)
Location: include/linux/tcp.h:32
Inline: True
Inline callers:
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_start
```
```
In net/ipv4/tcp_input.c (ffffffff8176e114)
Location: include/linux/tcp.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d0ec)
Location: include/linux/tcp.h:32
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81782aa0)
Location: include/linux/tcp.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
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
In net/core/skbuff.c (ffffffff8176bf6c)
Location: include/linux/tcp.h:37
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/dev.c (ffffffff817855d0)
Location: include/linux/tcp.h:37
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff8179fd1c)
Location: include/linux/tcp.h:37
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff817dc531)
Location: include/linux/tcp.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ec048)
Location: include/linux/tcp.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ec781)
Location: include/linux/tcp.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff817efc27)
Location: include/linux/tcp.h:37
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81860bf0)
Location: include/linux/tcp.h:37
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff8179914c)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/dev.c (ffffffff817b2be0)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff817ce6ec)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff8180c5ff)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c9d0)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181d071)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81820637)
Location: include/linux/tcp.h:38
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81892bbc)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff817b7722)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/dev.c (ffffffff817d03ef)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/tso.c (ffffffff817edb9c)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff8182c53b)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183d1c5)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d88d)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81840b47)
Location: include/linux/tcp.h:38
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b91a9)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff8182fde2)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff81869ddc)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff818ab40e)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc9b0)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bcf9d)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c02b7)
Location: include/linux/tcp.h:38
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193c0f5)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff8187a462)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff818b9aa9)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff8190085e)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819124ef)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912dfe)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81915e1c)
Location: include/linux/tcp.h:38
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819954e6)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff8189b072)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff818e0869)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff8192ed24)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940cc9)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819415be)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819445c9)
Location: include/linux/tcp.h:38
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbdcb)
Location: include/linux/tcp.h:38
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff818e5752)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff8192eef9)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff8198deeb)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a52a3)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5bb8)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a8bb9)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a8be)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff819178a2)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff81961169)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff819c4abb)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819dbf99)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc978)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819df859)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a71461)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff819e9ee2)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff81a3467c)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff81aaff77)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac90dc)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9a48)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acccfb)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6ad6a)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff819e9c82)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/filter.c (ffffffff81a2c6ea)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/core/tso.c (ffffffff81a36a49)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/tcp_input.c (ffffffff81abafc1)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81ac75a3)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad507c)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad5998)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad8cfb)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b797fd)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff819cfdc4)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/filter.c (ffffffff81a13c9a)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/core/tso.c (ffffffff81a1dbc4)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/tcp_input.c (ffffffff81aa5f81)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81ab25c2)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac00fe)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac09f7)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3d6a)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b68317)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff81a7f7f4)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/filter.c (ffffffff81ac575a)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/core/tso.c (ffffffff81ad1664)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/tcp_input.c (ffffffff81b62361)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f462)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7dd6e)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7e3b7)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b823fa)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c30017)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff81bf3c43)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/filter.c (ffffffff81c4128f)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/core/tso.c (ffffffff81c4ef69)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/tcp_input.c (ffffffff81cf15f1)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81cfeb12)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0dd7f)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e335)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d128fa)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd3c8)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff81da19a3)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/filter.c (ffffffff81df69ef)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/core/tso.c (ffffffff81e04019)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ipv4/tcp_input.c (ffffffff81eb5df1)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3a42)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed372b)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed3de5)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed873a)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e4ae)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/filter.c (ffffffff81e6869f)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/core/tso.c (ffffffff81e768b8)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/gso.c (ffffffff81e7d463)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_transport_seglen
```
```
In net/ipv4/tcp_input.c (ffffffff81f14211)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81f21c82)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f32437)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f32dd9)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f3784a)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffef54)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/filter.c (ffffffff81f2786f)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/core/tso.c (ffffffff81f3687b)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/gso.c (ffffffff81f3e3e3)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/gso.c:skb_gso_transport_seglen
```
```
In net/ipv4/tcp_input.c (ffffffff81fd86f1)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5c22)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff8402)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8f29)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffd91a)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cdc91)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109eb5ec)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
```
```
In net/core/skbuff.c (ffff800010bb0c44)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffff800010c04a3c)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffff800010c7abb4)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8f244)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f8dc)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c933d4)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39868)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In drivers/net/ethernet/freescale/fec_main.c (c0acd8e8)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
```
```
In net/core/skbuff.c (c0ccdfcc)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (c0d1dea0)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (c0d88234)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (c0d9e184)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (c0d9e99c)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (c0da1bcc)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (c0e3c378)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (c000000000c86e58)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (c000000000cee9e8)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (c000000000d7f930)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9dec8)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e8f4)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (c000000000da3610)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6cf48)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffe000741df6)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffe000783626)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffe0007de5b2)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ef3d2)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efc04)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2914)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876af8)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff818b78a2)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff81901139)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff8196492b)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197be09)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c7e8)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197f6c9)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10af1)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff818717f2)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff818baf69)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff8191e41b)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819358c9)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819362a8)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81939189)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd8b1)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff819088a2)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff81952169)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff819cf0fb)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e65d9)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6fb8)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819e9e99)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7b571)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
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
In net/core/skbuff.c (ffffffff81929952)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_gso_transport_seglen
```
```
In net/core/tso.c (ffffffff81973ba9)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
  - net/core/tso.c:tso_build_hdr
  - net/core/tso.c:tso_build_hdr
```
```
In net/ipv4/tcp_input.c (ffffffff819d8c8b)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819f0299)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0c88)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f3cc9)
Location: include/linux/tcp.h:34
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87db1)
Location: include/linux/tcp.h:34
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
</details>
</li>
</ul>

## Differences
