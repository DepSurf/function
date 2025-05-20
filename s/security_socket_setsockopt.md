# Function: <code>security_socket_setsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133f500)
Location: security/security.c:1264
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8133f500-ffffffff8133f55b: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81374b20)
Location: security/security.c:1294
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81374b20-ffffffff81374b7b: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138b450)
Location: security/security.c:1315
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8138b450-ffffffff8138b4ab: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a1010)
Location: security/security.c:2245
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff813a1010-ffffffff813a106b: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c6ac0)
Location: security/security.c:2103
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff813c6ac0-ffffffff813c6b21: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f6450)
Location: security/security.c:1425
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff813f6450-ffffffff813f649e: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81411eb0)
Location: security/security.c:2176
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff81411eb0-ffffffff81411efe: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f7d0)
Location: security/security.c:2195
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff8143f7d0-ffffffff8143f827: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81459100)
Location: security/security.c:2234
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff81459100-ffffffff8145914c: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ac130)
Location: security/security.c:2538
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff814ac130-ffffffff814ac17c: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c9730)
Location: security/security.c:2555
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff814c9730-ffffffff814c977c: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cfd60)
Location: security/security.c:2618
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff814cfd60-ffffffff814cfdac: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81528a90)
Location: security/security.c:2626
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff81528a90-ffffffff81528adc: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bddb0)
Location: security/security.c:2656
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff815bddb0-ffffffff815bde1b: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81669ea0)
Location: security/security.c:2636
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff81669ea0-ffffffff81669f0b: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a2480)
Location: security/security.c:4569
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
```
**Symbols:**

```
ffffffff816a2480-ffffffff816a24eb: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816deff0)
Location: security/security.c:4730
Inline: False
Direct callers:
  - net/socket.c:do_sock_setsockopt
```
**Symbols:**

```
ffffffff816deff0-ffffffff816df05b: security_socket_setsockopt (STB_GLOBAL)
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
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010545110)
Location: security/security.c:2234
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffff800010545110-ffff800010545174: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fb000)
Location: security/security.c:2234
Inline: False
Direct callers:
  - net/socket.c:__se_sys_setsockopt
```
**Symbols:**

```
c06fb000-c06fb064: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c00000000069b0d0)
Location: security/security.c:2234
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
c00000000069b0d0-c00000000069b1a0: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a0fae)
Location: security/security.c:2234
Inline: False
Direct callers:
  - net/socket.c:__se_sys_setsockopt
```
**Symbols:**

```
ffffffe0003a0fae-ffffffe0003a0ffa: security_socket_setsockopt (STB_GLOBAL)
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
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814516e0)
Location: security/security.c:2234
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff814516e0-ffffffff8145172c: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81442130)
Location: security/security.c:2234
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff81442130-ffffffff8144217c: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144d780)
Location: security/security.c:2234
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff8144d780-ffffffff8144d7cc: security_socket_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_socket_setsockopt(struct socket *sock, int level, int optname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81464b50)
Location: security/security.c:2234
Inline: False
Direct callers:
  - net/socket.c:__sys_setsockopt
  - net/compat.c:__compat_sys_setsockopt
```
**Symbols:**

```
ffffffff81464b50-ffffffff81464b9c: security_socket_setsockopt (STB_GLOBAL)
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
