# Function: <code>aa_unix_sock_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81392a20)
Location: security/apparmor/af_unix.c:286
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_perm
```
**Symbols:**

```
ffffffff81392a20-ffffffff81392be3: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813ce020)
Location: security/apparmor/af_unix.c:286
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_perm
```
**Symbols:**

```
ffffffff813ce020-ffffffff813ce244: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813e56a0)
Location: security/apparmor/af_unix.c:286
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_perm
```
**Symbols:**

```
ffffffff813e56a0-ffffffff813e58c4: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813f30c0)
Location: security/apparmor/af_unix.c:287
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_perm
```
**Symbols:**

```
ffffffff813f30c0-ffffffff813f31e1: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8141b140)
Location: security/apparmor/af_unix.c:287
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_perm
```
**Symbols:**

```
ffffffff8141b140-ffffffff8141b2cc: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8144d040)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:aa_sock_perm
```
**Symbols:**

```
ffffffff8144d040-ffffffff8144d1c6: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81469fa0)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:aa_sock_perm
```
**Symbols:**

```
ffffffff81469fa0-ffffffff8146a11d: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81497000)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:aa_sock_perm
```
**Symbols:**

```
ffffffff81497000-ffffffff8149716b: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814b0f30)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:aa_sock_perm
```
**Symbols:**

```
ffffffff814b0f30-ffffffff814b109b: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81510b80)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff81510b80-ffffffff81510c92: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8152d9d0)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff8152d9d0-ffffffff8152dae2: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81533d00)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff81533d00-ffffffff81533e12: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81592280)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff81592280-ffffffff81592392: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81634020)
Location: security/apparmor/af_unix.c:303
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff81634020-ffffffff8163414b: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff816e8ec0)
Location: security/apparmor/af_unix.c:320
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff816e8ec0-ffffffff816e900c: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81722680)
Location: security/apparmor/af_unix.c:320
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff81722680-ffffffff817227d1: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff817611a0)
Location: security/apparmor/af_unix.c:320
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff817611a0-ffffffff817612ba: aa_unix_sock_perm (STB_GLOBAL)
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
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffff8000105a8770)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:aa_sock_perm
```
**Symbols:**

```
ffff8000105a8770-ffff8000105a88e8: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c0758830)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:aa_sock_perm
```
**Symbols:**

```
c0758830-c07589ac: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c000000000725630)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:aa_sock_perm
```
**Symbols:**

```
c000000000725630-c000000000725864: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffe0003f1e6c)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:aa_sock_perm
```
**Symbols:**

```
ffffffe0003f1e6c-ffffffe0003f1f82: aa_unix_sock_perm (STB_GLOBAL)
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
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a9510)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:aa_sock_perm
```
**Symbols:**

```
ffffffff814a9510-ffffffff814a967b: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81499f30)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:aa_sock_perm
```
**Symbols:**

```
ffffffff81499f30-ffffffff8149a09b: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a55b0)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:aa_sock_perm
```
**Symbols:**

```
ffffffff814a55b0-ffffffff814a571b: aa_unix_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_unix_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814bde40)
Location: security/apparmor/af_unix.c:288
Inline: False
Direct callers:
  - security/apparmor/lsm.c:aa_sock_perm
```
**Symbols:**

```
ffffffff814bde40-ffffffff814bdfae: aa_unix_sock_perm (STB_GLOBAL)
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
