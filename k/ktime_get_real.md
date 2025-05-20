# Function: <code>ktime_get_real</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810eeb20)
Location: include/linux/timekeeping.h:177
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff810facf0)
Location: include/linux/timekeeping.h:177
Inline: False
```
```
In kernel/events/core.c (ffffffff81179821)
Location: include/linux/timekeeping.h:177
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/char/random.c (ffffffff81513d81)
Location: include/linux/timekeeping.h:177
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81634131)
Location: include/linux/timekeeping.h:177
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/input/evdev.c (ffffffff8166d218)
Location: include/linux/timekeeping.h:177
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In net/socket.c (ffffffff816fce18)
Location: include/linux/timekeeping.h:177
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81704ace)
Location: include/linux/timekeeping.h:177
Inline: True
Inline callers:
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_get_timestampns
```
```
In net/core/skbuff.c (ffffffff81707030)
Location: include/linux/timekeeping.h:177
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff81711247)
Location: include/linux/timekeeping.h:177
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_tcp_sequence_number
```
```
In net/core/dev.c (ffffffff817195fa)
Location: include/linux/timekeeping.h:177
Inline: True
Inline callers:
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:dev_hard_start_xmit
```
```
In net/compat.c (ffffffff8173e471)
Location: include/linux/timekeeping.h:177
Inline: True
Inline callers:
  - net/compat.c:compat_sock_get_timestamp
  - net/compat.c:compat_sock_get_timestampns
