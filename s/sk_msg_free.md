# Function: <code>sk_msg_free</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818e74b8)
Location: net/core/skmsg.c:196
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:__sk_psock_purge_ingress_msg
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff818e6ca0-ffffffff818e6cb7: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81936e2d)
Location: net/core/skmsg.c:205
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:__sk_psock_purge_ingress_msg
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81936650-ffffffff81936667: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81969cfd)
Location: net/core/skmsg.c:204
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:__sk_psock_purge_ingress_msg
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81969620-ffffffff81969637: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3d80d)
Location: net/core/skmsg.c:205
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:__sk_psock_purge_ingress_msg
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81a3d050-ffffffff81a3d067: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a403ed)
Location: net/core/skmsg.c:207
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:__sk_psock_purge_ingress_msg
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81a3f330-ffffffff81a3f347: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4d7c7)
Location: net/core/skmsg.c:207
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_stop
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81a4d5b0-ffffffff81a4d5c7: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b05e87)
Location: net/core/skmsg.c:207
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_stop
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81b05d80-ffffffff81b05d97: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8b897)
Location: net/core/skmsg.c:216
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81c8b630-ffffffff81c8b653: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e463f7)
Location: net/core/skmsg.c:216
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81e45950-ffffffff81e45973: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea2929)
Location: net/core/skmsg.c:217
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81ea0f60-ffffffff81ea0f83: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f659c9)
Location: net/core/skmsg.c:217
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_destroy
  - net/core/skmsg.c:sk_psock_stop
  - net/core/skmsg.c:sk_psock_skb_ingress_enqueue
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/xfrm/espintcp.c:espintcp_close
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81f63610-ffffffff81f63633: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffff800010c0ff34)
Location: net/core/skmsg.c:204
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:__sk_psock_purge_ingress_msg
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffff800010c0e8e0-ffff800010c0e91c: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c0d27d2c)
Location: net/core/skmsg.c:204
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:__sk_psock_purge_ingress_msg
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
c0d275e0-c0d27604: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c000000000cfc270)
Location: net/core/skmsg.c:204
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:__sk_psock_purge_ingress_msg
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
c000000000cfb700-c000000000cfb71c: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffe00078c450)
Location: net/core/skmsg.c:204
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:__sk_psock_purge_ingress_msg
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffe00078bbf2-ffffffe00078bc28: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81909ccd)
Location: net/core/skmsg.c:204
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:__sk_psock_purge_ingress_msg
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff819095f0-ffffffff81909607: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818c3add)
Location: net/core/skmsg.c:204
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:__sk_psock_purge_ingress_msg
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff818c3400-ffffffff818c3417: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8195acfd)
Location: net/core/skmsg.c:204
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:__sk_psock_purge_ingress_msg
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff8195a620-ffffffff8195a637: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sk_msg_free(struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8197cf1d)
Location: net/core/skmsg.c:204
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:__sk_psock_purge_ingress_msg
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff8197c840-ffffffff8197c857: sk_msg_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
