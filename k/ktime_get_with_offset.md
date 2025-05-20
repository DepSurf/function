# Function: <code>ktime_get_with_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f5810)
Location: kernel/time/timekeeping.c:725
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sys.c:do_sysinfo
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/events/core.c:ktime_get_tai_ns
  - kernel/events/core.c:ktime_get_boot_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/char/random.c:init_std_data
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:dev_hard_start_xmit
  - net/compat.c:compat_sock_get_timestamp
  - net/compat.c:compat_sock_get_timestampns
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff810f5810-ffffffff810f58d0: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fc920)
Location: kernel/time/timekeeping.c:730
Inline: False
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/events/core.c:ktime_get_tai_ns
  - kernel/events/core.c:ktime_get_boot_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff810fc920-ffffffff810fc9e4: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810ff840)
Location: kernel/time/timekeeping.c:759
Inline: False
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/events/core.c:ktime_get_tai_ns
  - kernel/events/core.c:ktime_get_boot_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff810ff840-ffffffff810ff904: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81101c70)
Location: kernel/time/timekeeping.c:791
Inline: False
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/events/core.c:ktime_get_tai_ns
  - kernel/events/core.c:ktime_get_boot_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81101c70-ffffffff81101d24: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110cb70)
Location: kernel/time/timekeeping.c:795
Inline: False
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_tai_ns
  - kernel/events/core.c:ktime_get_boot_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff8110cb70-ffffffff8110cc27: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81118590)
Location: kernel/time/timekeeping.c:777
Inline: False
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_tai_ns
  - kernel/events/core.c:ktime_get_boot_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/char/random.c:init_std_data
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81118590-ffffffff81118648: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81123bb0)
Location: kernel/time/timekeeping.c:784
Inline: False
Direct callers:
  - kernel/sys.c:do_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_tai_ns
  - kernel/events/core.c:ktime_get_boot_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81123bb0-ffffffff81123c68: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:790
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sys.c:do_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff8112f7c4-ffffffff8112f7d7: ktime_get_with_offset.cold (STB_LOCAL)
ffffffff8112eab0-ffffffff8112eb5d: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113aa60)
Location: kernel/time/timekeeping.c:790
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sys.c:do_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff8113aa60-ffffffff8113ab14: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81149760)
Location: kernel/time/timekeeping.c:790
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81149760-ffffffff8114981b: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81146030)
Location: kernel/time/timekeeping.c:860
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81146030-ffffffff811460eb: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81146b10)
Location: kernel/time/timekeeping.c:860
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/char/random.c:rand_initialize
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81146b10-ffffffff81146bc9: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:860
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/char/random.c:rand_initialize
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
**Symbols:**

```
ffffffff81cb0d76-ffffffff81cb0d9a: ktime_get_with_offset.cold (STB_LOCAL)
ffffffff81169b60-ffffffff81169c43: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:879
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/devlink.c:devlink_health_do_dump
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff81e622dd-ffffffff81e62301: ktime_get_with_offset.cold (STB_LOCAL)
ffffffff8119d760-ffffffff8119d849: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:879
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/regulator/core.c:set_machine_constraints
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/devlink.c:devlink_health_do_dump
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff8205b14e-ffffffff8205b172: ktime_get_with_offset.cold (STB_LOCAL)
ffffffff811dc3d0-ffffffff811dc4b9: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:879
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/devlink/health.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff820d99e2-ffffffff820d9a06: ktime_get_with_offset.cold (STB_LOCAL)
ffffffff811f07e0-ffffffff811f08c9: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:879
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:get_boottime_timespec
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai_ktime
  - kernel/time/posix-timers.c:posix_get_tai_timespec
  - kernel/time/posix-timers.c:posix_get_boottime_ktime
  - kernel/time/posix-timers.c:posix_get_boottime_timespec
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
  - drivers/regulator/core.c:_regulator_do_disable
  - drivers/regulator/core.c:_regulator_do_enable
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/exthdrs.c:ipv6_dest_hao
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/devlink/health.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff821b52e1-ffffffff821b5305: ktime_get_with_offset.cold (STB_LOCAL)
ffffffff81206920-ffffffff81206a09: ktime_get_with_offset (STB_GLOBAL)
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
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a2f30)
Location: kernel/time/timekeeping.c:790
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sys.c:do_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffff8000101a2f30-ffff8000101a2fec: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ecdd0)
Location: kernel/time/timekeeping.c:790
Inline: False
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_trace_trigger_cpu
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - kernel/fork.c:copy_process
  - kernel/sys.c:__se_sys_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter
  - drivers/net/ethernet/ti/cpts.c:cpts_register
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
c03ecdd0-c03ecf30: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000204750)
Location: kernel/time/timekeeping.c:790
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sys.c:do_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
c000000000204750-c00000000020485c: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00012fbc0)
Location: kernel/time/timekeeping.c:790
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffe00012fbc0-ffffffe00012fc6c: ktime_get_with_offset (STB_GLOBAL)
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
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81133210)
Location: kernel/time/timekeeping.c:790
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sys.c:do_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81133210-ffffffff811332c4: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81125c70)
Location: kernel/time/timekeeping.c:790
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sys.c:do_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/nvme/host/core.c:nvme_init_identify
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81125c70-ffffffff81125d24: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81130f30)
Location: kernel/time/timekeeping.c:790
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sys.c:do_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_start
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_conntrack
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81130f30-ffffffff81130fe4: ktime_get_with_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ktime_t ktime_get_with_offset(enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113d950)
Location: kernel/time/timekeeping.c:790
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/sys.c:do_sysinfo
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/time/hrtimer.c:ktime_get_clocktai
  - kernel/time/hrtimer.c:ktime_get_boottime
  - kernel/time/hrtimer.c:ktime_get_real
  - kernel/time/alarmtimer.c:ktime_get_boottime
  - kernel/time/alarmtimer.c:ktime_get_real
  - kernel/time/posix-timers.c:posix_get_tai
  - kernel/time/posix-timers.c:posix_get_boottime
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/events/core.c:ktime_get_clocktai_ns
  - kernel/events/core.c:ktime_get_boottime_ns
  - kernel/events/core.c:ktime_get_real_ns
  - fs/proc/uptime.c:uptime_proc_show
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
  - drivers/char/random.c:init_std_data
  - drivers/usb/host/ehci-hcd.c:ehci_run
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - net/socket.c:__sock_recv_timestamp
  - net/core/sock.c:sock_gettstamp
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff8113d950-ffffffff8113da04: ktime_get_with_offset (STB_GLOBAL)
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
