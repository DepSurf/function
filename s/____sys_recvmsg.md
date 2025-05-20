# Function: <code>____sys_recvmsg</code>

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
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190c360)
Location: net/socket.c:2507
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff8190c360-ffffffff8190c4c8: ____sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819df7c0)
Location: net/socket.c:2549
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff819df7c0-ffffffff819df970: ____sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819defd0)
Location: net/socket.c:2542
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff819defd0-ffffffff819df175: ____sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c4ee0)
Location: net/socket.c:2532
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff819c4ee0-ffffffff819c5085: ____sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a74410)
Location: net/socket.c:2605
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff81a74410-ffffffff81a745b5: ____sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be7180)
Location: net/socket.c:2681
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff81be7180-ffffffff81be7348: ____sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d93230)
Location: net/socket.c:2669
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff81d93230-ffffffff81d933f8: ____sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e01d60)
Location: net/socket.c:2707
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff81e01d60-ffffffff81e01f88: ____sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebe720)
Location: net/socket.c:2777
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff81ebe720-ffffffff81ebe948: ____sys_recvmsg (STB_LOCAL)
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
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba4768)
Location: net/socket.c:2507
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffff800010ba4768-ffff800010ba4a4c: ____sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc4bc4)
Location: net/socket.c:2507
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
c0cc4bc4-c0cc4d3c: ____sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c77ff0)
Location: net/socket.c:2507
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
c000000000c77ff0-c000000000c7828c: ____sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000739498)
Location: net/socket.c:2507
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffe000739498-ffffffe00073957c: ____sys_recvmsg (STB_LOCAL)
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
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ac360)
Location: net/socket.c:2507
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff818ac360-ffffffff818ac4c8: ____sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818662b0)
Location: net/socket.c:2507
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff818662b0-ffffffff81866418: ____sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fd360)
Location: net/socket.c:2507
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff818fd360-ffffffff818fd4c8: ____sys_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ____sys_recvmsg(struct socket *sock, struct msghdr *msg_sys, struct user_msghdr *msg, struct sockaddr *uaddr, unsigned int flags, int nosec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191e3d0)
Location: net/socket.c:2507
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff8191e3d0-ffffffff8191e538: ____sys_recvmsg (STB_LOCAL)
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
