# Function: <code>sk_psock_data_ready</code>

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
In net/core/skmsg.c (ffffffff818e64b6)
Location: include/linux/skmsg.h:420
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffff819771ad)
Location: include/linux/skmsg.h:420
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
In net/core/skmsg.c (ffffffff81935e38)
Location: include/linux/skmsg.h:428
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e0cd9)
Location: include/linux/skmsg.h:428
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
In net/core/skmsg.c (ffffffff81968b4d)
Location: include/linux/skmsg.h:436
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a17d09)
Location: include/linux/skmsg.h:436
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
In net/core/skmsg.c (ffffffff81a3bd23)
Location: include/linux/skmsg.h:417
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b089af)
Location: include/linux/skmsg.h:417
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
In net/core/skmsg.c (ffffffff81a3e4c7)
Location: include/linux/skmsg.h:402
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b16da9)
Location: include/linux/skmsg.h:402
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
In net/core/skmsg.c (ffffffff81a4cc98)
Location: include/linux/skmsg.h:449
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b04caf)
Location: include/linux/skmsg.h:449
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
In net/core/skmsg.c (ffffffff81b06bb1)
Location: include/linux/skmsg.h:464
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc728f)
Location: include/linux/skmsg.h:464
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
In net/core/skmsg.c (ffffffff81c8b737)
Location: include/linux/skmsg.h:454
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5c6fe)
Location: include/linux/skmsg.h:454
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
In net/core/skmsg.c (ffffffff81e46ea7)
Location: include/linux/skmsg.h:456
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f26c7b)
Location: include/linux/skmsg.h:456
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
In net/core/skmsg.c (ffffffff81ea1e07)
Location: include/linux/skmsg.h:456
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f8693b)
Location: include/linux/skmsg.h:456
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
In net/core/skmsg.c (ffffffff81f643d7)
Location: include/linux/skmsg.h:462
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204df7a)
Location: include/linux/skmsg.h:462
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
In net/core/skmsg.c (ffff800010c0f99c)
Location: include/linux/skmsg.h:436
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd386c)
Location: include/linux/skmsg.h:436
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
In net/core/skmsg.c (c0d262e8)
Location: include/linux/skmsg.h:436
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (c0ddd7b0)
Location: include/linux/skmsg.h:436
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
In net/core/skmsg.c (c000000000cfa7d4)
Location: include/linux/skmsg.h:436
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (c000000000df2990)
Location: include/linux/skmsg.h:436
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
In net/core/skmsg.c (ffffffe00078b4d2)
Location: include/linux/skmsg.h:436
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824854)
Location: include/linux/skmsg.h:436
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
In net/core/skmsg.c (ffffffff81908b1d)
Location: include/linux/skmsg.h:436
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7399)
Location: include/linux/skmsg.h:436
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
In net/core/skmsg.c (ffffffff818c292d)
Location: include/linux/skmsg.h:436
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974189)
Location: include/linux/skmsg.h:436
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
In net/core/skmsg.c (ffffffff81959b4d)
Location: include/linux/skmsg.h:436
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a21e19)
Location: include/linux/skmsg.h:436
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
In net/core/skmsg.c (ffffffff8197bd6d)
Location: include/linux/skmsg.h:436
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2d1ca)
Location: include/linux/skmsg.h:436
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
</details>
</li>
</ul>

## Differences
