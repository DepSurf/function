# Function: <code>__copy_msghdr_from_user</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **uiov, size_t *nsegs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1ce0)
Location: net/socket.c:2226
Inline: False
Direct callers:
  - fs/io_uring.c:__io_recvmsg_copy_hdr
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff819e1ce0-ffffffff819e1e28: __copy_msghdr_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **uiov, size_t *nsegs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1980)
Location: net/socket.c:2219
Inline: False
Direct callers:
  - fs/io_uring.c:__io_recvmsg_copy_hdr
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff819e1980-ffffffff819e1ac8: __copy_msghdr_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **uiov, size_t *nsegs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c7a20)
Location: net/socket.c:2213
Inline: False
Direct callers:
  - fs/io_uring.c:__io_recvmsg_copy_hdr
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff819c7a20-ffffffff819c7b50: __copy_msghdr_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **uiov, size_t *nsegs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a76d70)
Location: net/socket.c:2286
Inline: False
Direct callers:
  - fs/io_uring.c:__io_recvmsg_copy_hdr
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff81a76d70-ffffffff81a76ea0: __copy_msghdr_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __copy_msghdr_from_user(struct msghdr *kmsg, struct user_msghdr *umsg, struct sockaddr **save_addr, struct iovec **uiov, size_t *nsegs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be9f90)
Location: net/socket.c:2361
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_recvmsg_copy_hdr
  - net/socket.c:___sys_recvmsg
  - net/socket.c:sendmsg_copy_msghdr
```
**Symbols:**

```
ffffffff81be9f90-ffffffff81bea0f3: __copy_msghdr_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
