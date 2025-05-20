# Function: <code>get_compat_msghdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8173ee10)
Location: net/compat.c:34
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/socket.c:___sys_recvmsg
```
**Symbols:**

```
ffffffff8173ee10-ffffffff8173efc8: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817abac0)
Location: net/compat.c:34
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff817abac0-ffffffff817abc76: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817db0e0)
Location: net/compat.c:34
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff817db0e0-ffffffff817db296: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817fa760)
Location: net/compat.c:35
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff817fa760-ffffffff817fa8a6: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818780d0)
Location: net/compat.c:35
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff818780d0-ffffffff81878216: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818ca290)
Location: net/compat.c:35
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff818ca290-ffffffff818ca3d1: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818f5360)
Location: net/compat.c:35
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff818f5360-ffffffff818f54a5: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81954a30)
Location: net/compat.c:36
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81954a30-ffffffff81954b84: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8198ae50)
Location: net/compat.c:36
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff8198ae50-ffffffff8198afa4: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81a62c30)
Location: net/compat.c:88
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:recvmsg_copy_msghdr
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff81a62c30-ffffffff81a62cb6: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81a6ad50)
Location: net/compat.c:88
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:recvmsg_copy_msghdr
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff81a6ad50-ffffffff81a6add6: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81a53480)
Location: net/compat.c:88
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:recvmsg_copy_msghdr
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff81a53480-ffffffff81a53503: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81b0c190)
Location: net/compat.c:88
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:recvmsg_copy_msghdr
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff81b0c190-ffffffff81b0c213: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81c928d0)
Location: net/compat.c:88
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:recvmsg_copy_msghdr
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff81c928d0-ffffffff81c92973: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81e4deb0)
Location: net/compat.c:83
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:recvmsg_copy_msghdr
  - net/socket.c:___sys_sendmsg
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff81e4deb0-ffffffff81e4df80: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81ea9540)
Location: net/compat.c:83
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:recvmsg_copy_msghdr
  - net/socket.c:___sys_sendmsg
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff81ea9540-ffffffff81ea9610: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81f6c000)
Location: net/compat.c:83
Inline: False
Direct callers:
  - net/socket.c:___sys_recvmsg
  - net/socket.c:recvmsg_copy_msghdr
  - net/socket.c:___sys_sendmsg
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff81f6c000-ffffffff81f6c0d0: get_compat_msghdr (STB_GLOBAL)
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
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffff800010c34ec8)
Location: net/compat.c:36
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffff800010c34ec8-ffff800010c35140: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (c000000000d2d660)
Location: net/compat.c:36
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
c000000000d2d660-c000000000d2d818: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8192acc0)
Location: net/compat.c:36
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff8192acc0-ffffffff8192ae14: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818e4a70)
Location: net/compat.c:36
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff818e4a70-ffffffff818e4bc4: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8197be50)
Location: net/compat.c:36
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff8197be50-ffffffff8197bfa4: get_compat_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_compat_msghdr(struct msghdr *kmsg, struct compat_msghdr *umsg, struct sockaddr **save_addr, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8199e3a0)
Location: net/compat.c:36
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmsg_sock
  - net/socket.c:___sys_recvmsg
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff8199e3a0-ffffffff8199e4f4: get_compat_msghdr (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
