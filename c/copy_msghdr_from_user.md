# Function: <code>copy_msghdr_from_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fe710)
Location: net/socket.c:1822
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff816fe710-ffffffff816fe8b6: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81765120)
Location: net/socket.c:1815
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81765120-ffffffff817652cb: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817921a0)
Location: net/socket.c:1858
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff817921a0-ffffffff8179234b: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817b0610)
Location: net/socket.c:1908
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff817b0610-ffffffff817b0757: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818287a0)
Location: net/socket.c:1901
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff818287a0-ffffffff818288e7: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818711f0)
Location: net/socket.c:2001
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff818711f0-ffffffff81871339: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81892460)
Location: net/socket.c:1988
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81892460-ffffffff8189259f: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dc700)
Location: net/socket.c:2183
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff818dc700-ffffffff818dc84f: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190d860)
Location: net/socket.c:2183
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff8190d860-ffffffff8190d9af: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1f0d)
Location: net/socket.c:2277
Inline: True
Inline callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff819e1e30-ffffffff819e1eb7: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1bad)
Location: net/socket.c:2270
Inline: True
Inline callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff819e1ad0-ffffffff819e1b57: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c7c31)
Location: net/socket.c:2264
Inline: True
Inline callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff819c7b50-ffffffff819c7bd4: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a76f81)
Location: net/socket.c:2337
Inline: True
Inline callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff81a76ea0-ffffffff81a76f24: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81bea216)
Location: net/socket.c:2413
Inline: True
Inline callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff81bea100-ffffffff81bea1ab: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d969d0)
Location: net/socket.c:2399
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81d969d0-ffffffff81d96a93: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e05040)
Location: net/socket.c:2436
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81e05040-ffffffff81e05103: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec1900)
Location: net/socket.c:2506
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81ec1900-ffffffff81ec19c3: copy_msghdr_from_user (STB_LOCAL)
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
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba3c88)
Location: net/socket.c:2183
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffff800010ba3c88-ffff800010ba3efc: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc573c)
Location: net/socket.c:2183
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
c0cc573c-c0cc58e4: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c77ad0)
Location: net/socket.c:2183
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
c000000000c77ad0-c000000000c77c88: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073a77a)
Location: net/socket.c:2183
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffe00073a77a-ffffffe00073a86e: copy_msghdr_from_user (STB_LOCAL)
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
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ad860)
Location: net/socket.c:2183
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff818ad860-ffffffff818ad9af: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818677b0)
Location: net/socket.c:2183
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff818677b0-ffffffff818678ff: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fe860)
Location: net/socket.c:2183
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff818fe860-ffffffff818fe9af: copy_msghdr_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191f8e0)
Location: net/socket.c:2183
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff8191f8e0-ffffffff8191fa2f: copy_msghdr_from_user (STB_LOCAL)
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
