# Function: <code>sk_msg_init</code>

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
In <code>4.15</code>: Absent ⚠️
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
In net/core/skmsg.c (ffffffff818e642c)
Location: include/linux/skmsg.h:168
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff819778c2)
Location: include/linux/skmsg.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In net/core/skmsg.c (ffffffff81935da8)
Location: include/linux/skmsg.h:168
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e13d9)
Location: include/linux/skmsg.h:168
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In net/core/skmsg.c (ffffffff81968ac8)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a1879b)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In net/core/skmsg.c (ffffffff81a3bc80)
Location: include/linux/skmsg.h:177
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b09494)
Location: include/linux/skmsg.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b22f16)
Location: include/linux/skmsg.h:177
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
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
In net/core/skmsg.c (ffffffff81a3f86d)
Location: include/linux/skmsg.h:177
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17cb4)
Location: include/linux/skmsg.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b31906)
Location: include/linux/skmsg.h:177
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
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
In net/core/skmsg.c (ffffffff81a4ea42)
Location: include/linux/skmsg.h:180
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b05886)
Location: include/linux/skmsg.h:180
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b1f636)
Location: include/linux/skmsg.h:180
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
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
In net/core/skmsg.c (ffffffff81b075ab)
Location: include/linux/skmsg.h:179
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc83e3)
Location: include/linux/skmsg.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81be4256)
Location: include/linux/skmsg.h:179
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
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
In net/core/skmsg.c (ffffffff81c8cd19)
Location: include/linux/skmsg.h:173
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5dcb2)
Location: include/linux/skmsg.h:173
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81d7b6d2)
Location: include/linux/skmsg.h:173
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
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
In net/core/skmsg.c (ffffffff81e4583f)
Location: include/linux/skmsg.h:175
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27962)
Location: include/linux/skmsg.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81f48762)
Location: include/linux/skmsg.h:175
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
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
In net/core/skmsg.c (ffffffff81ea0e4f)
Location: include/linux/skmsg.h:175
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f876ba)
Location: include/linux/skmsg.h:175
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81fa85d2)
Location: include/linux/skmsg.h:175
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
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
In net/core/skmsg.c (ffffffff81f634ff)
Location: include/linux/skmsg.h:181
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204ed3a)
Location: include/linux/skmsg.h:181
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff820758c2)
Location: include/linux/skmsg.h:181
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_sendmsg
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
In net/core/skmsg.c (ffff800010c0f918)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3f80)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In net/core/skmsg.c (c0d2625c)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (c0ddde70)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In net/core/skmsg.c (c000000000cfa744)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (c000000000df3420)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In net/core/skmsg.c (ffffffe00078b418)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824db2)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In net/core/skmsg.c (ffffffff81908a98)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7e2b)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In net/core/skmsg.c (ffffffff818c28a8)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974c1b)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In net/core/skmsg.c (ffffffff81959ac8)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a228ab)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
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
In net/core/skmsg.c (ffffffff8197bce8)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2dc5c)
Location: include/linux/skmsg.h:176
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
</ul>

## Differences
