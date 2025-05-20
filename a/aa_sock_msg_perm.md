# Function: <code>aa_sock_msg_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_sock_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81391290)
Location: security/apparmor/net.c:320
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff81391290-ffffffff813913d3: aa_sock_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_sock_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813cc880)
Location: security/apparmor/net.c:320
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff813cc880-ffffffff813cc9c3: aa_sock_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_sock_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813e3f00)
Location: security/apparmor/net.c:320
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff813e3f00-ffffffff813e4043: aa_sock_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_sock_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813f1da0)
Location: security/apparmor/net.c:319
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff813f1da0-ffffffff813f1dc5: aa_sock_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_sock_msg_perm(const char *op, u32 request, struct socket *sock, struct msghdr *msg, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81419e20)
Location: security/apparmor/net.c:319
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
**Symbols:**

```
ffffffff81419e20-ffffffff81419e45: aa_sock_msg_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814409d5)
Location: security/apparmor/lsm.c:1018
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8145d9d5)
Location: security/apparmor/lsm.c:987
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148aff5)
Location: security/apparmor/lsm.c:983
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814a4eb5)
Location: security/apparmor/lsm.c:983
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814ffe15)
Location: security/apparmor/lsm.c:1048
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8151d005)
Location: security/apparmor/lsm.c:1048
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81523815)
Location: security/apparmor/lsm.c:1057
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff815819f5)
Location: security/apparmor/lsm.c:1057
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81620e35)
Location: security/apparmor/lsm.c:1276
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816d4695)
Location: security/apparmor/lsm.c:1333
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8170d625)
Location: security/apparmor/lsm.c:1483
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8174b289)
Location: security/apparmor/lsm.c:1515
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffff80001059af0c)
Location: security/apparmor/lsm.c:983
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c074bfd8)
Location: security/apparmor/lsm.c:983
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c00000000071294c)
Location: security/apparmor/lsm.c:983
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffe0003e7414)
Location: security/apparmor/lsm.c:983
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149d495)
Location: security/apparmor/lsm.c:983
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148deb5)
Location: security/apparmor/lsm.c:983
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81499535)
Location: security/apparmor/lsm.c:983
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814b16b5)
Location: security/apparmor/lsm.c:983
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_recvmsg
  - security/apparmor/lsm.c:apparmor_socket_sendmsg
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
</ul>
