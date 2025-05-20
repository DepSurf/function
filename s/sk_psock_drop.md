# Function: <code>sk_psock_drop</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818e7490)
Location: net/core/skmsg.c:574
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff818e7490-ffffffff818e75c1: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81936e10)
Location: net/core/skmsg.c:586
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81936e10-ffffffff81936f6d: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81969ce0)
Location: net/core/skmsg.c:595
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81969ce0-ffffffff81969e6d: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3d7f0)
Location: net/core/skmsg.c:596
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link_no_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81a3d7f0-ffffffff81a3d96a: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a403d0)
Location: net/core/skmsg.c:681
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link_no_progs
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81a403d0-ffffffff81a40580: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4eef0)
Location: net/core/skmsg.c:820
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81a4eef0-ffffffff81a4f002: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b07a60)
Location: net/core/skmsg.c:815
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81b07a60-ffffffff81b07ba6: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8d810)
Location: net/core/skmsg.c:835
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81c8d810-ffffffff81c8d962: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e48690)
Location: net/core/skmsg.c:839
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81e48690-ffffffff81e487e0: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea3d20)
Location: net/core/skmsg.c:829
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81ea3d20-ffffffff81ea3e70: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f66620)
Location: net/core/skmsg.c:835
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81f66620-ffffffff81f66770: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffff800010c0ff08)
Location: net/core/skmsg.c:595
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffff800010c0ff08-ffff800010c100f8: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c0d27d04)
Location: net/core/skmsg.c:595
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_link
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
c0d27d04-c0d27e64: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c000000000cfc230)
Location: net/core/skmsg.c:595
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
c000000000cfc230-c000000000cfc3fc: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffe00078c430)
Location: net/core/skmsg.c:595
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffe00078c430-ffffffe00078c560: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81909cb0)
Location: net/core/skmsg.c:595
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81909cb0-ffffffff81909e3d: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818c3ac0)
Location: net/core/skmsg.c:595
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff818c3ac0-ffffffff818c3c4d: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8195ace0)
Location: net/core/skmsg.c:595
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff8195ace0-ffffffff8195ae6d: sk_psock_drop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sk_psock_drop(struct sock *sk, struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8197cf00)
Location: net/core/skmsg.c:595
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff8197cf00-ffffffff8197d08d: sk_psock_drop (STB_GLOBAL)
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
