# Function: <code>tcp_skb_can_collapse_to</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:820
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/net/tcp.h:820
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:820
Inline: True
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
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:837
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/net/tcp.h:837
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:837
Inline: True
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
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:889
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/net/tcp.h:889
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:889
Inline: True
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
In net/ipv4/tcp.c (0)
Location: include/net/tcp.h:891
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/net/tcp.h:891
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/net/tcp.h:891
Inline: True
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
In net/ipv4/tcp.c (ffffffff818fa464)
Location: include/net/tcp.h:909
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff818fe11b)
Location: include/net/tcp.h:909
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff8190ac23)
Location: include/net/tcp.h:909
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp.c (ffffffff819283a1)
Location: include/net/tcp.h:947
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff8192c235)
Location: include/net/tcp.h:947
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff81938ed1)
Location: include/net/tcp.h:947
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp.c (ffffffff8198b31d)
Location: include/net/tcp.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff8198f597)
Location: include/net/tcp.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff8199d114)
Location: include/net/tcp.h:948
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp.c (ffffffff819c1b8e)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819c62d7)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff819d3bd4)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp.c (ffffffff81aad3cc)
Location: include/net/tcp.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81ab59e6)
Location: include/net/tcp.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ac03af)
Location: include/net/tcp.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
```
In net/mptcp/protocol.c (ffffffff81baa6f4)
Location: include/net/tcp.h:980
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
In net/ipv4/tcp.c (ffffffff81ab479c)
Location: include/net/tcp.h:985
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_input.c (ffffffff81ac0d46)
Location: include/net/tcp.h:985
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81acbe0f)
Location: include/net/tcp.h:985
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
```
In net/mptcp/protocol.c (ffffffff81bba0d5)
Location: include/net/tcp.h:985
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/ipv4/tcp.c (ffffffff81a9f8ff)
Location: include/net/tcp.h:965
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_input.c (ffffffff81aabcf6)
Location: include/net/tcp.h:965
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ab704e)
Location: include/net/tcp.h:965
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
```
In net/mptcp/protocol.c (ffffffff81ba9485)
Location: include/net/tcp.h:965
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/ipv4/tcp.c (ffffffff81b5b6b8)
Location: include/net/tcp.h:958
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_input.c (ffffffff81b68136)
Location: include/net/tcp.h:958
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81b7423e)
Location: include/net/tcp.h:958
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
```
In net/mptcp/protocol.c (ffffffff81c78a56)
Location: include/net/tcp.h:958
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
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
In net/ipv4/tcp.c (ffffffff81cea862)
Location: include/net/tcp.h:973
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81cf72ad)
Location: include/net/tcp.h:973
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81d03713)
Location: include/net/tcp.h:973
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
```
In net/mptcp/protocol.c (ffffffff81e1f4dc)
Location: include/net/tcp.h:973
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
In net/ipv4/tcp.c (ffffffff81eae734)
Location: include/net/tcp.h:986
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81ebbd3d)
Location: include/net/tcp.h:986
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ec8653)
Location: include/net/tcp.h:986
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
```
In net/mptcp/protocol.c (ffffffff81ff6013)
Location: include/net/tcp.h:986
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
In net/ipv4/tcp.c (ffffffff81f0c7d9)
Location: include/net/tcp.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81f1a1c0)
Location: include/net/tcp.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81f27173)
Location: include/net/tcp.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
```
In net/mptcp/protocol.c (ffffffff8207212e)
Location: include/net/tcp.h:981
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
In net/ipv4/tcp.c (ffffffff81fd08be)
Location: include/net/tcp.h:1018
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81fde990)
Location: include/net/tcp.h:1018
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81febb63)
Location: include/net/tcp.h:1018
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
```
In net/mptcp/protocol.c (ffffffff8214610a)
Location: include/net/tcp.h:1018
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
In net/ipv4/tcp.c (ffff800010c749b4)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffff800010c79bbc)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffff800010c86600)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp.c (c0d83058)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (c0d8a1e8)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (c0d95ac8)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp.c (c000000000d7bd1c)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (c000000000d81d94)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (c000000000d92fec)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp.c (ffffffe0007d7dc6)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffe0007dc00a)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffe0007e7c18)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp.c (ffffffff819619fe)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff81966147)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff81973a44)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp.c (ffffffff8191b4ee)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff8191fc37)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff8192d514)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp.c (ffffffff819cc1ce)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819d0917)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff819de214)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
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
In net/ipv4/tcp.c (ffffffff819d5d5e)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_input.c (ffffffff819da4a7)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff819e7e94)
Location: include/net/tcp.h:969
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
```
</details>
</li>
</ul>

## Differences
