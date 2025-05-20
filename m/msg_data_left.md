# Function: <code>msg_data_left</code>

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
In net/socket.c (0)
Location: include/linux/socket.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/socket.h:142
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/socket.h:142
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
In net/socket.c (0)
Location: include/linux/socket.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/socket.h:142
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/socket.h:142
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
In net/socket.c (0)
Location: include/linux/socket.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/socket.h:142
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/socket.h:142
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
In net/socket.c (0)
Location: include/linux/socket.h:142
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/socket.h:142
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/socket.h:142
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
In net/socket.c (0)
Location: include/linux/socket.h:143
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/socket.h:143
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818a4c47)
Location: include/linux/socket.h:143
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In kernel/bpf/sockmap.c (ffffffff811cfa89)
Location: include/linux/socket.h:143
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
```
```
In net/socket.c (ffffffff8187384f)
Location: include/linux/socket.h:143
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:___sys_sendmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffff81884068)
Location: include/linux/socket.h:143
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff818fa50a)
Location: include/linux/socket.h:143
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
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
In net/socket.c (ffffffff8189419f)
Location: include/linux/socket.h:143
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:___sys_sendmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffff818a50c9)
Location: include/linux/socket.h:143
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff81928444)
Location: include/linux/socket.h:143
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff819779e6)
Location: include/linux/socket.h:143
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/socket.c (ffffffff818de50b)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffff818efc4a)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff8198b328)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e14dd)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/socket.c (ffffffff8191060b)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffff81921c6a)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff819c1b99)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a1829d)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/socket.c (ffffffff819df921)
Location: include/linux/socket.h:157
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffff819f598a)
Location: include/linux/socket.h:157
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff81aad3d7)
Location: include/linux/socket.h:157
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0960c)
Location: include/linux/socket.h:157
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81bad170)
Location: include/linux/socket.h:157
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/socket.c (ffffffff819df126)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffff819f543a)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff81ab47a7)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17786)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81bbfb38)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/socket.c (ffffffff819c502b)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffff819db5da)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff81a9f90a)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b05364)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81baf71c)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/socket.c (ffffffff81a7455b)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffff81a8ae4a)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff81b5b6c3)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc7c6e)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81c7d3cd)
Location: include/linux/socket.h:158
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/socket.c (ffffffff81be731d)
Location: include/linux/socket.h:162
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffff81c004ab)
Location: include/linux/socket.h:162
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff81cea86c)
Location: include/linux/socket.h:162
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5d22e)
Location: include/linux/socket.h:162
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81e22a19)
Location: include/linux/socket.h:162
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/socket.c (ffffffff81d933cd)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffff81daf8db)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff81eae73f)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f2802e)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff81ffb70e)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/socket.c (ffffffff81e01ef6)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:sock_write_iter
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:kernel_sendmsg
  - net/socket.c:kernel_sendmsg
```
```
In net/core/skbuff.c (ffffffff81e10c5c)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/core/skbuff.c:sendmsg_locked
```
```
In net/core/datagram.c (ffffffff81e1fb4b)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff81f0c7e5)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f874b2)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff82077a94)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/socket.c (ffffffff81ebe8b6)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
  - net/socket.c:sock_sendmsg
```
```
In net/core/skbuff.c (ffffffff81ecd78c)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/core/skbuff.c:sendmsg_locked
```
```
In net/core/datagram.c (ffffffff81edd1fb)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff81fd08ca)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204eb32)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/mptcp/protocol.c (ffffffff8214cb03)
Location: include/linux/socket.h:170
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/socket.c (ffff800010ba8800)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffff800010bbc2f4)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffff800010c749bc)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd4098)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/socket.c (c0cc7248)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (c0cd875c)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (c0d83064)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (c0dddf74)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/socket.c (c000000000c7cf3c)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (c000000000c955d0)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (c000000000d7bd28)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (c000000000df3560)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/socket.c (ffffffe00073bfe8)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffe00074b04a)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffe0007d7dd0)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824e86)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/socket.c (ffffffff818b060b)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffff818c1c6a)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff81961a09)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b792d)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/socket.c (ffffffff8186a55b)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffff8187bbaa)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff8191b4f9)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff8197471d)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/socket.c (ffffffff8190160b)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffff81912c6a)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff819cc1d9)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a223ad)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
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
In net/socket.c (ffffffff819225f4)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:sock_recvmsg
  - net/socket.c:kernel_sendmsg_locked
  - net/socket.c:sock_sendmsg
```
```
In net/core/datagram.c (ffffffff81933dea)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/core/datagram.c:skb_copy_and_csum_datagram_msg
```
```
In net/ipv4/tcp.c (ffffffff819d5d69)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2d781)
Location: include/linux/socket.h:144
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
</ul>

## Differences
