# Function: <code>aa_sk_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813909c0)
Location: security/apparmor/net.c:209
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_perm
  - security/apparmor/net.c:aa_sock_bind_perm
  - security/apparmor/net.c:aa_sock_connect_perm
  - security/apparmor/net.c:aa_sock_listen_perm
  - security/apparmor/net.c:aa_sock_accept_perm
  - security/apparmor/net.c:aa_sock_msg_perm
  - security/apparmor/net.c:aa_sock_opt_perm
```
**Symbols:**

```
ffffffff813909c0-ffffffff81390bc5: aa_sk_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813cbf50)
Location: security/apparmor/net.c:209
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_opt_perm
  - security/apparmor/net.c:aa_sock_msg_perm
  - security/apparmor/net.c:aa_sock_accept_perm
  - security/apparmor/net.c:aa_sock_listen_perm
  - security/apparmor/net.c:aa_sock_connect_perm
  - security/apparmor/net.c:aa_sock_bind_perm
  - security/apparmor/net.c:aa_sock_perm
```
**Symbols:**

```
ffffffff813cbf50-ffffffff813cc1ba: aa_sk_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813e35d0)
Location: security/apparmor/net.c:209
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_opt_perm
  - security/apparmor/net.c:aa_sock_msg_perm
  - security/apparmor/net.c:aa_sock_accept_perm
  - security/apparmor/net.c:aa_sock_listen_perm
  - security/apparmor/net.c:aa_sock_connect_perm
  - security/apparmor/net.c:aa_sock_bind_perm
  - security/apparmor/net.c:aa_sock_perm
```
**Symbols:**

```
ffffffff813e35d0-ffffffff813e383a: aa_sk_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813f1b10)
Location: security/apparmor/net.c:208
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_opt_perm
  - security/apparmor/net.c:aa_sock_msg_perm
  - security/apparmor/net.c:aa_sock_accept_perm
  - security/apparmor/net.c:aa_sock_listen_perm
  - security/apparmor/net.c:aa_sock_connect_perm
  - security/apparmor/net.c:aa_sock_bind_perm
  - security/apparmor/net.c:aa_sock_perm
```
**Symbols:**

```
ffffffff813f1b10-ffffffff813f1c4a: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81419b30)
Location: security/apparmor/net.c:208
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_opt_perm
  - security/apparmor/net.c:aa_sock_msg_perm
  - security/apparmor/net.c:aa_sock_accept_perm
  - security/apparmor/net.c:aa_sock_listen_perm
  - security/apparmor/net.c:aa_sock_connect_perm
  - security/apparmor/net.c:aa_sock_bind_perm
  - security/apparmor/net.c:aa_sock_perm
```
**Symbols:**

```
ffffffff81419b30-ffffffff81419cc6: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8144bf90)
Location: security/apparmor/net.c:228
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:aa_sock_perm
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff8144bf90-ffffffff8144c113: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81468f10)
Location: security/apparmor/net.c:231
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:aa_sock_perm
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff81468f10-ffffffff81469080: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81495f60)
Location: security/apparmor/net.c:227
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:aa_sock_perm
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff81495f60-ffffffff814960d0: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814afe90)
Location: security/apparmor/net.c:227
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:aa_sock_perm
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff814afe90-ffffffff814b0000: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8150f300)
Location: security/apparmor/net.c:228
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff8150f300-ffffffff8150f4aa: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8152c140)
Location: security/apparmor/net.c:230
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff8152c140-ffffffff8152c2ef: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff815323e0)
Location: security/apparmor/net.c:230
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff815323e0-ffffffff8153258b: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81590960)
Location: security/apparmor/net.c:230
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff81590960-ffffffff81590b0b: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81631a60)
Location: security/apparmor/net.c:231
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff81631a60-ffffffff81631c7b: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff816e67c0)
Location: security/apparmor/net.c:236
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff816e67c0-ffffffff816e69fd: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8171fef0)
Location: security/apparmor/net.c:236
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff8171fef0-ffffffff8172015e: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8175e920)
Location: security/apparmor/net.c:239
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff8175e920-ffffffff8175eb94: aa_sk_perm (STB_GLOBAL)
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
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffff8000105a75e0)
Location: security/apparmor/net.c:227
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:aa_sock_perm
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffff8000105a75e0-ffff8000105a7770: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (c07575b0)
Location: security/apparmor/net.c:227
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:aa_sock_perm
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
c07575b0-c075772c: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (c000000000723fa0)
Location: security/apparmor/net.c:227
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:aa_sock_perm
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
c000000000723fa0-c0000000007241d4: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffe0003f0df8)
Location: security/apparmor/net.c:227
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:aa_sock_perm
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffe0003f0df8-ffffffe0003f0f0e: aa_sk_perm (STB_GLOBAL)
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
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814a8470)
Location: security/apparmor/net.c:227
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:aa_sock_perm
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff814a8470-ffffffff814a85e0: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81498e90)
Location: security/apparmor/net.c:227
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:aa_sock_perm
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff81498e90-ffffffff81499000: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814a4510)
Location: security/apparmor/net.c:227
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:aa_sock_perm
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff814a4510-ffffffff814a4680: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_sk_perm(const char *op, u32 request, struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814bcda0)
Location: security/apparmor/net.c:227
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
  - security/apparmor/lsm.c:aa_sock_perm
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
  - security/apparmor/lsm.c:apparmor_socket_accept
  - security/apparmor/lsm.c:apparmor_socket_listen
  - security/apparmor/lsm.c:apparmor_socket_connect
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff814bcda0-ffffffff814bcf0b: aa_sk_perm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
