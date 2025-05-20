# Function: <code>aa_unix_msg_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81393230)
Location: security/apparmor/af_unix.c:438
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_msg_perm
```
**Symbols:**

```
ffffffff81393230-ffffffff8139323d: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813ce990)
Location: security/apparmor/af_unix.c:438
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_msg_perm
```
**Symbols:**

```
ffffffff813ce990-ffffffff813ce99d: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813e6010)
Location: security/apparmor/af_unix.c:438
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_msg_perm
```
**Symbols:**

```
ffffffff813e6010-ffffffff813e601d: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813f3640)
Location: security/apparmor/af_unix.c:445
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_msg_perm
```
**Symbols:**

```
ffffffff813f3640-ffffffff813f364d: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8141b7e0)
Location: security/apparmor/af_unix.c:445
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_msg_perm
```
**Symbols:**

```
ffffffff8141b7e0-ffffffff8141b7ed: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8144d6d0)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff8144d6d0-ffffffff8144d6dd: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8146a670)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff8146a670-ffffffff8146a67d: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81497690)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff81497690-ffffffff8149769d: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814b15c0)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff814b15c0-ffffffff814b15cd: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81510fa0)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff81510fa0-ffffffff81510fad: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8152ddf0)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff8152ddf0-ffffffff8152ddfd: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81534120)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff81534120-ffffffff8153412d: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff815926a0)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff815926a0-ffffffff815926ad: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81634490)
Location: security/apparmor/af_unix.c:467
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff81634490-ffffffff816344a1: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff816e93a0)
Location: security/apparmor/af_unix.c:485
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff816e93a0-ffffffff816e93b1: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81722b70)
Location: security/apparmor/af_unix.c:485
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff81722b70-ffffffff81722b81: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81761650)
Location: security/apparmor/af_unix.c:485
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff81761650-ffffffff81761661: aa_unix_msg_perm (STB_GLOBAL)
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
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffff8000105a8ea0)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffff8000105a8ea0-ffff8000105a8ebc: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c0758f74)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
c0758f74-c0758f90: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c000000000726120)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
c000000000726120-c000000000726130: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffe0003f23ee)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffe0003f23ee-ffffffe0003f240a: aa_unix_msg_perm (STB_GLOBAL)
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
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a9ba0)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff814a9ba0-ffffffff814a9bad: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8149a5c0)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff8149a5c0-ffffffff8149a5cd: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a5c40)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff814a5c40-ffffffff814a5c4d: aa_unix_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_unix_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814be4e0)
Location: security/apparmor/af_unix.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff814be4e0-ffffffff814be4ed: aa_unix_msg_perm (STB_GLOBAL)
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
