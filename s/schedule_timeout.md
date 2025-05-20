# Function: <code>schedule_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81823360)
Location: kernel/time/timer.c:1493
Inline: False
Direct callers:
  - kernel/kmod.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait.c:bit_wait_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/locking/semaphore.c:__down
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down_killable
  - kernel/rcu/tree.c:synchronize_sched_expedited
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/time/timer.c:msleep
  - kernel/module.c:load_module
  - kernel/audit.c:audit_log_start
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:kswapd
  - mm/huge_memory.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:SYSC_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/xen/xenbus/xenbus_xs.c:read_reply
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_wait_for_backend
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_recv_datagram
  - net/core/stream.c:sk_stream_wait_connect
  - net/core/stream.c:sk_stream_wait_memory
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/unix/af_unix.c:unix_wait_for_peer
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81823360-ffffffff818235cd: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8189dde0)
Location: kernel/time/timer.c:1709
Inline: False
Direct callers:
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/kmod.c:usermodehelper_read_lock_wait
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:bit_wait_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - kernel/audit.c:audit_log_start
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/khugepaged.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:SYSC_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/xen/xenbus/xenbus_xs.c:read_reply
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_wait_for_backend
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sk_wait_data
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/core/stream.c:sk_stream_wait_memory
  - net/core/stream.c:sk_stream_wait_connect
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/af_inet.c:__inet_stream_connect
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff8189dde0-ffffffff8189e21e: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff818d2c90)
Location: kernel/time/timer.c:1714
Inline: False
Direct callers:
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/kmod.c:usermodehelper_read_lock_wait
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:bit_wait_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/khugepaged.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:SYSC_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/xen/xenbus/xenbus_xs.c:read_reply
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_wait_for_backend
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/base/firmware_class.c:__fw_state_wait_common
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff818d2c90-ffffffff818d307c: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81909ea0)
Location: kernel/time/timer.c:1705
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write
  - kernel/kmod.c:__usermodehelper_disable
  - kernel/kmod.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/khugepaged.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:SYSC_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81909ea0-ffffffff8190a1ee: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff819941e0)
