# Function: <code>___sys_sendmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fe8c0)
Location: net/socket.c:1875
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
```
**Symbols:**

```
ffffffff816fe8c0-ffffffff816feb4d: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817652d0)
Location: net/socket.c:1868
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff817652d0-ffffffff8176559e: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81792350)
Location: net/socket.c:1911
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff81792350-ffffffff8179261e: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817b0760)
Location: net/socket.c:1959
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff817b0760-ffffffff817b0a49: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818288f0)
Location: net/socket.c:1952
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff818288f0-ffffffff81828bdf: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81871340)
Location: net/socket.c:2052
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff81871340-ffffffff8187162c: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818925a0)
Location: net/socket.c:2039
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff818925a0-ffffffff8189288c: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dc850)
Location: net/socket.c:2235
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
  - net/socket.c:__sys_sendmsg_sock
```
**Symbols:**

```
ffffffff818dc850-ffffffff818dcb7b: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190e2c0)
Location: net/socket.c:2336
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff8190e2c0-ffffffff8190e389: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e26d0)
Location: net/socket.c:2391
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff819e26d0-ffffffff819e278a: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e2350)
Location: net/socket.c:2384
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff819e2350-ffffffff819e240a: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c83e0)
Location: net/socket.c:2378
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff819c83e0-ffffffff819c8498: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a77730)
Location: net/socket.c:2451
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff81a77730-ffffffff81a777e8: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81beaad0)
Location: net/socket.c:2527
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff81beaad0-ffffffff81beabad: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d97310)
Location: net/socket.c:2515
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff81d97310-ffffffff81d973fa: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e05980)
Location: net/socket.c:2553
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff81e05980-ffffffff81e05a6a: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec2240)
Location: net/socket.c:2623
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff81ec2240-ffffffff81ec232a: ___sys_sendmsg (STB_LOCAL)
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
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba3f00)
Location: net/socket.c:2336
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffff800010ba3f00-ffff800010ba3fe0: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc58e4)
Location: net/socket.c:2336
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
c0cc58e4-c0cc5998: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c77c90)
Location: net/socket.c:2336
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
c000000000c77c90-c000000000c77d98: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073ac7c)
Location: net/socket.c:2336
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffe00073ac7c-ffffffe00073ad04: ___sys_sendmsg (STB_LOCAL)
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
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ae2c0)
Location: net/socket.c:2336
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff818ae2c0-ffffffff818ae389: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81868210)
Location: net/socket.c:2336
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff81868210-ffffffff818682d9: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ff2c0)
Location: net/socket.c:2336
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff818ff2c0-ffffffff818ff389: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ___sys_sendmsg(struct socket *sock, struct user_msghdr *msg, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819202b0)
Location: net/socket.c:2336
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmmsg
  - net/socket.c:__sys_sendmsg
```
**Symbols:**

```
ffffffff819202b0-ffffffff81920379: ___sys_sendmsg (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int allowed_msghdr_flags</code>
</li>
</ul>
</details>
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