```
```
In net/ipv4/tcp_cubic.c (ffffffff817ac951)
Location: include/linux/timekeeping.h:177
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (ffffffff817c1d34)
Location: include/linux/timekeeping.h:177
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff817f32d2)
Location: include/linux/timekeeping.h:177
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff810eeb20-ffffffff810eeb2d: ktime_get_real (STB_LOCAL)
ffffffff810facf0-ffffffff810facfd: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810f5b00)
Location: include/linux/timekeeping.h:193
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff81101fe0)
Location: include/linux/timekeeping.h:193
Inline: False
```
```
In kernel/events/core.c (ffffffff8118a0c1)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (ffffffff8146f656)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (ffffffff815660c1)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81695f49)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/input/evdev.c (ffffffff816cd548)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In net/socket.c (ffffffff81763b28)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8176b77e)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
```
```
In net/core/skbuff.c (ffffffff8176ee60)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff81778d88)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
```
```
In net/core/dev.c (ffffffff817830d9)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/compat.c (ffffffff817ab22c)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
```
In net/ipv4/tcp_cubic.c (ffffffff81819a40)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (ffffffff8182ed4d)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff818621c9)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff810f5b00-ffffffff810f5b0d: ktime_get_real (STB_LOCAL)
ffffffff81101fe0-ffffffff81101fed: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fcac0)
Location: include/linux/timekeeping.h:193
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff81104800)
Location: include/linux/timekeeping.h:193
Inline: False
```
```
In kernel/events/core.c (ffffffff811994b1)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (ffffffff814919c6)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (ffffffff81592821)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c4029)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/input/evdev.c (ffffffff816fb4e8)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In net/socket.c (ffffffff81790b54)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8179884e)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
```
```
In net/core/skbuff.c (ffffffff8179c344)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff817a5ec8)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
```
```
In net/core/dev.c (ffffffff817b0979)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/compat.c (ffffffff817da84c)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
```
In net/ipv4/tcp_cubic.c (ffffffff8184b300)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (ffffffff818607cd)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81894029)
Location: include/linux/timekeeping.h:193
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff810fcac0-ffffffff810fcacd: ktime_get_real (STB_LOCAL)
ffffffff81104800-ffffffff8110480d: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff810fef20)
Location: include/linux/timekeeping.h:182
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff81106bc0)
Location: include/linux/timekeeping.h:182
Inline: False
```
```
In kernel/events/core.c (ffffffff811a1401)
Location: include/linux/timekeeping.h:182
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (ffffffff8149b5f6)
Location: include/linux/timekeeping.h:182
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (ffffffff815a6ab3)
Location: include/linux/timekeeping.h:182
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816d87e9)
Location: include/linux/timekeeping.h:182
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/input/evdev.c (ffffffff81710f60)
Location: include/linux/timekeeping.h:182
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In net/socket.c (ffffffff817ae1ea)
Location: include/linux/timekeeping.h:182
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff817b63e0)
Location: include/linux/timekeeping.h:182
Inline: True
Inline callers:
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
```
```
In net/core/skbuff.c (ffffffff817bcfe7)
Location: include/linux/timekeeping.h:182
Inline: True
```
```
In net/core/secure_seq.c (ffffffff817c3e70)
Location: include/linux/timekeeping.h:182
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff817d0ba2)
Location: include/linux/timekeeping.h:182
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/compat.c (ffffffff817f9d80)
Location: include/linux/timekeeping.h:182
Inline: True
Inline callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
```
In net/ipv4/tcp_cubic.c (ffffffff8186ed85)
Location: include/linux/timekeeping.h:182
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (ffffffff81884f48)
Location: include/linux/timekeeping.h:182
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff818ba751)
Location: include/linux/timekeeping.h:182
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff810fef20-ffffffff810fef2d: ktime_get_real (STB_LOCAL)
ffffffff81106bc0-ffffffff81106bcd: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81109d00)
Location: include/linux/timekeeping.h:62
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff81111c70)
Location: include/linux/timekeeping.h:62
Inline: False
```
```
In kernel/events/core.c (ffffffff811b4f81)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (ffffffff814da496)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (ffffffff8160d3b3)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81744f19)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/input/evdev.c (ffffffff817821e0)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In net/socket.c (ffffffff818262ba)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8182e9a0)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
```
```
In net/core/skbuff.c (ffffffff81835297)
Location: include/linux/timekeeping.h:62
Inline: True
```
```
In net/core/secure_seq.c (ffffffff8183d91c)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff8184adfe)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/compat.c (ffffffff81877690)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
```
In net/ipv4/tcp_cubic.c (ffffffff818ef715)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (ffffffff81905e8c)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff8193d731)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81109d00-ffffffff81109d0d: ktime_get_real (STB_LOCAL)
ffffffff81111c70-ffffffff81111c7d: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81115820)
Location: include/linux/timekeeping.h:62
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8111d660)
Location: include/linux/timekeeping.h:62
Inline: False
```
```
In kernel/events/core.c (ffffffff811d3de0)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (ffffffff81507585)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
```
```
In drivers/char/random.c (ffffffff8164645d)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8178564b)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/input/evdev.c (ffffffff817c2eff)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In net/socket.c (ffffffff8186fb9a)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81878e1e)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
```
```
In net/core/skbuff.c (ffffffff8187f509)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff8188813e)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff81892110)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/compat.c (ffffffff818c8d8c)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/compat.c:compat_sock_get_timestamp
```
```
In net/ipv4/tcp_cubic.c (ffffffff81946074)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (ffffffff8195cba8)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff8199665f)
Location: include/linux/timekeeping.h:62
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81115820-ffffffff8111582d: ktime_get_real (STB_LOCAL)
ffffffff8111d660-ffffffff8111d66d: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81120ef0)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff81128e10)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/events/core.c (ffffffff811e42e0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (ffffffff8151bb05)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (ffffffff816650ad)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817aebbb)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/input/evdev.c (ffffffff817ea45f)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In net/socket.c (ffffffff81890777)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff818997c4)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
```
```
In net/core/skbuff.c (ffffffff818a02d9)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff818a8d0e)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff818b80ff)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/compat.c (ffffffff818f3ea2)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In net/ipv4/tcp_cubic.c (ffffffff81976214)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (ffffffff81991be0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff819ccf6c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81120ef0-ffffffff81120efd: ktime_get_real (STB_LOCAL)
ffffffff81128e10-ffffffff81128e1d: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112b670)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff81133860)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/events/core.c (ffffffff811fb5d0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (ffffffff81549cb5)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (ffffffff828f9de6)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817eda19)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In drivers/input/evdev.c (ffffffff8182af5f)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/input/evdev.c:__evdev_queue_syn_dropped
```
```
In net/socket.c (ffffffff818da600)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff818e3dc8)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffff818eacee)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff818f43ae)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff81904370)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/ipv4/tcp_cubic.c (ffffffff819dfd98)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (ffffffff819fce37)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a3ba28)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff8112b670-ffffffff8112b67d: ktime_get_real (STB_LOCAL)
ffffffff81133860-ffffffff8113386d: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811377f0)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8113f7b0)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/events/core.c (ffffffff81208980)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (ffffffff8156ae55)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (ffffffff82902ce9)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181e8e9)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (ffffffff8190c750)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81915fa8)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffff8191ce5e)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff8192635e)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff81935485)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffffffff819746e5)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (ffffffff8197d7ca)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a16d88)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (ffffffff81a33ac7)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a726a8)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff811377f0-ffffffff811377fd: ktime_get_real (STB_LOCAL)
ffffffff8113f7b0-ffffffff8113f7bd: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81146220)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8114e300)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff8114f6c5)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
```
```
In kernel/events/core.c (ffffffff81231400)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/char/random.c (ffffffff82d19ab2)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ed7d9)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (ffffffff819df1e5)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff819e94f8)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffff819ef1bc)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff819fa33a)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff81a0a190)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffffffff81a498f5)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (ffffffff81a53ed2)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b28d60)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b6c387)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81146220-ffffffff8114622d: ktime_get_real (STB_LOCAL)
ffffffff8114e300-ffffffff8114e30d: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81142740)
Location: include/linux/timekeeping.h:76
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8114a590)
Location: include/linux/timekeeping.h:76
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff8114b945)
Location: include/linux/timekeeping.h:76
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
```
```
In kernel/events/core.c (ffffffff8123b070)
Location: include/linux/timekeeping.h:76
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163b8c6)
Location: include/linux/timekeeping.h:76
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/char/random.c (ffffffff830077b6)
Location: include/linux/timekeeping.h:76
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f6894)
Location: include/linux/timekeeping.h:76
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (ffffffff819deb85)
Location: include/linux/timekeeping.h:76
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff819e93a8)
Location: include/linux/timekeeping.h:76
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffff819eee5c)
Location: include/linux/timekeeping.h:76
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff819f9f2a)
Location: include/linux/timekeeping.h:76
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff81a0b735)
Location: include/linux/timekeeping.h:76
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffffffff81a4f0c5)
Location: include/linux/timekeeping.h:76
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (ffffffff81a5ba52)
Location: include/linux/timekeeping.h:76
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b36fd1)
Location: include/linux/timekeeping.h:76
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b7adf7)
Location: include/linux/timekeeping.h:76
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81142740-ffffffff8114274d: ktime_get_real (STB_LOCAL)
ffffffff8114a590-ffffffff8114a59d: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143910)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8114ba50)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff8114cdf5)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
```
```
In kernel/events/core.c (ffffffff8123f830)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161f7a6)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/char/random.c (ffffffff83212312)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818da429)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (ffffffff819c4b45)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff819cf4c8)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffff819d751c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff819e00ee)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff819f35e8)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffffffff81a34055)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (ffffffff81a3eb79)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b24bb2)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81b69790)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81143910-ffffffff8114391d: ktime_get_real (STB_LOCAL)
ffffffff8114ba50-ffffffff8114ba5d: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81166d00)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8116f760)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff81170e35)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
```
```
In kernel/events/core.c (ffffffff8127a050)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In fs/ext4/super.c (ffffffff81498973)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168ed33)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/char/random.c (ffffffff832fb526)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81975edc)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (ffffffff81a73fce)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81a7df78)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffff81a85d5c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff81a904fb)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff81aa4f3f)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffffffff81ae9b55)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (ffffffff81af485b)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81be9bf4)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81c311ba)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ioam6.c (ffffffff81c39298)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
**Symbols:**