Location: kernel/time/timer.c:1754
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/khugepaged.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff819941e0-ffffffff81994522: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff819f0760)
Location: kernel/time/timer.c:1765
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/khugepaged.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff819f0760-ffffffff819f0abd: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a2bae0)
Location: kernel/time/timer.c:1764
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81a2bae0-ffffffff81a2be3d: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a9bd10)
Location: kernel/time/timer.c:1768
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81a9bd10-ffffffff81a9bffb: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81ad3660)
Location: kernel/time/timer.c:1856
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81ad3660-ffffffff81ad394b: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81bcb770)
Location: kernel/time/timer.c:1877
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:resolve_symbol_wait
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wqe_worker
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_wait_for_wmem
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81bcb770-ffffffff81bcb8c2: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81c44610)
Location: kernel/time/timer.c:1839
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:resolve_symbol_wait
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/io_uring.c:io_cqring_wait
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wqe_worker
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_wait_for_wmem
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81c44610-ffffffff81c44748: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81c37880)
Location: kernel/time/timer.c:1856
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/locking/semaphore.c:__down_common
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:simplify_symbols
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/io_uring.c:io_cqring_wait
  - fs/io-wq.c:io_wqe_worker
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81c37880-ffffffff81c379b5: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81d56140)
Location: kernel/time/timer.c:1842
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/locking/semaphore.c:__down_common
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:simplify_symbols
  - kernel/audit.c:audit_receive
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/io-wq.c:io_wqe_worker
  - fs/locks.c:__break_lease
  - ipc/sem.c:__do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_wait_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/xen/balloon.c:balloon_thread
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81d56140-ffffffff81d56271: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81f28140)
Location: kernel/time/timer.c:1896
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/build_utility.c:wait_woken
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/locking/semaphore.c:__down_common
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/module/main.c:simplify_symbols
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/locks.c:__break_lease
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - io_uring/io-wq.c:io_wqe_worker
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/xen/balloon.c:balloon_thread
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81f28140-ffffffff81f28299: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff820d3d30)
Location: kernel/time/timer.c:2128
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/build_utility.c:wait_woken
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_timeout
  - kernel/sched/build_utility.c:wait_for_completion
  - kernel/locking/semaphore.c:___down_common
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/module/main.c:simplify_symbols
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/locks.c:__break_lease
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - io_uring/io-wq.c:io_wqe_worker
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/xen/balloon.c:balloon_thread
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff820d3d30-ffffffff820d3e94: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff82157fb0)
Location: kernel/time/timer.c:2128
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/build_utility.c:wait_woken
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_timeout
  - kernel/sched/build_utility.c:wait_for_completion
  - kernel/locking/semaphore.c:___down_common
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/module/main.c:simplify_symbols
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/locks.c:__break_lease
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - io_uring/io-wq.c:io_wq_worker
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/xen/balloon.c:balloon_thread
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff82157fb0-ffffffff82158114: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8223ae20)
Location: kernel/time/timer.c:2144
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/build_utility.c:wait_woken
  - kernel/sched/build_utility.c:bit_wait_timeout
  - kernel/sched/build_utility.c:wait_for_completion_killable_timeout
  - kernel/sched/build_utility.c:wait_for_completion_state
  - kernel/sched/build_utility.c:wait_for_completion_killable
  - kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout
  - kernel/sched/build_utility.c:wait_for_completion_interruptible
  - kernel/sched/build_utility.c:wait_for_completion_timeout
  - kernel/sched/build_utility.c:wait_for_completion
  - kernel/locking/semaphore.c:___down_common
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/module/main.c:simplify_symbols
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:reclaim_throttle
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/locks.c:__break_lease
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - io_uring/io-wq.c:io_wq_worker
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/xen/balloon.c:balloon_thread
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:down_write_failed
  - drivers/tty/tty_ldsem.c:down_read_failed
  - drivers/char/random.c:wait_for_random_bytes
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence
  - drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_wait_one_vblank
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_data_wait
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff8223ae20-ffffffff8223af84: schedule_timeout (STB_GLOBAL)
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
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff800010da6320)
Location: kernel/time/timer.c:1856
Inline: False
Direct callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffff800010da6320-ffff800010da64ac: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0e9df14)
Location: kernel/time/timer.c:1856
Inline: False
Direct callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:try_to_free_pages
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_trx_complete
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/host/sdhci.c:sdhci_send_tuning
  - drivers/mmc/host/cqhci.c:cqhci_halt
  - sound/core/pcm_native.c:snd_pcm_drain
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
c0e9df14-c0e9e240: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c000000000ee88f0)
Location: kernel/time/timer.c:1856
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal.c:kopald
  - arch/powerpc/platforms/powernv/vas-window.c:vas_win_close
  - arch/powerpc/platforms/powernv/vas-window.c:vas_win_close
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/tty/hvc/hvsi.c:hvsi_close
  - drivers/tty/hvc/hvsi.c:wait_for_state
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
c000000000ee88f0-c000000000ee8ccc: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe0008c8668)
Location: kernel/time/timer.c:1856
Inline: False
Direct callers:
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffe0008c8668-ffffffe0008c8920: schedule_timeout (STB_GLOBAL)
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
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a724d0)
Location: kernel/time/timer.c:1856
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81a724d0-ffffffff81a727bb: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81a2e8a0)
Location: kernel/time/timer.c:1856
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81a2e8a0-ffffffff81a2eb8b: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81ade8e0)
Location: kernel/time/timer.c:1856
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81ade8e0-ffffffff81adebcb: schedule_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81aead60)
Location: kernel/time/timer.c:1856
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write
  - kernel/umh.c:__usermodehelper_disable
  - kernel/umh.c:usermodehelper_read_lock_wait
  - kernel/kmod.c:__request_module
  - kernel/sched/core.c:io_schedule_timeout
  - kernel/sched/wait.c:wait_woken
  - kernel/sched/wait_bit.c:bit_wait_timeout
  - kernel/sched/completion.c:wait_for_completion_killable_timeout
  - kernel/sched/completion.c:wait_for_completion_killable
  - kernel/sched/completion.c:wait_for_completion_interruptible_timeout
  - kernel/sched/completion.c:wait_for_completion_interruptible
  - kernel/sched/completion.c:wait_for_completion_timeout
  - kernel/sched/completion.c:wait_for_completion
  - kernel/locking/semaphore.c:__down_timeout
  - kernel/locking/semaphore.c:__down_killable
  - kernel/locking/semaphore.c:__down_interruptible
  - kernel/locking/semaphore.c:__down
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - kernel/time/timer.c:schedule_timeout_idle
  - kernel/time/timer.c:schedule_timeout_killable
  - kernel/module.c:load_module
  - mm/oom_kill.c:oom_killer_disable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/locks.c:__break_lease
  - ipc/sem.c:do_semtimedop
  - security/tomoyo/common.c:tomoyo_supervisor
  - block/blk-mq.c:blk_mq_freeze_queue_wait_timeout
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
  - drivers/acpi/ec.c:ec_guard
  - drivers/tty/tty_ioctl.c:tty_wait_until_sent
  - drivers/tty/tty_ldsem.c:ldsem_down_write
  - drivers/tty/tty_ldsem.c:ldsem_down_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/dma-buf/dma-fence.c:dma_fence_default_wait
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/media/cec/cec-adap.c:cec_thread_func
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/pps/pps.c:pps_cdev_pps_fetch
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_ioctl
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - net/core/sock.c:sock_alloc_send_pskb
  - net/core/datagram.c:__skb_wait_for_more_packets
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_wait_for_peer
```
**Symbols:**

```
ffffffff81aead60-ffffffff81aeb05f: schedule_timeout (STB_GLOBAL)
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
