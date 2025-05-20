# Function: <code>sockfd_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fca20)
Location: net/socket.c:431
Inline: False
Direct callers:
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff816fca20-ffffffff816fca6d: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81763590)
Location: net/socket.c:431
Inline: False
Direct callers:
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81763590-ffffffff817635dd: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817905d0)
Location: net/socket.c:473
Inline: False
Direct callers:
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817905d0-ffffffff8179061d: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817adcd0)
Location: net/socket.c:471
Inline: False
Direct callers:
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817adcd0-ffffffff817add1d: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81825b50)
Location: net/socket.c:477
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:sock_map_update_elem
  - net/compat.c:compat_SyS_socketcall
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81825b50-ffffffff81825b9d: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186f6b0)
Location: net/socket.c:471
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/sockmap.c:sock_hash_update_elem
  - kernel/bpf/sockmap.c:sock_map_update_elem
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff8186f6b0-ffffffff8186f6fd: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81890260)
Location: net/socket.c:450
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81890260-ffffffff818902ad: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818da0f0)
Location: net/socket.c:461
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff818da0f0-ffffffff818da13d: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190c0d0)
Location: net/socket.c:461
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff8190c0d0-ffffffff8190c11d: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de320)
Location: net/socket.c:476
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff819de320-ffffffff819de373: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819ddd80)
Location: net/socket.c:474
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff819ddd80-ffffffff819dddd3: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c3d90)
Location: net/socket.c:475
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff819c3d90-ffffffff819c3de3: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a73110)
Location: net/socket.c:525
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81a73110-ffffffff81a73163: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be5aa0)
Location: net/socket.c:526
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81be5aa0-ffffffff81be5b01: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d91d80)
Location: net/socket.c:528
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81d91d80-ffffffff81d91de1: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e00070)
Location: net/socket.c:531
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/handshake/netlink.c:handshake_nl_done_doit
```
**Symbols:**

```
ffffffff81e00070-ffffffff81e000d4: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebc510)
Location: net/socket.c:533
Inline: False
Direct callers:
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xskmap.c:xsk_map_update_elem
  - net/handshake/netlink.c:handshake_nl_done_doit
```
**Symbols:**

```
ffffffff81ebc510-ffffffff81ebc574: sockfd_lookup (STB_GLOBAL)
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
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba1190)
Location: net/socket.c:461
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffff800010ba1190-ffff800010ba1214: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc34e8)
Location: net/socket.c:461
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
c0cc34e8-c0cc3558: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c75610)
Location: net/socket.c:461
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
c000000000c75610-c000000000c756bc: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000739210)
Location: net/socket.c:461
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffe000739210-ffffffe000739280: sockfd_lookup (STB_GLOBAL)
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
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ac0d0)
Location: net/socket.c:461
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff818ac0d0-ffffffff818ac11d: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81866020)
Location: net/socket.c:461
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81866020-ffffffff8186606d: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fd0d0)
Location: net/socket.c:461
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff818fd0d0-ffffffff818fd11d: sockfd_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct socket *sockfd_lookup(int fd, int *err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191e140)
Location: net/socket.c:461
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
  - kernel/bpf/reuseport_array.c:bpf_fd_reuseport_array_update_elem
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/compat.c:__compat_sys_getsockopt
  - net/compat.c:__compat_sys_setsockopt
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff8191e140-ffffffff8191e18d: sockfd_lookup (STB_GLOBAL)
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
