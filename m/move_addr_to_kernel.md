# Function: <code>move_addr_to_kernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff816fe300)
Location: net/socket.c:188
Inline: True
Inline callers:
  - net/socket.c:SYSC_bind
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_sendto
  - net/socket.c:copy_msghdr_from_user
Direct callers:
  - net/socket.c:SYSC_bind
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_sendto
  - net/socket.c:copy_msghdr_from_user
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff816fe300-ffffffff816fe35f: move_addr_to_kernel.part.14 (STB_LOCAL)
ffffffff816fed40-ffffffff816fed65: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff81765283)
Location: net/socket.c:188
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_bind
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81764cf0-ffffffff81764d66: move_addr_to_kernel.part.16 (STB_LOCAL)
ffffffff81765790-ffffffff817657b5: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff81792303)
Location: net/socket.c:188
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_bind
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81791d70-ffffffff81791de6: move_addr_to_kernel.part.17 (STB_LOCAL)
ffffffff81792810-ffffffff81792835: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff817b0705)
Location: net/socket.c:188
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_bind
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff817b01f0-ffffffff817b026a: move_addr_to_kernel.part.19 (STB_LOCAL)
ffffffff817b0c90-ffffffff817b0cb6: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff81828895)
Location: net/socket.c:188
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:SYSC_sendto
  - net/socket.c:SYSC_connect
  - net/socket.c:SYSC_bind
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81828370-ffffffff818283ea: move_addr_to_kernel.part.18 (STB_LOCAL)
ffffffff81828e20-ffffffff81828e46: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff818712ea)
Location: net/socket.c:182
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81871170-ffffffff818711e3: move_addr_to_kernel.part.21 (STB_LOCAL)
ffffffff81872430-ffffffff81872455: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff81892555)
Location: net/socket.c:182
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff818923e0-ffffffff81892453: move_addr_to_kernel.part.20 (STB_LOCAL)
ffffffff81892d80-ffffffff81892da5: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff818dc805)
Location: net/socket.c:178
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff818dc680-ffffffff818dc6f5: move_addr_to_kernel.part.0 (STB_LOCAL)
ffffffff818dd070-ffffffff818dd095: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff8190d965)
Location: net/socket.c:178
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff8190d7e0-ffffffff8190d855: move_addr_to_kernel.part.0 (STB_LOCAL)
ffffffff8190f0d0-ffffffff8190f0f5: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff819e1df4)
Location: net/socket.c:192
Inline: True
Inline callers:
  - net/socket.c:__copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - fs/io_uring.c:io_connect
  - fs/io_uring.c:io_connect_prep
  - net/socket.c:__copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:__get_compat_msghdr
```
**Symbols:**

```
ffffffff819dff40-ffffffff819dffbd: move_addr_to_kernel.part.0 (STB_LOCAL)
ffffffff819e09d0-ffffffff819e09f5: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff819e1a94)
Location: net/socket.c:192
Inline: True
Inline callers:
  - net/socket.c:__copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_connect
  - net/socket.c:__copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:__get_compat_msghdr
```
**Symbols:**

```
ffffffff819df700-ffffffff819df77d: move_addr_to_kernel.part.0 (STB_LOCAL)
ffffffff819e0220-ffffffff819e0245: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff819c7b23)
Location: net/socket.c:192
Inline: True
Inline callers:
  - net/socket.c:__copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - fs/io_uring.c:io_connect
  - net/socket.c:__copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:__get_compat_msghdr
```
**Symbols:**

```
ffffffff819c6190-ffffffff819c6205: move_addr_to_kernel.part.0 (STB_LOCAL)
ffffffff819c6280-ffffffff819c62a5: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff81a76e73)
Location: net/socket.c:242
Inline: True
Inline callers:
  - net/socket.c:__copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - fs/io_uring.c:io_connect
  - net/socket.c:__copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:__get_compat_msghdr
```
**Symbols:**

```
ffffffff81a741e0-ffffffff81a74255: move_addr_to_kernel.part.0 (STB_LOCAL)
ffffffff81a74e50-ffffffff81a74e75: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be7b90)
Location: net/socket.c:243
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_connect
  - net/socket.c:__copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:__get_compat_msghdr
```
**Symbols:**

```
ffffffff81be7b90-ffffffff81be7c3f: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d94240)
Location: net/socket.c:243
Inline: False
Direct callers:
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_connect_prep_async
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send
  - io_uring/net.c:io_send_prep_async
  - net/socket.c:__copy_msghdr
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:__get_compat_msghdr
```
**Symbols:**

```
ffffffff81d94240-ffffffff81d942ef: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e02890)
Location: net/socket.c:245
Inline: False
Direct callers:
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_connect_prep_async
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send
  - io_uring/net.c:io_send_prep_async
  - net/socket.c:__copy_msghdr
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:__get_compat_msghdr
```
**Symbols:**

```
ffffffff81e02890-ffffffff81e0293f: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebf290)
Location: net/socket.c:247
Inline: False
Direct callers:
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_connect_prep_async
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send
  - io_uring/net.c:io_send_prep_async
  - net/socket.c:__copy_msghdr
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:__get_compat_msghdr
```
**Symbols:**

```
ffffffff81ebf290-ffffffff81ebf33f: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffff800010ba3ec0)
Location: net/socket.c:178
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffff800010ba3ac8-ffff800010ba3c88: move_addr_to_kernel.part.0 (STB_LOCAL)
ffff800010ba71c8-ffff800010ba7224: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc5638)
Location: net/socket.c:178
Inline: False
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
```
**Symbols:**

```
c0cc5638-c0cc573c: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (c000000000c77c24)
Location: net/socket.c:178
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
c000000000c77a00-c000000000c77ac8: move_addr_to_kernel.part.0 (STB_LOCAL)
c000000000c7b500-c000000000c7b548: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffe00073a83a)
Location: net/socket.c:178
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
```
**Symbols:**

```
ffffffe00073a714-ffffffe00073a77a: move_addr_to_kernel.part.0 (STB_LOCAL)
ffffffe00073ad04-ffffffe00073ad4e: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff818ad965)
Location: net/socket.c:178
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff818ad7e0-ffffffff818ad855: move_addr_to_kernel.part.0 (STB_LOCAL)
ffffffff818af0d0-ffffffff818af0f5: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff818678b5)
Location: net/socket.c:178
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff81867730-ffffffff818677a5: move_addr_to_kernel.part.0 (STB_LOCAL)
ffffffff81869020-ffffffff81869045: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff818fe965)
Location: net/socket.c:178
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff818fe7e0-ffffffff818fe855: move_addr_to_kernel.part.0 (STB_LOCAL)
ffffffff819000d0-ffffffff819000f5: move_addr_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int move_addr_to_kernel(void *uaddr, int ulen, struct __kernel_sockaddr_storage *kaddr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/socket.c (ffffffff8191f9e5)
Location: net/socket.c:178
Inline: True
Inline callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
Direct callers:
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:__sys_sendto
  - net/socket.c:__sys_connect
  - net/socket.c:__sys_bind
  - net/compat.c:get_compat_msghdr
```
**Symbols:**

```
ffffffff8191f860-ffffffff8191f8d5: move_addr_to_kernel.part.0 (STB_LOCAL)
ffffffff819210c0-ffffffff819210e5: move_addr_to_kernel (STB_GLOBAL)
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
