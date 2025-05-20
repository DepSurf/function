# Function: <code>sk_msg_elem</code>

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
In net/core/filter.c (ffffffff818d9234)
Location: include/linux/skmsg.h:206
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff818e5cc5)
Location: include/linux/skmsg.h:206
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff8197776e)
Location: include/linux/skmsg.h:206
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In net/core/filter.c (ffffffff8192b358)
Location: include/linux/skmsg.h:206
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff819355df)
Location: include/linux/skmsg.h:206
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff819e129b)
Location: include/linux/skmsg.h:206
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In net/core/filter.c (ffffffff8195d6b3)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff8196839f)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a18667)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In net/core/filter.c (ffffffff81a2c840)
Location: include/linux/skmsg.h:211
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81a3c8d0)
Location: include/linux/skmsg.h:211
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0842f)
Location: include/linux/skmsg.h:211
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/skmsg.h:211
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
In net/core/filter.c (ffffffff81a2ddf0)
Location: include/linux/skmsg.h:211
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81a3efa0)
Location: include/linux/skmsg.h:211
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b1698f)
Location: include/linux/skmsg.h:211
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/skmsg.h:211
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
In net/core/filter.c (ffffffff81a1b0f0)
Location: include/linux/skmsg.h:214
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81a4d96e)
Location: include/linux/skmsg.h:214
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b046af)
Location: include/linux/skmsg.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (0)
Location: include/linux/skmsg.h:214
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
In net/core/filter.c (ffffffff81ac8343)
Location: include/linux/skmsg.h:213
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81b05102)
Location: include/linux/skmsg.h:213
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc82d2)
Location: include/linux/skmsg.h:213
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81be4348)
Location: include/linux/skmsg.h:213
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
In net/core/filter.c (ffffffff81c44873)
Location: include/linux/skmsg.h:207
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81c8d3e8)
Location: include/linux/skmsg.h:207
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5db72)
Location: include/linux/skmsg.h:207
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81d7b7e2)
Location: include/linux/skmsg.h:207
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
In net/core/filter.c (ffffffff81dfee23)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81e45a28)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f27822)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81f48872)
Location: include/linux/skmsg.h:209
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
In net/core/filter.c (ffffffff81e708f3)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81ea1038)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87a32)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff81fa86e2)
Location: include/linux/skmsg.h:209
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
In net/core/filter.c (ffffffff81f2ff83)
Location: include/linux/skmsg.h:215
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff81f63718)
Location: include/linux/skmsg.h:215
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_recvmsg
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204f114)
Location: include/linux/skmsg.h:215
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
```
In net/xfrm/espintcp.c (ffffffff820759d2)
Location: include/linux/skmsg.h:215
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
In net/core/filter.c (ffff800010bfd810)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffff800010c0e2a8)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3e64)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In net/core/filter.c (c0d19c10)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (c0d265ec)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_return_zero
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (c0dddd58)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In net/core/filter.c (c000000000ce92ec)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (c000000000cf9b70)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (c000000000df31fc)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In net/core/filter.c (ffffffe00077cfe4)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffe00078ad12)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824c90)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In net/core/filter.c (ffffffff818fd683)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff8190836f)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7cf7)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In net/core/filter.c (ffffffff818b74b3)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff818c217f)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974ae7)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In net/core/filter.c (ffffffff8194e6b3)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff8195939f)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a22777)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
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
In net/core/filter.c (ffffffff81970083)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/skmsg.c (ffffffff8197b4bf)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:sk_msg_free_elem
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_clone
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2db53)
Location: include/linux/skmsg.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
</details>
</li>
</ul>

## Differences
