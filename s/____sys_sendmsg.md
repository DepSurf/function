# Function: <code>____sys_sendmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190e040)
Location: net/socket.c:2235
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff8190e040-ffffffff8190e2bb: ____sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dfb60)
Location: net/socket.c:2296
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff819dfb60-ffffffff819dfdf1: ____sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819df320)
Location: net/socket.c:2289
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff819df320-ffffffff819df5b1: ____sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c5230)
Location: net/socket.c:2283
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff819c5230-ffffffff819c54b8: ____sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a74760)
Location: net/socket.c:2356
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81a74760-ffffffff81a749e8: ____sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be7500)
Location: net/socket.c:2432
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81be7500-ffffffff81be77b1: ____sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:2420
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81d935f0-ffffffff81d93901: ____sys_sendmsg (STB_LOCAL)
ffffffff820aaaf3-ffffffff820aab16: ____sys_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:2457
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81e021b0-ffffffff81e02515: ____sys_sendmsg (STB_LOCAL)
ffffffff8212c034-ffffffff8212c057: ____sys_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:2527
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81ebea90-ffffffff81ebee72: ____sys_sendmsg (STB_LOCAL)
ffffffff8220dcfa-ffffffff8220dd15: ____sys_sendmsg.cold (STB_LOCAL)
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
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba3870)
Location: net/socket.c:2235
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffff800010ba3870-ffff800010ba3ac4: ____sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc4d3c)
Location: net/socket.c:2235
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
c0cc4d3c-c0cc4fa0: ____sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c774c0)
Location: net/socket.c:2235
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
c000000000c774c0-c000000000c77828: ____sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073aade)
Location: net/socket.c:2235
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffe00073aade-ffffffe00073ac7c: ____sys_sendmsg (STB_LOCAL)
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
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ae040)
Location: net/socket.c:2235
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff818ae040-ffffffff818ae2bb: ____sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81867f90)
Location: net/socket.c:2235
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81867f90-ffffffff8186820b: ____sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ff040)
Location: net/socket.c:2235
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff818ff040-ffffffff818ff2bb: ____sys_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ____sys_sendmsg(struct socket *sock, struct msghdr *msg_sys, unsigned int flags, struct used_address *used_address, unsigned int allowed_msghdr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81920030)
Location: net/socket.c:2235
Inline: False
Direct callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81920030-ffffffff819202ab: ____sys_sendmsg (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
