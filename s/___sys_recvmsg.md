# Function: <code>___sys_recvmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816feb50)
Location: net/socket.c:2063
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff816feb50-ffffffff816fed3a: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817655a0)
Location: net/socket.c:2064
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff817655a0-ffffffff8176578a: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81792620)
Location: net/socket.c:2109
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff81792620-ffffffff8179280a: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817b0a50)
Location: net/socket.c:2159
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff817b0a50-ffffffff817b0c84: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81828be0)
Location: net/socket.c:2152
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff81828be0-ffffffff81828e17: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81871630)
Location: net/socket.c:2255
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff81871630-ffffffff81871807: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81892890)
Location: net/socket.c:2242
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff81892890-ffffffff81892a90: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dcb80)
Location: net/socket.c:2445
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
  - net/socket.c:__sys_recvmsg_sock
```
**Symbols:**

```
ffffffff818dcb80-ffffffff818dcd64: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190d9b0)
Location: net/socket.c:2558
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff8190d9b0-ffffffff8190da70: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1ec0)
Location: net/socket.c:2605
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff819e1ec0-ffffffff819e1fe4: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1b60)
Location: net/socket.c:2598
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff819e1b60-ffffffff819e1c84: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c7be0)
Location: net/socket.c:2588
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff819c7be0-ffffffff819c7ceb: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a76f30)
Location: net/socket.c:2661
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff81a76f30-ffffffff81a7703b: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81bea1b0)
Location: net/socket.c:2737
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff81bea1b0-ffffffff81bea2f5: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d96ab0)
Location: net/socket.c:2725
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff81d96ab0-ffffffff81d96b94: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e05120)
Location: net/socket.c:2763
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff81e05120-ffffffff81e0520e: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec19e0)
Location: net/socket.c:2833
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff81ec19e0-ffffffff81ec1ace: ___sys_recvmsg (STB_LOCAL)
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
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba4a50)
Location: net/socket.c:2558
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffff800010ba4a50-ffff800010ba4b24: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc5998)
Location: net/socket.c:2558
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
c0cc5998-c0cc5a48: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c78290)
Location: net/socket.c:2558
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
c000000000c78290-c000000000c78394: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073a86e)
Location: net/socket.c:2558
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffe00073a86e-ffffffe00073a8f2: ___sys_recvmsg (STB_LOCAL)
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
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ad9b0)
Location: net/socket.c:2558
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff818ad9b0-ffffffff818ada70: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81867900)
Location: net/socket.c:2558
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff81867900-ffffffff818679c0: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fe9b0)
Location: net/socket.c:2558
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff818fe9b0-ffffffff818fea70: ___sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ___sys_recvmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191fa30)
Location: net/socket.c:2558
Inline: False
Direct callers:
  - net/socket.c:do_recvmmsg
  - net/socket.c:do_recvmmsg
  - net/socket.c:__sys_recvmsg
```
**Symbols:**

```
ffffffff8191fa30-ffffffff8191faf0: ___sys_recvmsg (STB_LOCAL)
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
