# Function: <code>aa_unix_opt_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81393240)
Location: security/apparmor/af_unix.c:474
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_opt_perm
```
**Symbols:**

```
ffffffff81393240-ffffffff81393461: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813ce9a0)
Location: security/apparmor/af_unix.c:474
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_opt_perm
```
**Symbols:**

```
ffffffff813ce9a0-ffffffff813cec17: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813e6020)
Location: security/apparmor/af_unix.c:474
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_opt_perm
```
**Symbols:**

```
ffffffff813e6020-ffffffff813e6297: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff813f3650)
Location: security/apparmor/af_unix.c:481
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_opt_perm
```
**Symbols:**

```
ffffffff813f3650-ffffffff813f37c4: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8141b7f0)
Location: security/apparmor/af_unix.c:481
Inline: False
Direct callers:
  - security/apparmor/net.c:aa_sock_opt_perm
```
**Symbols:**

```
ffffffff8141b7f0-ffffffff8141b9a7: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8144d6e0)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff8144d6e0-ffffffff8144d88e: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8146a680)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff8146a680-ffffffff8146a84d: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814976a0)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff814976a0-ffffffff8149785f: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814b15d0)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff814b15d0-ffffffff814b178f: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81510fb0)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff81510fb0-ffffffff815110b9: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8152de00)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff8152de00-ffffffff8152df09: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81534130)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff81534130-ffffffff81534239: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff815926b0)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff815926b0-ffffffff815927b9: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff816344b0)
Location: security/apparmor/af_unix.c:505
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff816344b0-ffffffff816345be: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff816e93d0)
Location: security/apparmor/af_unix.c:523
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff816e93d0-ffffffff816e94de: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81722ba0)
Location: security/apparmor/af_unix.c:523
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff81722ba0-ffffffff81722cae: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff81761680)
Location: security/apparmor/af_unix.c:523
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff81761680-ffffffff81761791: aa_unix_opt_perm (STB_GLOBAL)
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
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffff8000105a8ec0)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffff8000105a8ec0-ffff8000105a90b8: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c0758f90)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
c0758f90-c075919c: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (c000000000726130)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
c000000000726130-c000000000726434: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffe0003f240a)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffe0003f240a-ffffffe0003f258a: aa_unix_opt_perm (STB_GLOBAL)
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
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a9bb0)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff814a9bb0-ffffffff814a9d6f: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff8149a5d0)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff8149a5d0-ffffffff8149a78f: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814a5c50)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff814a5c50-ffffffff814a5e0f: aa_unix_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_unix_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/af_unix.c (ffffffff814be4f0)
Location: security/apparmor/af_unix.c:482
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff814be4f0-ffffffff814be6b5: aa_unix_opt_perm (STB_GLOBAL)
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
