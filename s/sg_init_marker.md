# Function: <code>sg_init_marker</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811cf835)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendpage
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
```
```
In lib/scatterlist.c (ffffffff814c3fa8)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
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
In lib/scatterlist.c (ffffffff814d86a8)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skmsg.c (ffffffff818e642c)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff819778d4)
Location: include/linux/scatterlist.h:248
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
In lib/scatterlist.c (ffffffff81504418)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skmsg.c (ffffffff81935da8)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e13f1)
Location: include/linux/scatterlist.h:248
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
In lib/scatterlist.c (ffffffff81522428)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skmsg.c (ffffffff81968ac8)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a187b3)
Location: include/linux/scatterlist.h:248
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
In lib/scatterlist.c (ffffffff81586247)
Location: include/linux/scatterlist.h:262
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In net/core/skmsg.c (ffffffff81a3bc8f)
Location: include/linux/scatterlist.h:262
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_ingress
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b094ac)
Location: include/linux/scatterlist.h:262
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b22f35)
Location: include/linux/scatterlist.h:262
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
In lib/scatterlist.c (ffffffff815a3327)
Location: include/linux/scatterlist.h:261
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In net/core/skmsg.c (ffffffff81a3f87a)
Location: include/linux/scatterlist.h:261
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17ccc)
Location: include/linux/scatterlist.h:261
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b31925)
Location: include/linux/scatterlist.h:261
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
In lib/scatterlist.c (ffffffff815aa6e8)
Location: include/linux/scatterlist.h:261
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In net/core/skmsg.c (ffffffff81a4ea4f)
Location: include/linux/scatterlist.h:261
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0589e)
Location: include/linux/scatterlist.h:261
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81b1f655)
Location: include/linux/scatterlist.h:261
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
In lib/scatterlist.c (ffffffff81613978)
Location: include/linux/scatterlist.h:267
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In net/core/skmsg.c (ffffffff81b075b8)
Location: include/linux/scatterlist.h:267
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc83fb)
Location: include/linux/scatterlist.h:267
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81be4275)
Location: include/linux/scatterlist.h:267
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
In lib/scatterlist.c (ffffffff816df018)
Location: include/linux/scatterlist.h:284
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skmsg.c (ffffffff81c8cd26)
Location: include/linux/scatterlist.h:284
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5dcc4)
Location: include/linux/scatterlist.h:284
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81d7b707)
Location: include/linux/scatterlist.h:284
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
In lib/scatterlist.c (ffffffff817cf208)
Location: include/linux/scatterlist.h:353
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skmsg.c (ffffffff81e459b7)
Location: include/linux/scatterlist.h:353
Inline: True
Inline callers:
  - net/core/skmsg.c:alloc_sk_msg
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27974)
Location: include/linux/scatterlist.h:353
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81f48797)
Location: include/linux/scatterlist.h:353
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
In lib/scatterlist.c (ffffffff8180d6b8)
Location: include/linux/scatterlist.h:413
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skmsg.c (ffffffff81ea0fc7)
Location: include/linux/scatterlist.h:413
Inline: True
Inline callers:
  - net/core/skmsg.c:alloc_sk_msg
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f876d6)
Location: include/linux/scatterlist.h:413
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff81fa8607)
Location: include/linux/scatterlist.h:413
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
In lib/scatterlist.c (ffffffff81853368)
Location: include/linux/scatterlist.h:413
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skmsg.c (ffffffff81f636a6)
Location: include/linux/scatterlist.h:413
Inline: True
Inline callers:
  - net/core/skmsg.c:alloc_sk_msg
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204ed56)
Location: include/linux/scatterlist.h:413
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
```
In net/xfrm/espintcp.c (ffffffff820758f7)
Location: include/linux/scatterlist.h:413
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
In lib/scatterlist.c (ffff80001062c0b4)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skmsg.c (ffff800010c0f928)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3f90)
Location: include/linux/scatterlist.h:248
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
In lib/scatterlist.c (c07d2aa8)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skmsg.c (c0d2626c)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (c0ddde80)
Location: include/linux/scatterlist.h:248
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
In lib/scatterlist.c (c0000000007ce9bc)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skmsg.c (c000000000cfa758)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (c000000000df3434)
Location: include/linux/scatterlist.h:248
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
In lib/scatterlist.c (ffffffe00045c2d6)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_one
```
```
In net/core/skmsg.c (ffffffe00078b418)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824dc4)
Location: include/linux/scatterlist.h:248
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
In lib/scatterlist.c (ffffffff8151aa08)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skmsg.c (ffffffff81908a98)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7e43)
Location: include/linux/scatterlist.h:248
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
In lib/scatterlist.c (ffffffff8150acf8)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skmsg.c (ffffffff818c28a8)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974c33)
Location: include/linux/scatterlist.h:248
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
In lib/scatterlist.c (ffffffff81516a98)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skmsg.c (ffffffff81959ac8)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a228c3)
Location: include/linux/scatterlist.h:248
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
In lib/scatterlist.c (ffffffff81530228)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_init_table
```
```
In net/core/skmsg.c (ffffffff8197bce8)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:__sk_msg_free
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2dc74)
Location: include/linux/scatterlist.h:248
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
</details>
</li>
</ul>

## Differences
