# Function: <code>tcp_rtx_and_write_queues_empty</code>

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
Location: include/net/tcp.h:1623
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff818b25ac)
Location: include/net/tcp.h:1623
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
In net/ipv4/tcp.c (ffffffff818fa696)
Location: include/net/tcp.h:1639
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff81907aa5)
Location: include/net/tcp.h:1639
Inline: True
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
Location: include/net/tcp.h:1711
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff81935d35)
Location: include/net/tcp.h:1711
Inline: True
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
Location: include/net/tcp.h:1751
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff8199a0c5)
Location: include/net/tcp.h:1751
Inline: True
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
Location: include/net/tcp.h:1773
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff819d0ad5)
Location: include/net/tcp.h:1773
Inline: True
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
Location: include/net/tcp.h:1811
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff81abdcb5)
Location: include/net/tcp.h:1811
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
Location: include/net/tcp.h:1825
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_output.c (ffffffff81ac9595)
Location: include/net/tcp.h:1825
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
Location: include/net/tcp.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_output.c (ffffffff81ab4445)
Location: include/net/tcp.h:1829
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
Location: include/net/tcp.h:1822
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_output.c (ffffffff81b71345)
Location: include/net/tcp.h:1822
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81c7aa45)
Location: include/net/tcp.h:1822
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
```
```
In net/mptcp/pm_netlink.c (ffffffff81c8b0f6)
Location: include/net/tcp.h:1822
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
Location: include/net/tcp.h:1878
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_output.c (ffffffff81d0084c)
Location: include/net/tcp.h:1878
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81e1fa47)
Location: include/net/tcp.h:1878
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/pm_netlink.c (ffffffff81e31564)
Location: include/net/tcp.h:1878
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
In net/ipv4/tcp.c (ffffffff81eaea0a)
Location: include/net/tcp.h:1898
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:tcp_build_frag
```
```
In net/ipv4/tcp_output.c (ffffffff81ec597c)
Location: include/net/tcp.h:1898
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ff6487)
Location: include/net/tcp.h:1898
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/pm_netlink.c (ffffffff82009b74)
Location: include/net/tcp.h:1898
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
In net/ipv4/tcp.c (ffffffff81f0c9df)
Location: include/net/tcp.h:1911
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81f23f58)
Location: include/net/tcp.h:1911
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82072663)
Location: include/net/tcp.h:1911
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
```
In net/mptcp/pm_netlink.c (ffffffff82085e7e)
Location: include/net/tcp.h:1911
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
In net/ipv4/tcp.c (ffffffff81fd0ac4)
Location: include/net/tcp.h:2013
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_output.c (ffffffff81fe8768)
Location: include/net/tcp.h:2013
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82149b45)
Location: include/net/tcp.h:2013
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_subflow_get_retrans
```
```
In net/mptcp/pm_netlink.c (ffffffff8215b02e)
Location: include/net/tcp.h:2013
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
Location: include/net/tcp.h:1773
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffff800010c83754)
Location: include/net/tcp.h:1773
Inline: True
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
Location: include/net/tcp.h:1773
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (c0d9293c)
Location: include/net/tcp.h:1773
Inline: True
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
Location: include/net/tcp.h:1773
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (c000000000d8efd0)
Location: include/net/tcp.h:1773
Inline: True
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
Location: include/net/tcp.h:1773
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffe0007e52cc)
Location: include/net/tcp.h:1773
Inline: True
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
Location: include/net/tcp.h:1773
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff81970945)
Location: include/net/tcp.h:1773
Inline: True
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
Location: include/net/tcp.h:1773
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff8192a415)
Location: include/net/tcp.h:1773
Inline: True
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
Location: include/net/tcp.h:1773
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff819db115)
Location: include/net/tcp.h:1773
Inline: True
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
Location: include/net/tcp.h:1773
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp.c:do_tcp_sendpages
```
```
In net/ipv4/tcp_output.c (ffffffff819e4d95)
Location: include/net/tcp.h:1773
Inline: True
```
</details>
</li>
</ul>

## Differences
