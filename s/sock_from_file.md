# Function: <code>sock_from_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fb680)
Location: net/socket.c:408
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup
  - net/socket.c:sockfd_lookup_light
Direct callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff816fb680-ffffffff816fb6a6: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81763f4b)
Location: net/socket.c:408
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff817620e0-ffffffff81762106: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81790f7b)
Location: net/socket.c:450
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - net/core/scm.c:scm_detach_fds
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff8178f0f0-ffffffff8178f116: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ae89b)
Location: net/socket.c:448
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - net/core/scm.c:scm_detach_fds
```
**Symbols:**

```
ffffffff817ad0f0-ffffffff817ad116: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8182697b)
Location: net/socket.c:454
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - net/core/scm.c:scm_detach_fds
```
**Symbols:**

```
ffffffff818250f0-ffffffff81825116: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186ffee)
Location: net/socket.c:448
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - net/core/scm.c:scm_detach_fds
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff8186f0f0-ffffffff8186f116: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81890bbe)
Location: net/socket.c:427
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - net/core/scm.c:scm_detach_fds
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff8188f5a0-ffffffff8188f5c6: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818daacb)
Location: net/socket.c:438
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/io_uring.c:io_send_recvmsg
  - net/core/scm.c:scm_detach_fds
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff818d9620-ffffffff818d9646: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190cc1b)
Location: net/socket.c:438
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/io_uring.c:io_send_recvmsg
  - net/core/scm.c:scm_detach_fds
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff8190b620-ffffffff8190b646: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1365)
Location: net/socket.c:453
Inline: True
Inline callers:
  - net/socket.c:__sys_connect_file
  - net/socket.c:__sys_accept4_file
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_sendmsg
  - net/core/sock.c:__receive_sock
  - net/core/scm.c:__scm_install_fd
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff819dd810-ffffffff819dd836: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0bb5)
Location: net/socket.c:452
Inline: True
Inline callers:
  - net/socket.c:__sys_connect_file
  - net/socket.c:__sys_accept4_file
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_sendmsg
  - net/core/sock.c:__receive_sock
  - net/core/filter.c:bpf_sock_from_file
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff819dd210-ffffffff819dd230: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c6bf5)
Location: net/socket.c:453
Inline: True
Inline callers:
  - net/socket.c:__sys_connect_file
  - net/socket.c:__sys_accept4_file
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_sendmsg
  - net/core/sock.c:__receive_sock
  - net/core/filter.c:bpf_sock_from_file
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff819c3460-ffffffff819c3480: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a75f45)
Location: net/socket.c:503
Inline: True
Inline callers:
  - net/socket.c:__sys_connect_file
  - net/socket.c:do_accept
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_sendmsg
  - net/core/sock.c:__receive_sock
  - net/core/filter.c:bpf_sock_from_file
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff81a72d10-ffffffff81a72d30: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be8fd5)
Location: net/socket.c:504
Inline: True
Inline callers:
  - net/socket.c:__sys_connect_file
  - net/socket.c:do_accept
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - io_uring/io_uring.c:io_recv
  - io_uring/io_uring.c:io_recvmsg
  - io_uring/io_uring.c:io_send
  - io_uring/io_uring.c:io_sendmsg
  - io_uring/io_uring.c:io_shutdown
  - net/core/sock.c:__receive_sock
  - net/core/filter.c:bpf_sock_from_file
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff81be5510-ffffffff81be553c: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d95745)
Location: net/socket.c:506
Inline: True
Inline callers:
  - net/socket.c:__sys_connect_file
  - net/socket.c:do_accept
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_shutdown
  - net/core/sock.c:__receive_sock
  - net/core/filter.c:bpf_sock_from_file
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff81d91760-ffffffff81d9178c: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e03d75)
Location: net/socket.c:509
Inline: True
Inline callers:
  - net/socket.c:__sys_connect_file
  - net/socket.c:do_accept
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/splice.c:splice_to_socket
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_shutdown
  - io_uring/net.c:io_shutdown
  - net/core/sock.c:__receive_sock
  - net/core/filter.c:bpf_sock_from_file
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff81dffa30-ffffffff81dffa5f: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec07a5)
Location: net/socket.c:511
Inline: True
Inline callers:
  - net/socket.c:__sys_connect_file
  - net/socket.c:do_accept
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/splice.c:splice_to_socket
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_shutdown
  - io_uring/net.c:io_shutdown
  - net/core/sock.c:__receive_sock
  - net/core/filter.c:bpf_sock_from_file
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff81ebbf10-ffffffff81ebbf3f: sock_from_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba1b34)
Location: net/socket.c:438
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_poll_callback
  - fs/io_uring.c:io_send_recvmsg
  - net/core/scm.c:scm_detach_fds
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffff800010ba09f8-ffff800010ba0a50: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc3b7c)
Location: net/socket.c:438
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/io_uring.c:io_send_recvmsg
  - net/core/scm.c:scm_detach_fds
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
c0cc2ea4-c0cc2edc: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c762a4)
Location: net/socket.c:438
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_poll_callback
  - fs/io_uring.c:io_send_recvmsg
  - net/core/scm.c:scm_detach_fds
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
c000000000c74910-c000000000c74958: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000739c28)
Location: net/socket.c:438
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/io_uring.c:io_send_recvmsg
  - net/core/scm.c:scm_detach_fds
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffe000738810-ffffffe00073885c: sock_from_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818acc1b)
Location: net/socket.c:438
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/io_uring.c:io_send_recvmsg
  - net/core/scm.c:scm_detach_fds
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff818ab620-ffffffff818ab646: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81866b6b)
Location: net/socket.c:438
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/io_uring.c:io_send_recvmsg
  - net/core/scm.c:scm_detach_fds
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff81865570-ffffffff81865596: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fdc1b)
Location: net/socket.c:438
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/io_uring.c:io_send_recvmsg
  - net/core/scm.c:scm_detach_fds
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff818fc620-ffffffff818fc646: sock_from_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct socket *sock_from_file(struct file *file, int *err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191ecab)
Location: net/socket.c:438
Inline: True
Inline callers:
  - net/socket.c:sockfd_lookup_light
  - net/socket.c:sockfd_lookup
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_poll_callback
  - fs/io_uring.c:io_send_recvmsg
  - net/core/scm.c:scm_detach_fds
  - net/core/netprio_cgroup.c:update_netprio
  - net/core/netclassid_cgroup.c:update_classid_sock
```
**Symbols:**

```
ffffffff8191d620-ffffffff8191d646: sock_from_file (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *err</code>
</li>
</ul>
</details>
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
