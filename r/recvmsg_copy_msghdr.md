# Function: <code>recvmsg_copy_msghdr</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81910812)
Location: net/socket.c:2486
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int recvmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct sockaddr **uaddr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1f05)
Location: net/socket.c:2528
Inline: True
Inline callers:
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff819e2b40-ffffffff819e2b81: recvmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int recvmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct sockaddr **uaddr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1ba5)
Location: net/socket.c:2521
Inline: True
Inline callers:
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff819e27a0-ffffffff819e27e1: recvmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int recvmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct sockaddr **uaddr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c7c29)
Location: net/socket.c:2511
Inline: True
Inline callers:
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff819c8810-ffffffff819c884b: recvmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int recvmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct sockaddr **uaddr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a76f79)
Location: net/socket.c:2584
Inline: True
Inline callers:
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff81a77b60-ffffffff81a77b9b: recvmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int recvmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct sockaddr **uaddr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81bea20a)
Location: net/socket.c:2660
Inline: True
Inline callers:
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff81beb000-ffffffff81beb057: recvmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int recvmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct sockaddr **uaddr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d96b09)
Location: net/socket.c:2648
Inline: True
Inline callers:
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff81d97930-ffffffff81d97987: recvmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int recvmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct sockaddr **uaddr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e05179)
Location: net/socket.c:2686
Inline: True
Inline callers:
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff81e05fa0-ffffffff81e05ff7: recvmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int recvmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct sockaddr **uaddr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec1a39)
Location: net/socket.c:2756
Inline: True
Inline callers:
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff81ec2860-ffffffff81ec28b7: recvmsg_copy_msghdr (STB_GLOBAL)
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
In net/socket.c (ffff800010ba8a1c)
Location: net/socket.c:2486
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
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
In net/socket.c (c0cc73a0)
Location: net/socket.c:2486
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
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
In net/socket.c (c000000000c7d234)
Location: net/socket.c:2486
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
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
In net/socket.c (ffffffe00073c098)
Location: net/socket.c:2486
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
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
In net/socket.c (ffffffff818b0812)
Location: net/socket.c:2486
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
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
In net/socket.c (ffffffff8186a762)
Location: net/socket.c:2486
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
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
In net/socket.c (ffffffff81901812)
Location: net/socket.c:2486
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
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
In net/socket.c (ffffffff819227b2)
Location: net/socket.c:2486
Inline: True
Inline callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
