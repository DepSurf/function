# Function: <code>aa_sock_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81390d00)
Location: security/apparmor/net.c:241
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff81390d00-ffffffff81390dd6: aa_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813cc2f0)
Location: security/apparmor/net.c:241
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff813cc2f0-ffffffff813cc3c6: aa_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813e3970)
Location: security/apparmor/net.c:241
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff813e3970-ffffffff813e3a46: aa_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813f1c50)
Location: security/apparmor/net.c:240
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff813f1c50-ffffffff813f1c75: aa_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81419cd0)
Location: security/apparmor/net.c:240
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff81419cd0-ffffffff81419cf5: aa_sock_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814408f0)
Location: security/apparmor/lsm.c:1050
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff814408f0-ffffffff81440915: aa_sock_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8145d8f0)
Location: security/apparmor/lsm.c:1019
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff8145d8f0-ffffffff8145d915: aa_sock_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148af10)
Location: security/apparmor/lsm.c:1015
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff8148af10-ffffffff8148af36: aa_sock_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814a4dd0)
Location: security/apparmor/lsm.c:1015
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff814a4dd0-ffffffff814a4df6: aa_sock_perm (STB_LOCAL)
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
In security/apparmor/lsm.c (ffffffff815002c5)
Location: security/apparmor/lsm.c:1080
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
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
In security/apparmor/lsm.c (ffffffff8151d475)
Location: security/apparmor/lsm.c:1080
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
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
In security/apparmor/lsm.c (ffffffff81523c85)
Location: security/apparmor/lsm.c:1089
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
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
In security/apparmor/lsm.c (ffffffff81581f15)
Location: security/apparmor/lsm.c:1089
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
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
In security/apparmor/lsm.c (ffffffff81621385)
Location: security/apparmor/lsm.c:1308
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
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
In security/apparmor/lsm.c (ffffffff816d45a5)
Location: security/apparmor/lsm.c:1365
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
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
In security/apparmor/lsm.c (ffffffff8170d535)
Location: security/apparmor/lsm.c:1515
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
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
In security/apparmor/lsm.c (ffffffff8174c5c5)
Location: security/apparmor/lsm.c:1541
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
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
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffff80001059ad50)
Location: security/apparmor/lsm.c:1015
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffff80001059ad50-ffff80001059adc0: aa_sock_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c074be98)
Location: security/apparmor/lsm.c:1015
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
c074be98-c074bed0: aa_sock_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c0000000007127a0)
Location: security/apparmor/lsm.c:1015
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
c0000000007127a0-c000000000712808: aa_sock_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffe0003e7280)
Location: security/apparmor/lsm.c:1015
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffe0003e7280-ffffffe0003e72e0: aa_sock_perm (STB_LOCAL)
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
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149d3b0)
Location: security/apparmor/lsm.c:1015
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff8149d3b0-ffffffff8149d3d6: aa_sock_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148ddd0)
Location: security/apparmor/lsm.c:1015
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff8148ddd0-ffffffff8148ddf6: aa_sock_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81499450)
Location: security/apparmor/lsm.c:1015
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff81499450-ffffffff81499476: aa_sock_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_sock_perm(const char *op, u32 request, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814b15d0)
Location: security/apparmor/lsm.c:1015
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_shutdown
  - security/apparmor/lsm.c:apparmor_socket_getpeername
  - security/apparmor/lsm.c:apparmor_socket_getsockname
```
**Symbols:**

```
ffffffff814b15d0-ffffffff814b15f6: aa_sock_perm (STB_LOCAL)
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
