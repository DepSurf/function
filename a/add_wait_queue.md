# Function: <code>add_wait_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void add_wait_queue(wait_queue_head_t *q, wait_queue_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c3200)
Location: kernel/sched/wait.c:23
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/huge_memory.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/rtc-dev.c:rtc_dev_read
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
```
**Symbols:**

```
ffffffff810c3200-ffffffff810c3249: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void add_wait_queue(wait_queue_head_t *q, wait_queue_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c6b90)
Location: kernel/sched/wait.c:23
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/rtc-dev.c:rtc_dev_read
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff810c6b90-ffffffff810c6bd9: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void add_wait_queue(wait_queue_head_t *q, wait_queue_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ccb70)
Location: kernel/sched/wait.c:23
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/rtc-dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff810ccb70-ffffffff810ccbb9: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c9430)
Location: kernel/sched/wait.c:24
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/rtc-dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff810c9430-ffffffff810c9478: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d0b20)
Location: kernel/sched/wait.c:24
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/rtc-dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff810d0b20-ffffffff810d0b69: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d9060)
Location: kernel/sched/wait.c:17
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/rtc-dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff810d9060-ffffffff810d90a9: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e2b60)
Location: kernel/sched/wait.c:17
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/aio.c:aio_poll_complete_work
  - lib/sbitmap.c:sbitmap_add_wait_queue
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810e2b60-ffffffff810e2ba9: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9770)
Location: kernel/sched/wait.c:18
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/aio.c:aio_poll_complete_work
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_poll_complete_work
  - lib/sbitmap.c:sbitmap_add_wait_queue
  - lib/sbitmap.c:sbitmap_add_wait_queue
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810e9770-ffffffff810e97b9: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f5140)
Location: kernel/sched/wait.c:18
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/aio.c:aio_poll_complete_work
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_poll_complete_work
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/virqfd.c:virqfd_ptable_queue_proc
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810f5140-ffffffff810f5189: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fe860)
Location: kernel/sched/wait.c:18
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_dequeue
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/aio.c:aio_poll_complete_work
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_async_queue_proc
  - fs/io_uring.c:io_poll_rewait
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/virqfd.c:virqfd_ptable_queue_proc
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/mptcp/protocol.c:mptcp_wait_data
```
**Symbols:**

```
ffffffff810fe860-ffffffff810fe8a9: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fda40)
Location: kernel/sched/wait.c:18
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_dequeue
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/aio.c:aio_poll_complete_work
  - fs/io_uring.c:__io_queue_proc
  - fs/io_uring.c:io_poll_rewait
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/virqfd.c:virqfd_ptable_queue_proc
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/mptcp/protocol.c:mptcp_wait_data
```
**Symbols:**

```
ffffffff810fda40-ffffffff810fdab8: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ffd80)
Location: kernel/sched/wait.c:18
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region_locked
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_dequeue
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/aio.c:aio_poll_complete_work
  - fs/io_uring.c:__io_queue_proc
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_poll_rewait
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/virqfd.c:virqfd_ptable_queue_proc
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/skmsg.c:sk_msg_wait_data
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/mptcp/protocol.c:mptcp_wait_data
```
**Symbols:**

```
ffffffff810ffd80-ffffffff810ffdf5: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111be60)
Location: kernel/sched/wait.c:18
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region_locked
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_dequeue
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/io_uring.c:__io_queue_proc
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_poll_rewait
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/virqfd.c:virqfd_ptable_queue_proc
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/unix/unix_bpf.c:unix_msg_wait_data
```
**Symbols:**

```
ffffffff8111be60-ffffffff8111bed5: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81141620)
Location: kernel/sched/wait.c:17
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region_locked
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_dequeue
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/aio.c:aio_poll_queue_proc
  - io_uring/io_uring.c:__io_queue_proc
  - drivers/pci/vgaarb.c:vga_get
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/virqfd.c:virqfd_ptable_queue_proc
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81141620-ffffffff811416a9: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116c6d0)
Location: kernel/sched/wait.c:17
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region_locked
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_dequeue
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/aio.c:aio_poll_queue_proc
  - io_uring/poll.c:__io_queue_proc
  - drivers/pci/vgaarb.c:vga_get
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff8116c6d0-ffffffff8116c759: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117cc80)
Location: kernel/sched/wait.c:17
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region_locked
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_dequeue
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/aio.c:aio_poll_queue_proc
  - io_uring/poll.c:__io_queue_proc
  - drivers/pci/vgaarb.c:vga_get
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
**Symbols:**

```
ffffffff8117cc80-ffffffff8117cd09: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118a9b0)
Location: kernel/sched/wait.c:17
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region_locked
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_dequeue
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/aio.c:aio_poll_queue_proc
  - io_uring/poll.c:__io_queue_proc
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_cb
  - drivers/pci/vgaarb.c:vga_get
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
**Symbols:**

```
ffffffff8118a9b0-ffffffff8118aa39: add_wait_queue (STB_GLOBAL)
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
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff800010158960)
Location: kernel/sched/wait.c:18
Inline: False
Direct callers:
  - virt/kvm/eventfd.c:irqfd_ptable_queue_proc
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/aio.c:aio_poll_complete_work
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_poll_complete_work
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffff800010158960-ffff800010158a20: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a5770)
Location: kernel/sched/wait.c:18
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/aio.c:aio_poll_complete_work
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_poll_complete_work
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - sound/core/control.c:snd_ctl_read
  - sound/core/timer.c:snd_timer_user_read
  - sound/core/pcm_native.c:snd_pcm_drain
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
c03a5770-c03a57c4: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001ac600)
Location: kernel/sched/wait.c:18
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - fs/userfaultfd.c:userfaultfd_ctx_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/aio.c:aio_poll_complete_work
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_poll_complete_work
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/virqfd.c:virqfd_ptable_queue_proc
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
c0000000001ac600-c0000000001ac684: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000fe70c)
Location: kernel/sched/wait.c:18
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/aio.c:aio_poll_complete_work
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_poll_complete_work
  - lib/sbitmap.c:sbitmap_add_wait_queue
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffe0000fe70c-ffffffe0000fe768: add_wait_queue (STB_GLOBAL)
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
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ee540)
Location: kernel/sched/wait.c:18
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/aio.c:aio_poll_complete_work
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_poll_complete_work
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810ee540-ffffffff810ee589: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810de5d0)
Location: kernel/sched/wait.c:18
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/aio.c:aio_poll_complete_work
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_poll_complete_work
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/virqfd.c:virqfd_ptable_queue_proc
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810de5d0-ffffffff810de619: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eb670)
Location: kernel/sched/wait.c:18
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/aio.c:aio_poll_complete_work
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_poll_complete_work
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/virqfd.c:virqfd_ptable_queue_proc
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810eb670-ffffffff810eb6b9: add_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void add_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f66d0)
Location: kernel/sched/wait.c:18
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_ptable_queue_proc
  - fs/select.c:__pollwait
  - fs/dcache.c:d_alloc_parallel
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/signalfd.c:signalfd_read
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_poll_queue_proc
  - fs/aio.c:aio_poll_complete_work
  - fs/io_uring.c:io_poll_queue_proc
  - fs/io_uring.c:io_poll_complete_work
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/virqfd.c:virqfd_ptable_queue_proc
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810f66d0-ffffffff810f6719: add_wait_queue (STB_GLOBAL)
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
<code>struct wait_queue_head *wq_head</code>
</li>
<li>
<b>Param added. </b>
<code>struct wait_queue_entry *wq_entry</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_head_t *q</code>
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
