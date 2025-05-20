# Function: <code>sk_psock_queue_msg</code>

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
In net/core/skmsg.c (ffffffff818e649d)
Location: include/linux/skmsg.h:279
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffff8197718e)
Location: include/linux/skmsg.h:279
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
In net/core/skmsg.c (ffffffff81935e1d)
Location: include/linux/skmsg.h:279
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e0cb3)
Location: include/linux/skmsg.h:279
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
In net/core/skmsg.c (ffffffff81968b36)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a17ce3)
Location: include/linux/skmsg.h:282
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
In net/core/skmsg.c (ffffffff81a3bd09)
Location: include/linux/skmsg.h:287
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b08982)
Location: include/linux/skmsg.h:287
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
In net/core/skmsg.c (ffffffff81a3e4a6)
Location: include/linux/skmsg.h:287
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b16d7c)
Location: include/linux/skmsg.h:287
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
In net/core/skmsg.c (ffffffff81a4cc57)
Location: include/linux/skmsg.h:290
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b04c67)
Location: include/linux/skmsg.h:290
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
In net/core/skmsg.c (ffffffff81b06b62)
Location: include/linux/skmsg.h:320
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc7228)
Location: include/linux/skmsg.h:320
Inline: True
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
In net/core/skmsg.c (ffffffff81c8b6eb)
Location: include/linux/skmsg.h:308
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5c697)
Location: include/linux/skmsg.h:308
Inline: True
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
In net/core/skmsg.c (ffffffff81e46e5b)
Location: include/linux/skmsg.h:310
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f26c14)
Location: include/linux/skmsg.h:310
Inline: True
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
In net/core/skmsg.c (ffffffff81ea1dbb)
Location: include/linux/skmsg.h:310
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f868d4)
Location: include/linux/skmsg.h:310
Inline: True
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
In net/core/skmsg.c (ffffffff81f6438b)
Location: include/linux/skmsg.h:316
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204df13)
Location: include/linux/skmsg.h:316
Inline: True
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
In net/core/skmsg.c (ffff800010c0f990)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3858)
Location: include/linux/skmsg.h:282
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
In net/core/skmsg.c (c0d262e4)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (c0ddd798)
Location: include/linux/skmsg.h:282
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
In net/core/skmsg.c (c000000000cfa7c4)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (c000000000df297c)
Location: include/linux/skmsg.h:282
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
In net/core/skmsg.c (ffffffe00078b404)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824832)
Location: include/linux/skmsg.h:282
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
In net/core/skmsg.c (ffffffff81908b06)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7373)
Location: include/linux/skmsg.h:282
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
In net/core/skmsg.c (ffffffff818c2916)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974163)
Location: include/linux/skmsg.h:282
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
In net/core/skmsg.c (ffffffff81959b36)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a21df3)
Location: include/linux/skmsg.h:282
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
In net/core/skmsg.c (ffffffff8197bd56)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2d1a4)
Location: include/linux/skmsg.h:282
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
</details>
</li>
</ul>

## Differences
