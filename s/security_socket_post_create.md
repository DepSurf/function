# Function: <code>security_socket_post_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133f150)
Location: security/security.c:1211
Inline: False
Direct callers:
  - net/socket.c:sock_create_lite
  - net/socket.c:__sock_create
```
**Symbols:**

```
ffffffff8133f150-ffffffff8133f1cb: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81374770)
Location: security/security.c:1241
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff81374770-ffffffff813747eb: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138b0a0)
Location: security/security.c:1262
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff8138b0a0-ffffffff8138b11b: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a0c60)
Location: security/security.c:2192
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff813a0c60-ffffffff813a0cdb: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c66a0)
Location: security/security.c:2050
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff813c66a0-ffffffff813c6721: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f6120)
Location: security/security.c:1366
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff813f6120-ffffffff813f6188: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81411b80)
Location: security/security.c:2117
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff81411b80-ffffffff81411be8: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143f420)
Location: security/security.c:2136
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff8143f420-ffffffff8143f497: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81458dd0)
Location: security/security.c:2175
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff81458dd0-ffffffff81458e36: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814abe00)
Location: security/security.c:2479
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff814abe00-ffffffff814abe66: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c9400)
Location: security/security.c:2496
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff814c9400-ffffffff814c9466: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cfa30)
Location: security/security.c:2559
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff814cfa30-ffffffff814cfa96: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81528760)
Location: security/security.c:2567
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff81528760-ffffffff815287c6: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bd970)
Location: security/security.c:2597
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff815bd970-ffffffff815bda07: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816699c0)
Location: security/security.c:2577
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff816699c0-ffffffff81669a57: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1fa0)
Location: security/security.c:4396
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff816a1fa0-ffffffff816a2037: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816deb10)
Location: security/security.c:4557
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff816deb10-ffffffff816deba7: security_socket_post_create (STB_GLOBAL)
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
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010544d18)
Location: security/security.c:2175
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffff800010544d18-ffff800010544d98: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fac28)
Location: security/security.c:2175
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
c06fac28-c06faca4: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c00000000069a8c0)
Location: security/security.c:2175
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
c00000000069a8c0-c00000000069a9b8: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a0cce)
Location: security/security.c:2175
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffe0003a0cce-ffffffe0003a0d2a: security_socket_post_create (STB_GLOBAL)
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
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814513b0)
Location: security/security.c:2175
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff814513b0-ffffffff81451416: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441e00)
Location: security/security.c:2175
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff81441e00-ffffffff81441e66: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144d450)
Location: security/security.c:2175
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff8144d450-ffffffff8144d4b6: security_socket_post_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_socket_post_create(struct socket *sock, int family, int type, int protocol, int kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81464820)
Location: security/security.c:2175
Inline: False
Direct callers:
  - net/socket.c:__sock_create
  - net/socket.c:sock_create_lite
```
**Symbols:**

```
ffffffff81464820-ffffffff81464886: security_socket_post_create (STB_GLOBAL)
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
