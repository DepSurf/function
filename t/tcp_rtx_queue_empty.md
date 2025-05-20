# Function: <code>tcp_rtx_queue_empty</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a48c6)
Location: include/net/tcp.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff818b182a)
Location: include/net/tcp.h:1618
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff818b753a)
Location: include/net/tcp.h:1618
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp.c (ffffffff818fa696)
Location: include/net/tcp.h:1634
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff818fd675)
Location: include/net/tcp.h:1634
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81906a7a)
Location: include/net/tcp.h:1634
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8190ceb5)
Location: include/net/tcp.h:1634
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp.c (ffffffff819285cd)
Location: include/net/tcp.h:1706
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff8192b775)
Location: include/net/tcp.h:1706
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81934d8d)
Location: include/net/tcp.h:1706
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8193b1c5)
Location: include/net/tcp.h:1706
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp.c (ffffffff8198b547)
Location: include/net/tcp.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff8198ea05)
Location: include/net/tcp.h:1746
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81998b5f)
Location: include/net/tcp.h:1746
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f592)
Location: include/net/tcp.h:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp.c (ffffffff819c1d8c)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff819c5975)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819cf68a)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819d6142)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp.c (ffffffff81aad54e)
Location: include/net/tcp.h:1806
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0855)
Location: include/net/tcp.h:1806
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81abbf3a)
Location: include/net/tcp.h:1806
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
In net/ipv4/tcp.c (ffffffff81ab4b5b)
Location: include/net/tcp.h:1820
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81abb895)
Location: include/net/tcp.h:1820
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ac74ba)
Location: include/net/tcp.h:1820
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
In net/ipv4/tcp.c (ffffffff81a9fcd3)
Location: include/net/tcp.h:1824
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6855)
Location: include/net/tcp.h:1824
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ab24dd)
Location: include/net/tcp.h:1824
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
In net/ipv4/tcp.c (ffffffff81b5ba8c)
Location: include/net/tcp.h:1817
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81b62c45)
Location: include/net/tcp.h:1817
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f36f)
Location: include/net/tcp.h:1817
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81c7aa45)
Location: include/net/tcp.h:1817
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b0f6)
Location: include/net/tcp.h:1817
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
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
In net/ipv4/tcp.c (ffffffff81ceac39)
Location: include/net/tcp.h:1873
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81cf19b5)
Location: include/net/tcp.h:1873
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81cfe9ee)
Location: include/net/tcp.h:1873
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81e1fa47)
Location: include/net/tcp.h:1873
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/pm_netlink.c (ffffffff81e31564)
Location: include/net/tcp.h:1873
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
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
In net/ipv4/tcp.c (ffffffff81eb32f5)
Location: include/net/tcp.h:1893
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81eb61e5)
Location: include/net/tcp.h:1893
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ec390e)
Location: include/net/tcp.h:1893
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ff6487)
Location: include/net/tcp.h:1893
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/pm_netlink.c (ffffffff82009b74)
Location: include/net/tcp.h:1893
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
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
In net/ipv4/tcp.c (ffffffff81f11a12)
Location: include/net/tcp.h:1906
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81f14605)
Location: include/net/tcp.h:1906
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81f21b4e)
Location: include/net/tcp.h:1906
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82072663)
Location: include/net/tcp.h:1906
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/pm_netlink.c (ffffffff82085e7e)
Location: include/net/tcp.h:1906
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
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
In net/ipv4/tcp.c (ffffffff81fd5cb0)
Location: include/net/tcp.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8ae5)
Location: include/net/tcp.h:2008
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81fe8fbe)
Location: include/net/tcp.h:2008
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/mptcp/protocol.c (ffffffff82149b45)
Location: include/net/tcp.h:2008
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_retrans
```
```
In net/mptcp/pm_netlink.c (ffffffff8215b02e)
Location: include/net/tcp.h:2008
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
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
In net/ipv4/tcp.c (ffff800010c74af8)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffff800010c77abc)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_output.c (ffff800010c82214)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffff800010c89168)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp.c (c0d831d4)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (c0d86824)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_output.c (c0d90c60)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_small_queue_check
```
```
In net/ipv4/tcp_timer.c (c0d981b0)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp.c (c000000000d7c034)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (c000000000d80d40)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d8d4a0)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_timer.c (c000000000d963bc)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp.c (ffffffe0007d7f6c)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffe0007db45e)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffe0007e4034)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea0dc)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp.c (ffffffff81961bfc)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff819657e5)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8196f4fa)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81975fb2)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp.c (ffffffff8191b6ec)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff8191f2d5)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81928fca)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8192fa72)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp.c (ffffffff819cc3cc)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff819cffb5)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819d9cca)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0782)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp.c (ffffffff819d5f5c)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_push
```
```
In net/ipv4/tcp_input.c (ffffffff819d9b45)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819e392a)
Location: include/net/tcp.h:1768
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea442)
Location: include/net/tcp.h:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
</details>
</li>
</ul>

## Differences