```
ffffffff81166d00-ffffffff81166d0d: ktime_get_real (STB_LOCAL)
ffffffff8116f760-ffffffff8116f76d: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119a4d0)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff811a3c90)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff811a54c5)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
```
```
In kernel/events/core.c (ffffffff812cd550)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In fs/ext4/super.c (ffffffff81523723)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817aca81)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/char/random.c (ffffffff81934827)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad1a5c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (ffffffff81be6c5b)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81bee101)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffff81bf9fb9)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff81c063b4)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff81c1b83a)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffffffff81c6c3b5)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (ffffffff81c77f0f)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_do_dump
```
```
In net/ipv4/ip_input.c (ffffffff81cd581d)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/unix/af_unix.c (ffffffff81d82670)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d5cc)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81dce545)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ioam6.c (ffffffff81dd6f7b)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/packet/af_packet.c (ffffffff81df6547)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff8119a4d0-ffffffff8119a4e3: ktime_get_real (STB_LOCAL)
ffffffff811a3c90-ffffffff811a3ca3: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811d8c30)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff811e34f0)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff811e4eb5)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
```
```
In kernel/events/core.c (ffffffff81335480)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In fs/ext4/super.c (ffffffff815c0903)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c4ba0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
```
```
In drivers/char/random.c (ffffffff81a941c7)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5c4fb)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (ffffffff81d93bc6)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81d9acde)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffff81da8e87)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff81db5cf4)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff81dcc7ea)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffffffff81e23db5)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (ffffffff81e3098f)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_do_dump
```
```
In net/ipv4/ip_input.c (ffffffff81e95c7d)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/unix/af_unix.c (ffffffff81f4fbcb)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b6ac)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81f9f695)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ioam6.c (ffffffff81fa8936)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/packet/af_packet.c (ffffffff81fcaaca)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff811d8c30-ffffffff811d8c43: ktime_get_real (STB_LOCAL)
ffffffff811e34f0-ffffffff811e3503: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ed060)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff811f7b20)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff811f9515)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
```
```
In kernel/events/core.c (ffffffff813661d0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In fs/ext4/super.c (ffffffff815f809a)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81907c70)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
```
```
In drivers/char/random.c (ffffffff81adf9e7)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc3b7b)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (ffffffff81e01766)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81e0945e)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffff81e19fa1)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff81e262c4)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff81e3d34a)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffffffff81e992f5)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/ipv4/ip_input.c (ffffffff81ef44bd)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/unix/af_unix.c (ffffffff81faf46e)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb47c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/exthdrs.c (ffffffff82000204)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ioam6.c (ffffffff820092c6)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/packet/af_packet.c (ffffffff8202b7f4)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/devlink/health.c (ffffffff82046d5f)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff811ed060-ffffffff811ed073: ktime_get_real (STB_LOCAL)
ffffffff811f7b20-ffffffff811f7b33: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81203290)
Location: include/linux/timekeeping.h:78
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8120dcc0)
Location: include/linux/timekeeping.h:78
Inline: False
```
```
In kernel/time/posix-timers.c (ffffffff8120f705)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:posix_get_realtime_ktime
```
```
In kernel/events/core.c (ffffffff8138f2f0)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In fs/ext4/super.c (ffffffff81630c4a)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194f491)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
```
```
In drivers/char/random.c (ffffffff81b32e07)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d78a68)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (ffffffff81ebe113)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81ec5e4e)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffff81ed757a)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff81ee4254)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff81efbbea)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffffffff81f5b9b5)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/ipv4/ip_input.c (ffffffff81fb843d)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/unix/af_unix.c (ffffffff8207ca1a)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/ip6_input.c (ffffffff8208888c)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/exthdrs.c (ffffffff820cef94)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
```
In net/ipv6/ioam6.c (ffffffff820d8266)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
  - net/ipv6/ioam6.c:__ioam6_fill_trace_data
