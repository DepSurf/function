# Function: <code>aa_sock_opt_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_sock_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813913e0)
Location: security/apparmor/net.c:335
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff813913e0-ffffffff813914ea: aa_sock_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_sock_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813cc9d0)
Location: security/apparmor/net.c:335
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff813cc9d0-ffffffff813ccada: aa_sock_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_sock_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813e4050)
Location: security/apparmor/net.c:335
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff813e4050-ffffffff813e415a: aa_sock_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_sock_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813f1dd0)
Location: security/apparmor/net.c:334
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff813f1dd0-ffffffff813f1df5: aa_sock_opt_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_sock_opt_perm(const char *op, u32 request, struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81419e50)
Location: security/apparmor/net.c:334
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
```
**Symbols:**

```
ffffffff81419e50-ffffffff81419e75: aa_sock_opt_perm (STB_GLOBAL)
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
In security/apparmor/lsm.c (ffffffff81440985)
Location: security/apparmor/lsm.c:1078
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff8145d985)
Location: security/apparmor/lsm.c:1047
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff8148afa5)
Location: security/apparmor/lsm.c:1043
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff814a4e65)
Location: security/apparmor/lsm.c:1043
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff814ffdc5)
Location: security/apparmor/lsm.c:1108
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff8151cfb5)
Location: security/apparmor/lsm.c:1108
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff815237c5)
Location: security/apparmor/lsm.c:1117
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff815819a5)
Location: security/apparmor/lsm.c:1117
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff81620dc5)
Location: security/apparmor/lsm.c:1336
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff816d4615)
Location: security/apparmor/lsm.c:1393
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff8170d5a5)
Location: security/apparmor/lsm.c:1543
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff8174b1d9)
Location: security/apparmor/lsm.c:1563
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffff80001059b40c)
Location: security/apparmor/lsm.c:1043
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (c074bf6c)
Location: security/apparmor/lsm.c:1043
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (c0000000007128bc)
Location: security/apparmor/lsm.c:1043
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffe0003e73a0)
Location: security/apparmor/lsm.c:1043
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff8149d445)
Location: security/apparmor/lsm.c:1043
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff8148de65)
Location: security/apparmor/lsm.c:1043
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff814994e5)
Location: security/apparmor/lsm.c:1043
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
In security/apparmor/lsm.c (ffffffff814b1665)
Location: security/apparmor/lsm.c:1043
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_setsockopt
  - security/apparmor/lsm.c:apparmor_socket_getsockopt
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
