# Function: <code>sk_wmem_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81768ef1)
Location: include/net/sock.h:1382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d6255)
Location: include/net/sock.h:1289
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81806253)
Location: include/net/sock.h:1345
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81826dbf)
Location: include/net/sock.h:1348
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a4cf5)
Location: include/net/sock.h:1352
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
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
In kernel/bpf/sockmap.c (ffffffff811cf110)
Location: include/net/sock.h:1367
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
```
```
In net/core/sock.c (ffffffff81877485)
Location: include/net/sock.h:1367
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc_sg
```
```
In net/ipv4/tcp.c (ffffffff818fa722)
Location: include/net/sock.h:1367
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
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
In net/core/skmsg.c (ffffffff818e60c4)
Location: include/net/sock.h:1405
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff819286fd)
Location: include/net/sock.h:1405
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_bpf.c (ffffffff81977105)
Location: include/net/sock.h:1405
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/core/skmsg.c (ffffffff81935804)
Location: include/net/sock.h:1408
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff8198b66e)
Location: include/net/sock.h:1408
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e0c34)
Location: include/net/sock.h:1408
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/core/skmsg.c (ffffffff81968686)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff819c1eb4)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a17c64)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/core/skmsg.c (ffffffff81a3c201)
Location: include/net/sock.h:1466
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81aad6cf)
Location: include/net/sock.h:1466
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0888c)
Location: include/net/sock.h:1466
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81baa9a9)
Location: include/net/sock.h:1466
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
In net/core/skmsg.c (ffffffff81a3e8c1)
Location: include/net/sock.h:1482
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81ab4a46)
Location: include/net/sock.h:1482
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b16c86)
Location: include/net/sock.h:1482
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81bbfc67)
Location: include/net/sock.h:1482
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_wmem_reserve
  - net/mptcp/protocol.c:__mptcp_wmem_reserve
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
In net/core/skmsg.c (ffffffff81a4cac1)
Location: include/net/sock.h:1498
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81a9fbfa)
Location: include/net/sock.h:1498
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b04b63)
Location: include/net/sock.h:1498
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81baf9cc)
Location: include/net/sock.h:1498
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
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
In net/core/skmsg.c (ffffffff81b05410)
Location: include/net/sock.h:1508
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81b5b9b3)
Location: include/net/sock.h:1508
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc70dd)
Location: include/net/sock.h:1508
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81c7d575)
Location: include/net/sock.h:1508
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
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
In net/core/skmsg.c (ffffffff81c8c771)
Location: include/net/sock.h:1581
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81ce751a)
Location: include/net/sock.h:1581
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5c50f)
Location: include/net/sock.h:1581
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81e22a2a)
Location: include/net/sock.h:1581
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/core/skmsg.c (ffffffff81e46a0d)
Location: include/net/sock.h:1627
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81eaacaa)
Location: include/net/sock.h:1627
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f26aad)
Location: include/net/sock.h:1627
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ffb71f)
Location: include/net/sock.h:1627
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/core/skmsg.c (ffffffff81ea2459)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81f0949a)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81f2283c)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f8676d)
Location: include/net/sock.h:1618
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82077aa5)
Location: include/net/sock.h:1618
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/core/skmsg.c (ffffffff81f64a52)
Location: include/net/sock.h:1593
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81fcd78a)
Location: include/net/sock.h:1593
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_downgrade_zcopy_pure
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81fe622c)
Location: include/net/sock.h:1593
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_clone_payload
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204ddac)
Location: include/net/sock.h:1593
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff8214cb14)
Location: include/net/sock.h:1593
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/core/skmsg.c (ffff800010c0f158)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffff800010c74c10)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3770)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/core/skmsg.c (c0d26c04)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (c0d83390)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_bpf.c (c0ddd67c)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/core/skmsg.c (c000000000cfa388)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (c000000000d7c19c)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_bpf.c (c000000000df287c)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/core/skmsg.c (ffffffe00078b176)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffe0007d807c)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824710)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/core/skmsg.c (ffffffff81908656)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff81961d24)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b72f4)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/core/skmsg.c (ffffffff818c2466)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff8191b814)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff819740e4)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/core/skmsg.c (ffffffff81959686)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff819cc4f4)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a21d74)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/core/skmsg.c (ffffffff8197b856)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp.c (ffffffff819d6084)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2d11f)
Location: include/net/sock.h:1418
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
</details>
</li>
</ul>

## Differences