```
```
In net/packet/af_packet.c (ffffffff820fb2bd)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
```
```
In net/devlink/health.c (ffffffff82112461)
Location: include/linux/timekeeping.h:78
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff81203290-ffffffff812032a3: ktime_get_real (STB_LOCAL)
ffffffff8120dcc0-ffffffff8120dcd3: ktime_get_real (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a0b10)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffff8000101a8d20)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/events/core.c (ffff800010291d80)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (ffff8000106be740)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (ffff800011495d44)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (ffff8000109ecd10)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a56270)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (ffff800010ba1628)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffff800010baef60)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffff800010bb754c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffff800010bc25b4)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffff800010bd371c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffff800010c1b864)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (ffff800010c25380)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In net/ipv4/tcp_cubic.c (ffff800010cd2efc)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (ffff800010cf3a44)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffff800010d3afb4)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffff8000101a0b10-ffff8000101a0b28: ktime_get_real (STB_LOCAL)
ffff8000101a8d20-ffff8000101a8d38: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/common/bL_switcher.c (c03267e0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_trace_trigger_cpu
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - arch/arm/common/bL_switcher.c:bL_switch_to
```
```
In kernel/time/hrtimer.c (c03ea900)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (c03f4cac)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/events/core.c (c04c2f54)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (c085e54c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (c15960a8)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (c0aceca0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_start_cyclecounter
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad0f18)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_register
```
```
In drivers/usb/host/ehci-hcd.c (c0b2bcec)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (c0cc467c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (c0ccca00)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (c0cd421c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (c0cdd938)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (c0cee47c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (c0d326b0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (c0d3c488)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In net/ipv4/tcp_cubic.c (c0ddc90c)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In net/unix/af_unix.c (c0dfacfc)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (c0e3d904)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
c03ea900-c03ea918: ktime_get_real (STB_LOCAL)
c03f4cac-c03f4cc4: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000201f50)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (c00000000020cdb0)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/events/core.c (c0000000003403f4)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (c00000000083b6b0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (c0000000013a8350)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b20880)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (c000000000c75ba0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (c000000000c84c90)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (c000000000c8f0dc)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (c000000000c9c41c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (c000000000cb22cc)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (c000000000d0aac4)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (c000000000d1ab40)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In net/ipv4/tcp_cubic.c (c000000000df112c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (c000000000e19c4c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (c000000000e6e840)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
c000000000201f50-c000000000201f80: ktime_get_real (STB_LOCAL)
c00000000020cdb0-c00000000020cde0: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012e43c)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffe000135092)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/events/core.c (ffffffe0001c4642)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a565a)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (ffffffe00002f950)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe0006757ac)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (ffffffe00073972c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffe000740a8e)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffe00074704a)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffe00074f550)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffe00075d952)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffffffe000794c04)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (ffffffe00079d7e4)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In net/ipv4/tcp_cubic.c (ffffffe000823cb2)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (ffffffe0008403bc)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffe000877d32)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffe00012e43c-ffffffe00012e456: ktime_get_real (STB_LOCAL)
ffffffe000135092-ffffffe0001350ac: ktime_get_real (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112ffa0)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff81137f60)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/events/core.c (ffffffff81200fa0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (ffffffff81560615)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (ffffffff828ea4d0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/nvme/host/core.c (ffffffff81747a08)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_identify
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d6cc9)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (ffffffff818ac750)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff818b5fa8)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffff818bce5e)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff818c635e)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff818d5459)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffffffff819146b5)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (ffffffff8191d63a)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In net/ipv4/tcp_cubic.c (ffffffff819b6418)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (ffffffff819d3157)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a11d38)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff8112ffa0-ffffffff8112ffad: ktime_get_real (STB_LOCAL)
ffffffff81137f60-ffffffff81137f6d: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122a10)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff8112a9b0)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/events/core.c (ffffffff811f3cf0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (ffffffff81551465)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (ffffffff828e195d)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/nvme/host/core.c (ffffffff81729658)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_identify
```
```
In net/socket.c (ffffffff818666a0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff8186fef8)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffff81876d9e)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff8188029e)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff8188f2c9)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffffffff818ce475)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (ffffffff818d73ea)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In net/ipv4/tcp_cubic.c (ffffffff81973208)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (ffffffff8198ff17)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff819ceaf8)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff81122a10-ffffffff81122a1d: ktime_get_real (STB_LOCAL)
ffffffff8112a9b0-ffffffff8112a9bd: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112dcc0)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff81135c80)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/events/core.c (ffffffff811fed70)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (ffffffff8155f185)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (ffffffff828fe00c)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81813769)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (ffffffff818fd750)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81906fa8)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffff8190de5e)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff8191735e)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff81926485)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffffffff819656e5)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (ffffffff8196e7ca)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a00b1)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a1138)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_start
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ae0cd)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_conntrack
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a20e98)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/unix/af_unix.c (ffffffff81a3dbd7)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a7c7b8)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff8112dcc0-ffffffff8112dccd: ktime_get_real (STB_LOCAL)
ffffffff81135c80-ffffffff81135c8d: ktime_get_real (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
ktime_t ktime_get_real();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113a610)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/time/alarmtimer.c (ffffffff811426d0)
Location: include/linux/timekeeping.h:77
Inline: False
```
```
In kernel/events/core.c (ffffffff8120de00)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:ktime_get_real_ns
```
```
In drivers/gpio/gpiolib.c (ffffffff81579005)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/char/random.c (ffffffff82903d4b)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/char/random.c:init_std_data
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182e609)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_run
```
```
In net/socket.c (ffffffff8191e7c0)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_timestamp
```
```
In net/core/sock.c (ffffffff81927fd8)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/sock.c:sock_gettstamp
```
```
In net/core/skbuff.c (ffffffff8192ef8e)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
```
```
In net/core/secure_seq.c (ffffffff8193856e)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/dev.c (ffffffff81947a2f)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_rx_internal
  - net/core/dev.c:dev_queue_xmit_nit
```
```
In net/core/drop_monitor.c (ffffffff81987925)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
```
```
In net/core/devlink.c (ffffffff81990c7a)
Location: include/linux/timekeeping.h:77
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a49690)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/ipv6/exthdrs.c (ffffffff81a89008)
Location: include/linux/timekeeping.h:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_dest_hao
```
**Symbols:**

```
ffffffff8113a610-ffffffff8113a61d: ktime_get_real (STB_LOCAL)
ffffffff811426d0-ffffffff811426dd: ktime_get_real (STB_LOCAL)
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
