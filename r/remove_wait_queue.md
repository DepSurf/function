# Function: <code>remove_wait_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void remove_wait_queue(wait_queue_head_t *q, wait_queue_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c32a0)
Location: kernel/sched/wait.c:45
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_log_start
  - mm/huge_memory.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/rtc-dev.c:rtc_dev_read
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
```
**Symbols:**

```
ffffffff810c32a0-ffffffff810c32f2: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void remove_wait_queue(wait_queue_head_t *q, wait_queue_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c6c30)
Location: kernel/sched/wait.c:45
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - kernel/audit.c:audit_log_start
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/rtc-dev.c:rtc_dev_read
  - drivers/md/dm.c:dm_wait_for_completion
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
```
**Symbols:**

```
ffffffff810c6c30-ffffffff810c6c82: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void remove_wait_queue(wait_queue_head_t *q, wait_queue_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ccc10)
Location: kernel/sched/wait.c:45
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/rtc-dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff810ccc10-ffffffff810ccc62: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c94d0)
Location: kernel/sched/wait.c:46
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/rtc-dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff810c94d0-ffffffff810c9522: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d0bc0)
Location: kernel/sched/wait.c:46
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/rtc-dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff810d0bc0-ffffffff810d0c12: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d9100)
Location: kernel/sched/wait.c:39
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - kernel/bpf/sockmap.c:bpf_tcp_recvmsg
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/rtc-dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff810d9100-ffffffff810d9152: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e2c00)
Location: kernel/sched/wait.c:39
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810e2c00-ffffffff810e2c52: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9810)
Location: kernel/sched/wait.c:40
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810e9810-ffffffff810e985c: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f51e0)
Location: kernel/sched/wait.c:40
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810f51e0-ffffffff810f522c: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fe900)
Location: kernel/sched/wait.c:40
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_dequeue
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/mptcp/protocol.c:mptcp_wait_data
```
**Symbols:**

```
ffffffff810fe900-ffffffff810fe94c: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd280)
Location: kernel/sched/wait.c:51
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_dequeue
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/mptcp/protocol.c:mptcp_wait_data
```
**Symbols:**

```
ffffffff810fd280-ffffffff810fd2cc: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ff640)
Location: kernel/sched/wait.c:51
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region_locked
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_dequeue
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/core/skmsg.c:sk_msg_wait_data
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/mptcp/protocol.c:mptcp_wait_data
```
**Symbols:**

```
ffffffff810ff640-ffffffff810ff68c: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111b730)
Location: kernel/sched/wait.c:51
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region_locked
  - kernel/audit.c:audit_receive
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_dequeue
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/unix/unix_bpf.c:unix_msg_wait_data
```
**Symbols:**

```
ffffffff8111b730-ffffffff8111b77c: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113b9a0)
Location: kernel/sched/wait.c:50
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region_locked
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/signalfd.c:signalfd_dequeue
  - drivers/pci/vgaarb.c:vga_get
  - drivers/pci/vgaarb.c:vga_get
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff8113b9a0-ffffffff8113b9f8: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81166410)
Location: kernel/sched/wait.c:50
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region_locked
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - fs/signalfd.c:signalfd_dequeue
  - drivers/pci/vgaarb.c:vga_get
  - drivers/pci/vgaarb.c:vga_get
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81166410-ffffffff81166468: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81176880)
Location: kernel/sched/wait.c:50
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region_locked
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_clear_and_put
  - fs/eventpoll.c:__ep_remove
  - fs/signalfd.c:signalfd_dequeue
  - drivers/pci/vgaarb.c:vga_get
  - drivers/pci/vgaarb.c:vga_get
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
**Symbols:**

```
ffffffff81176880-ffffffff811768d8: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81184b00)
Location: kernel/sched/wait.c:50
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region_locked
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/eventpoll.c:ep_clear_and_put
  - fs/eventpoll.c:__ep_remove
  - fs/signalfd.c:signalfd_dequeue
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_cb
  - io_uring/waitid.c:io_waitid_cb
  - drivers/pci/vgaarb.c:vga_get
  - drivers/pci/vgaarb.c:vga_get
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/net/tun.c:tun_ring_recv
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:inet_wait_for_connect
  - net/ipv4/tcp_bpf.c:tcp_msg_wait_data
  - net/ipv4/udp_bpf.c:udp_msg_wait_data
```
**Symbols:**

```
ffffffff81184b00-ffffffff81184b58: remove_wait_queue (STB_GLOBAL)
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
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff8000101587e0)
Location: kernel/sched/wait.c:40
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffff8000101587e0-ffff80001015889c: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a5818)
Location: kernel/sched/wait.c:40
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - sound/core/control.c:snd_ctl_read
  - sound/core/timer.c:snd_timer_user_read
  - sound/core/pcm_native.c:snd_pcm_drain
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
c03a5818-c03a5868: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001ac720)
Location: kernel/sched/wait.c:40
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
c0000000001ac720-c0000000001ac7bc: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000fe7c6)
Location: kernel/sched/wait.c:40
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffe0000fe7c6-ffffffe0000fe816: remove_wait_queue (STB_GLOBAL)
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
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ee5e0)
Location: kernel/sched/wait.c:40
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810ee5e0-ffffffff810ee62c: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810de670)
Location: kernel/sched/wait.c:40
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810de670-ffffffff810de6bc: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eb710)
Location: kernel/sched/wait.c:40
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810eb710-ffffffff810eb75c: remove_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void remove_wait_queue(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f6770)
Location: kernel/sched/wait.c:40
Inline: False
Direct callers:
  - kernel/exit.c:do_wait
  - kernel/resource.c:__request_region
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:memcg_event_remove
  - fs/select.c:poll_freewait
  - fs/select.c:poll_freewait
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_read
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_write
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/char/hpet.c:hpet_read
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/gpu/vga/vgaarb.c:vga_get
  - drivers/net/tun.c:tun_do_read
  - drivers/net/tun.c:tun_do_read
  - drivers/net/ppp/ppp_generic.c:ppp_read
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/usb/core/devio.c:reap_as
  - drivers/rtc/dev.c:rtc_dev_read
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:__mmc_claim_host
  - net/core/sock.c:sk_wait_data
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/dev.c:default_device_exit_batch
  - net/core/rtnetlink.c:rtnl_link_unregister
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff810f6770-ffffffff810f67bc: remove_wait_queue (STB_GLOBAL)
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
