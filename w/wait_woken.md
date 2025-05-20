# Function: <code>wait_woken</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int wait_woken(wait_queue_t *wait, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c3840)
Location: kernel/sched/wait.c:326
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
```
**Symbols:**

```
ffffffff810c3840-ffffffff810c38b9: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int wait_woken(wait_queue_t *wait, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c71d0)
Location: kernel/sched/wait.c:326
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
```
**Symbols:**

```
ffffffff810c71d0-ffffffff810c7246: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int wait_woken(wait_queue_t *wait, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810cd030)
Location: kernel/sched/wait.c:314
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff810cd030-ffffffff810cd0a8: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c9aa0)
Location: kernel/sched/wait.c:355
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff810c9aa0-ffffffff810c9b18: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d12c0)
Location: kernel/sched/wait.c:410
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff810d12c0-ffffffff810d1338: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d9810)
Location: kernel/sched/wait.c:407
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff810d9810-ffffffff810d9888: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e3310)
Location: kernel/sched/wait.c:409
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810e3310-ffffffff810e3389: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9f20)
Location: kernel/sched/wait.c:406
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810e9f20-ffffffff810e9f97: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f58f0)
Location: kernel/sched/wait.c:406
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810f58f0-ffffffff810f5967: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fede0)
Location: kernel/sched/wait.c:423
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/mptcp/protocol.c:mptcp_wait_data
```
**Symbols:**

```
ffffffff810fede0-ffffffff810fee5f: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd6e0)
Location: kernel/sched/wait.c:438
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/mptcp/protocol.c:mptcp_wait_data
```
**Symbols:**

```
ffffffff810fd6e0-ffffffff810fd75f: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ffac0)
Location: kernel/sched/wait.c:443
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/skmsg.c:sk_msg_wait_data
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/mptcp/protocol.c:mptcp_wait_data
```
**Symbols:**

```
ffffffff810ffac0-ffffffff810ffb39: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111bbd0)
Location: kernel/sched/wait.c:451
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/unix/unix_bpf.c:unix_msg_wait_data
```
**Symbols:**

```
ffffffff8111bbd0-ffffffff8111bc35: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113d7d0)
Location: kernel/sched/wait.c:450
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff8113d7d0-ffffffff8113d844: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81168340)
Location: kernel/sched/wait.c:454
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81168340-ffffffff811683b4: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81178a00)
Location: kernel/sched/wait.c:449
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
**Symbols:**

```
ffffffff81178a00-ffffffff81178a61: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81186720)
Location: kernel/sched/wait.c:414
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
**Symbols:**

```
ffffffff81186720-ffffffff81186781: wait_woken (STB_GLOBAL)
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
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff800010158140)
Location: kernel/sched/wait.c:406
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffff800010158140-ffff8000101581e8: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a6158)
Location: kernel/sched/wait.c:406
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
c03a6158-c03a6238: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001ad2a0)
Location: kernel/sched/wait.c:406
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
c0000000001ad2a0-c0000000001ad380: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000fee94)
Location: kernel/sched/wait.c:406
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffe0000fee94-ffffffe0000fef0c: wait_woken (STB_GLOBAL)
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
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eecf0)
Location: kernel/sched/wait.c:406
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810eecf0-ffffffff810eed67: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ded70)
Location: kernel/sched/wait.c:406
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810ded70-ffffffff810dede7: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ebe20)
Location: kernel/sched/wait.c:406
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810ebe20-ffffffff810ebe97: wait_woken (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int wait_woken(struct wait_queue_entry *wq_entry, unsigned int mode, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f6e70)
Location: kernel/sched/wait.c:406
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810f6e70-ffffffff810f6ee7: wait_woken (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wait_queue_entry *wq_entry</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_t *wait</code>
</li>
</ul>
</details>
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
