# Function: <code>security_socket_getsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133f4a0)
Location: security/security.c:1259
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8133f4a0-ffffffff8133f4fb: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81374ac0)
Location: security/security.c:1289
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81374ac0-ffffffff81374b1b: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138b3f0)
Location: security/security.c:1310
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8138b3f0-ffffffff8138b44b: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a0fb0)
Location: security/security.c:2240
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff813a0fb0-ffffffff813a100b: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c6a50)
Location: security/security.c:2098
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff813c6a50-ffffffff813c6ab1: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f6400)
Location: security/security.c:1420
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff813f6400-ffffffff813f644e: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81411e60)
Location: security/security.c:2171
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff81411e60-ffffffff81411eae: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f770)
Location: security/security.c:2190
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff8143f770-ffffffff8143f7c7: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814590b0)
Location: security/security.c:2229
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff814590b0-ffffffff814590fc: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ac0e0)
Location: security/security.c:2533
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff814ac0e0-ffffffff814ac12c: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c96e0)
Location: security/security.c:2550
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff814c96e0-ffffffff814c972c: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cfd10)
Location: security/security.c:2613
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff814cfd10-ffffffff814cfd5c: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81528a40)
Location: security/security.c:2621
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81528a40-ffffffff81528a8c: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bdd40)
Location: security/security.c:2651
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff815bdd40-ffffffff815bddab: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81669e20)
Location: security/security.c:2631
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff81669e20-ffffffff81669e8b: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a2400)
Location: security/security.c:4554
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
```
**Symbols:**

```
ffffffff816a2400-ffffffff816a246b: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816def70)
Location: security/security.c:4715
Inline: False
Direct callers:
  - net/socket.c:do_sock_getsockopt
```
**Symbols:**

```
ffffffff816def70-ffffffff816defdb: security_socket_getsockopt (STB_GLOBAL)
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
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105450a8)
Location: security/security.c:2229
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffff8000105450a8-ffff80001054510c: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06faf9c)
Location: security/security.c:2229
Inline: False
Direct callers:
  - net/socket.c:__se_sys_getsockopt
```
**Symbols:**

```
c06faf9c-c06fb000: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c00000000069b000)
Location: security/security.c:2229
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
c00000000069b000-c00000000069b0d0: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a0f62)
Location: security/security.c:2229
Inline: False
Direct callers:
  - net/socket.c:__se_sys_getsockopt
```
**Symbols:**

```
ffffffe0003a0f62-ffffffe0003a0fae: security_socket_getsockopt (STB_GLOBAL)
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
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81451690)
Location: security/security.c:2229
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff81451690-ffffffff814516dc: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814420e0)
Location: security/security.c:2229
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff814420e0-ffffffff8144212c: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144d730)
Location: security/security.c:2229
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff8144d730-ffffffff8144d77c: security_socket_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_socket_getsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81464b00)
Location: security/security.c:2229
Inline: False
Direct callers:
  - net/socket.c:__sys_getsockopt
  - net/compat.c:__compat_sys_getsockopt
```
**Symbols:**

```
ffffffff81464b00-ffffffff81464b4c: security_socket_getsockopt (STB_GLOBAL)
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
