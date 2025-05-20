# Function: <code>poll_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044d26)
Location: include/linux/poll.h:42
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810d8c4b)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/relay.c (ffffffff8113c3a1)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff8114a668)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffffffff811788b0)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff811d2e96)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff81214926)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff8124e916)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81251ad6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81252ec6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff812557c3)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffffffff812575f9)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff81257e76)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff81258f26)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff81259e86)
Location: include/linux/poll.h:42
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff81284c45)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff81287d46)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff8128b64f)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff8130bc25)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff8130e1f6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff81315338)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff8132bcb6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff813679f5)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff81368878)
Location: include/linux/poll.h:42
Inline: True
```
```
In block/bsg.c (ffffffff813d6866)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - block/bsg.c:bsg_poll
  - block/bsg.c:bsg_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff814cfef6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff814d5536)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff814e49b6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff814f10d2)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff81511816)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff81517746)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff815195df)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8153f471)
Location: include/linux/poll.h:42
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815a33a7)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/scsi/sg.c (ffffffff815c2394)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/net/tun.c (ffffffff815eda5c)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff815f4b16)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff81619736)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffff8161df86)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffff81666c06)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff8166b676)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff8166cc96)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff81671766)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/rtc-dev.c (ffffffff81675406)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_poll
```
```
In drivers/md/md.c (ffffffff8168bea6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In net/core/datagram.c (ffffffff8170c8f7)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81768c78)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff817be1af)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff81810c86)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044d76)
Location: include/linux/poll.h:42
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810dddab)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/relay.c (ffffffff811448f1)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff811530c4)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffffffff81188e80)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff811f0cf6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff8123b6b6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff81277096)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8127a2a6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8127b556)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff8127e003)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffffffff8127fef9)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff81280776)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff81281906)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff81282896)
Location: include/linux/poll.h:42
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff812b1d16)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff812b5096)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff812b8baf)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff8133fea8)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff81342326)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff81349b88)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff81360946)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff8139dae5)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff8139e74a)
Location: include/linux/poll.h:42
Inline: True
```
```
In block/bsg.c (ffffffff8141c576)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - block/bsg.c:bsg_poll
  - block/bsg.c:bsg_poll
```
```
In drivers/gpio/gpiolib.c (ffffffff8146d5d6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81520b16)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff81526306)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff81535ca6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81541842)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff81563d76)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff8156a466)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff8156c2ef)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815fa46b)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff815fd066)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff8161aacd)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8163fae7)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff8164cb92)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81654720)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff81679936)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffff8167e7c6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffff816c6eb6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff816cb936)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff816ccfd6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff816d1c66)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/rtc-dev.c (ffffffff816d5ca6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_poll
```
```
In drivers/md/md.c (ffffffff816ed566)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In net/core/datagram.c (ffffffff81775347)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff817d55d8)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff8182b12f)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff81883b06)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810469f6)
Location: include/linux/poll.h:42
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810e43bb)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/relay.c (ffffffff8114e78e)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff8115d0b5)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffffffff81198250)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff81201666)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff8124e456)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff8128ad86)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8128de56)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8128f106)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff81291b93)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffffffff81293a69)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff812942e6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff81295436)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff812963b6)
Location: include/linux/poll.h:42
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff812c75a6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff812ca926)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff812ce31c)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff81355c38)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff81358156)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff8135f498)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff81377166)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff813b46c5)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff813b531a)
Location: include/linux/poll.h:42
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff813c1cb2)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In block/bsg.c (ffffffff81437ab6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - block/bsg.c:bsg_poll
  - block/bsg.c:bsg_poll
```
```
In drivers/gpio/gpiolib.c (ffffffff8148f4a6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8154cf96)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff81552815)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff815623c6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff8156de82)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff815904d6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff81596ba6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff81598a5f)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8162873b)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff8162b536)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff8164b75d)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81671387)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff8167e8c3)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81682400)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff816a7616)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffff816ac546)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffff816f4eb6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff816f98e6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff816faf76)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff817019d6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/rtc-dev.c (ffffffff81705986)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_poll
```
```
In drivers/md/md.c (ffffffff8171ec66)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In net/core/datagram.c (ffffffff817a2637)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81805552)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff8185cb5f)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff818b83a6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104c596)
Location: include/linux/poll.h:42
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810e1256)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/relay.c (ffffffff81150e42)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff811600c5)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffffffff8119fed1)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff8120c616)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff8125a3e6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff81297b86)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8129ad96)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129c0b6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff8129e7d3)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffffffff812a0d3f)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff812a15c6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff812a26f6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff812a3236)
Location: include/linux/poll.h:42
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff812d4902)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff812d7db6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff812db93c)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff8136a839)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff8136cdd6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff81374022)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff8138acf6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff813cb054)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff813cbf8a)
Location: include/linux/poll.h:42
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff813d82ff)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In block/bsg.c (ffffffff81445246)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - block/bsg.c:bsg_poll
  - block/bsg.c:bsg_poll
```
```
In drivers/gpio/gpiolib.c (ffffffff81498ef6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81561316)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff81566fe5)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff81575d36)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81582432)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff815a4516)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff815aabc6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff815aca38)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8163e387)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff81641076)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff8165ffaf)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff816859e7)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff81693ab8)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8169782e)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff816bc956)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffff816c17a6)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffff8170a996)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff8170f446)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff81710966)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff81717206)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/rtc-dev.c (ffffffff8171b636)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_poll
```
```
In drivers/md/md.c (ffffffff81736ac0)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff81754066)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff817c0147)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81825032)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff818812df)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff818dec96)
Location: include/linux/poll.h:42
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104fe36)
Location: include/linux/poll.h:43
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810eb046)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/relay.c (ffffffff8115d632)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff8116d185)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffffffff811b37f1)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff81226246)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff8127c6e6)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff812bae66)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812be1a6)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812bf546)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff812c1d7b)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffffffff812c407f)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff812c48e6)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff812c59f6)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff812c65c6)
Location: include/linux/poll.h:43
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff812f9132)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff812fc4a6)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff8130025a)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff8138f3d9)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff813914c6)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff81398d92)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff813b00b6)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff813f14e4)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff813f242a)
Location: include/linux/poll.h:43
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff813fe74f)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In block/bsg.c (ffffffff81471d16)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - block/bsg.c:bsg_poll
  - block/bsg.c:bsg_poll
```
```
In drivers/gpio/gpiolib.c (ffffffff814d71e6)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff8159b966)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815c5606)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff815cb1a5)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff815da666)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff815e6f52)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff8160ae46)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff81611546)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff81613408)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816a7187)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff816a9a16)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff816c95bf)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff816ef247)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff816fd8e8)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817026fe)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff81728326)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffff8172d576)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffff8177bb56)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff817806b6)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff81781be6)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff817883d6)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/rtc-dev.c (ffffffff8178c8b6)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_poll
```
```
In drivers/md/md.c (ffffffff817a8860)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff817c6216)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff81839b57)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff818a39a2)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff8190246f)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff81964a26)
Location: include/linux/poll.h:43
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff81052aa5)
Location: include/linux/poll.h:44
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810f2826)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/relay.c (ffffffff8116c5b3)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff8117c18e)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffffffff811d2ce0)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff81248861)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff812a3686)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff812e3a0a)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812e7043)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e8f23)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff812eaf7b)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffffffff812ecf8c)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff812ed78b)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff812eec31)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff812ef706)
Location: include/linux/poll.h:44
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff81325d00)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff8132a0b5)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff8132df38)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff813be499)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff813c0824)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff813c8ee5)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff813e1040)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff8142241f)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff81422fd4)
Location: include/linux/poll.h:44
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff8142f652)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In block/bsg.c (ffffffff814a5ac5)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - block/bsg.c:bsg_poll
  - block/bsg.c:bsg_poll
```
```
In drivers/gpio/gpiolib.c (ffffffff815063b1)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff815d3365)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815fdd01)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff816039b5)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff81614625)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff816201e0)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff81644785)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff8164b133)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff8164d11b)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816e3404)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff816e5f57)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff81705f92)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8172bcc7)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff8173c97f)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81741423)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff81767186)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffff8176c3a5)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffff817bcc05)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff817c17e8)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff817c2d57)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff817c9411)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/rtc-dev.c (ffffffff817ceec1)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_poll
```
```
In drivers/pps/pps.c (ffffffff817dda35)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff817dfc25)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff817f028b)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff8180efc1)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff818842a2)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff818f87a7)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81959dc9)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff819be2d3)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81050105)
Location: include/linux/poll.h:44
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810fde66)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff81178143)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff81179fd2)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff8118998e)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffffffff811e3070)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff8125ce41)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff812b87d6)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff812f868a)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812fc183)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fd2a3)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff812ffa0b)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffffffff8130201c)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff8130211b)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff813035c1)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff813040b6)
Location: include/linux/poll.h:44
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffff8133ceb0)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff813413a5)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff81345338)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff813d7ada)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff813d9c04)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff813e2ea5)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff813fb6b0)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff8143ea84)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff8143f634)
Location: include/linux/poll.h:44
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff8144c242)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib.c (ffffffff8151a861)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff815ecb15)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81618dd1)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff8161ea55)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff81631355)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff8163d4a0)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff81662a85)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff816692a3)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff8166b34b)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81675f81)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81706784)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff817092e7)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff817284d2)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8174e467)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff81760e8f)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81765533)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff8178b706)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffff817909f5)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffff817e4065)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff817e8cd8)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff817ea2f7)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff817f0ac1)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff817f6031)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/media/cec/cec-api.c (ffffffff81807565)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_poll
```
```
In drivers/pps/pps.c (ffffffff81808e55)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8180b1f5)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff8181c17b)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff8183afa1)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff818a470f)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81926224)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff8198ef16)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff819f5473)
Location: include/linux/poll.h:44
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053205)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/fork.c (ffffffff810968f2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/psi.c (ffffffff810f75b2)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/printk/printk.c (ffffffff8110659a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff81184ec4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff81186e12)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff81196f71)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffffffff811fa240)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff81277fc1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff812d5342)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff81318cba)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8131c734)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131e3f4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff81320bac)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffffffff8132358c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff8132368c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff81324b41)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff81325642)
Location: include/linux/poll.h:48
Inline: True
```
```
In fs/io_uring.c (ffffffff8132d1b1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
```
```
In fs/proc/proc_sysctl.c (ffffffff813650e9)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff813697b5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff8136e0de)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff81402446)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff81405793)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff8140e9a4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff81427c00)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff8146c6d7)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff8146d264)
Location: include/linux/poll.h:48
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff81479fc4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib.c (ffffffff81548a01)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff8161eaf5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8164cae1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff81652055)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff81665315)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81671900)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff816985e5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff8169ec43)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff816a0efb)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816abd84)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817418e2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff81744aa9)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff81763be2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff8178a1e8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff8179eb24)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a2fc3)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff817c9d36)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffff817cf2d5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffff81824a95)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff818297f8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff8182adf7)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff81831751)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff81836d41)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/media/cec/cec-api.c (ffffffff81848e6b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_poll
```
```
In drivers/pps/pps.c (ffffffff8184ab05)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8184ced5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff8185e3bb)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff8187db51)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff818efe8b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff819873a0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff819fa692)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff81a64965)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053af5)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/fork.c (ffffffff8109cfc2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/psi.c (ffffffff81103352)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/printk/printk.c (ffffffff8111292a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff81190d94)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff81192d32)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff811a2971)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffffffff81207310)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff81287ab1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff812e6eb2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff8132bafa)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132f524)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81331234)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff8133394c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffffffff813362ec)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff813363ec)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff813378a1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff813383d2)
Location: include/linux/poll.h:48
Inline: True
```
```
In fs/io_uring.c (ffffffff81340011)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
```
```
In fs/proc/proc_sysctl.c (ffffffff8137d379)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff81381a05)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff8138629e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff8141c336)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff8141f742)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff814278f4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff81441930)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff814864b7)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff81487064)
Location: include/linux/poll.h:48
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff81493cc4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib.c (ffffffff81569a51)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff816405a5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8166ef71)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff816745f5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff81687965)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81694600)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff816bb1f5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff816c19d3)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff816c3c9b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816ceb04)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81765a62)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff81768be9)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff81787bd2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff817adde8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff817c25b4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c6a23)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff817fa856)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffff81800145)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffff81855f15)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff8185b188)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff8185c787)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff81863081)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff818686b1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/media/cec/cec-api.c (ffffffff8187a66b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_poll
```
```
In drivers/pps/pps.c (ffffffff8187c315)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8187e915)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff8188feeb)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff818af931)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff81921eab)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff819bdb40)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81a31312)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff81a9b455)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81058ae5)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/fork.c (ffffffff810a3c52)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/psi.c (ffffffff8110d478)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/printk/printk.c (ffffffff8111e1d7)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff811a58c4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff811a7b68)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff811b950e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/bpf/ringbuf.c (ffffffff8121def7)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:ringbuf_map_poll
```
```
In kernel/events/core.c (ffffffff812307e0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff812ba731)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff8131edd7)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff8136576a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81369514)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136b954)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff8136dbcc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
  - fs/eventpoll.c:ep_item_poll
```
```
In fs/signalfd.c (ffffffff8136f7dc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff813700bc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff813714a1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff81371fc2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/io_uring.c (ffffffff81382905)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
```
```
In fs/proc/proc_sysctl.c (ffffffff813c778e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff813cc025)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff813d0e9e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff8146aed6)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff8146e1e2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff81477814)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff814926c0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff814dc6a7)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff814dd06a)
Location: include/linux/poll.h:48
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff814eb0c4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib.c (ffffffff8160f217)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineinfo_watch_poll
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff816ecff5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171f361)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff817251e5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff81739bd5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81746300)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff81770ba5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff81776708)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff817784c0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81783a04)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81825d22)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff8182aac9)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff8184c532)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81874168)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff8188d08f)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81890b21)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff818caac6)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffff818d1365)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffff81929825)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff8192de78)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff8192f547)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff819367d1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff8193c2a1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/pps/pps.c (ffffffff8194a6d5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8194ce15)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff81961a81)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff81981811)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff819f50eb)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81aa95a1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81b252d2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff81b96cb5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
```
In net/mptcp/protocol.c (ffffffff81baaca2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810578f5)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/fork.c (ffffffff8109f3a2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/psi.c (ffffffff8110a4b4)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/printk/printk.c (ffffffff81118c4f)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff811a29d5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff811a5278)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff811b6f4e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/bpf/ringbuf.c (ffffffff81220c97)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:ringbuf_map_poll
```
```
In kernel/events/core.c (ffffffff8123a440)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff812c6141)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff8132a307)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff8137263a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813767f4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813791d4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff8137abf7)
Location: include/linux/poll.h:48
Inline: True
```
```
In fs/signalfd.c (ffffffff8137d53c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff8137de2c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff8137f231)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff8137fe06)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/io_uring.c (ffffffff8138b325)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
```
```
In fs/proc/proc_sysctl.c (ffffffff813d988e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff813ddc65)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff813e2aae)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff814857e6)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff81488972)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff81492c96)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff814affb0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff814f9ae7)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff814fa48a)
Location: include/linux/poll.h:48
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff815084c4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163b647)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_poll
  - drivers/gpio/gpiolib-cdev.c:linereq_poll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff8170a5e5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173c2c1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff817421a5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff817566de)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81761fa0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff8178bc15)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff81791438)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff81792fa0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff8179af94)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81836702)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff8183b789)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff8185c972)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81882d08)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff8189b309)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8189ed01)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff818d5bd6)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/input/input.c (ffffffff81930e2d)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff81935208)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff81936857)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff8193cbc1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff81942291)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/pps/pps.c (ffffffff81950225)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8195284d)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff81968361)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff81985e31)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff819f4b1b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81ab38c1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81b33e42)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff81ba6925)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
```
In net/xdp/xsk.c (ffffffff81bb77db)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
```
```
In net/mptcp/protocol.c (ffffffff81bbc133)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81058255)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/fork.c (ffffffff810a0272)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/psi.c (ffffffff8110d062)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/printk/printk.c (ffffffff8111921f)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff811a34a5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff811a5e48)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff811b79de)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/bpf/ringbuf.c (ffffffff81224727)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:ringbuf_map_poll
```
```
In kernel/events/core.c (ffffffff8123ec70)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff812ccac1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff813302ba)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff81378faa)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137d2f3)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81380023)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff81381767)
Location: include/linux/poll.h:48
Inline: True
```
```
In fs/signalfd.c (ffffffff813841bc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff81384aac)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff81385eb1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff81386ab6)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/io_uring.c (ffffffff8138ec51)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
```
```
In fs/proc/proc_sysctl.c (ffffffff813e057e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff813e4b45)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff813e96be)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff8148b256)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff8148e442)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff81497c06)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff814b5e00)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff81500827)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff815011aa)
Location: include/linux/poll.h:48
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff8150f034)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161f4c7)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_poll
  - drivers/gpio/gpiolib-cdev.c:linereq_poll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff816ebcb5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171fe21)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff81725b95)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff8173a3fe)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81745c60)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff8176ed55)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff81774798)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff81775cc0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff8177dad4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818198d2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff8181e9a9)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff8183f862)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81865558)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff8187df99)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81881721)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81887ba1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_poll
```
```
In drivers/usb/core/devio.c (ffffffff818b9126)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/input/input.c (ffffffff81913f9d)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff81918a98)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff8191a0d7)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff819203d1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff81925ac1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/pps/pps.c (ffffffff819340b5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff819366bd)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff8194c416)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff81969541)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff819dacab)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81a9e911)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81b217f2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff81b95ab5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
```
In net/xdp/xsk.c (ffffffff81ba695b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
```
```
In net/mptcp/protocol.c (ffffffff81bab203)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81061125)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/fork.c (ffffffff810b1682)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/psi.c (ffffffff8112bf4f)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/printk/printk.c (ffffffff811395f9)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff811ccb85)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff811cf5d8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff811e1c0e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/bpf/ringbuf.c (ffffffff8125c667)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:ringbuf_map_poll
```
```
In kernel/events/core.c (ffffffff812796a0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff81311e31)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff8137da7a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff813c5b0a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813ca373)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813ccf93)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff813ce9a7)
Location: include/linux/poll.h:48
Inline: True
```
```
In fs/signalfd.c (ffffffff813d145c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff813d1d2c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff813d3171)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff813d3d46)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/io_uring.c (ffffffff813dc4f1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
```
```
In fs/proc/proc_sysctl.c (ffffffff81431f7a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff81436715)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff8143b42e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff814e2a86)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff814e5eb2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff814ef816)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff8150e690)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff8155bae7)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff8155c65a)
Location: include/linux/poll.h:48
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff8156cbf4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168ea57)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_poll
  - drivers/gpio/gpiolib-cdev.c:linereq_poll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff81765dd5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179ec41)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff817a4b75)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff817baebe)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff817c6bf0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff817f4515)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff817f9bc5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff817fba30)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81803cc4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818a4038)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff818a9039)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff818cc212)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff818f48e5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff8190f77e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff819130c1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/wwan/wwan_core.c (ffffffff819195bd)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_poll
```
```
In drivers/usb/core/devio.c (ffffffff8194ec06)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/input/input.c (ffffffff819b60bd)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff819bae58)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff819bc8e7)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff819c31b1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff819c8a31)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/pps/pps.c (ffffffff819d74e5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff819d9dcd)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff819f17b6)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff81a11971)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff81a8b32b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81b5a621)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81be6b42)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff81c62305)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
```
In net/xdp/xsk.c (ffffffff81c7495f)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
```
```
In net/mptcp/protocol.c (ffffffff81c77b03)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8106dad5)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_poll
```
```
In kernel/fork.c (ffffffff810c79a1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/build_utility.c (ffffffff8114cc7b)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_poll
```
```
In kernel/printk/printk.c (ffffffff8115c0ad)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff812008d5)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff8120381a)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff8121892b)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/bpf/ringbuf.c (ffffffff812a6387)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:ringbuf_map_poll
```
```
In kernel/events/core.c (ffffffff812cc835)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff8137d011)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff813fe0fb)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff8144c9ea)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81451583)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81454743)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff81457bff)
Location: include/linux/poll.h:46
Inline: True
```
```
In fs/signalfd.c (ffffffff8145a53e)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff8145af7b)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff8145c6a1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff8145d306)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/proc/proc_sysctl.c (ffffffff814ac78e)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff814b0e45)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff814b66be)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff81570d73)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff81573c54)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff8157cc71)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff8159f6f2)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff815f6a24)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff815f7734)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_poll_query
```
```
In security/apparmor/apparmorfs.c (ffffffff816092a6)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In io_uring/io_uring.c (ffffffff816c52c1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_poll
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ad469)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_poll
  - drivers/gpio/gpiolib-cdev.c:lineevent_poll
  - drivers/gpio/gpiolib-cdev.c:linereq_poll
```
```
In drivers/pci/vgaarb.c (ffffffff817f3cb4)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_fpoll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff8189a1f5)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d8621)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff818de905)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff818f71b0)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81903be0)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff81934075)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff81938685)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff81939dec)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81943583)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819ed9ba)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff819f2f67)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff81a195a2)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/net/tun.c (ffffffff81a62d41)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a67961)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6e83d)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_poll
```
```
In drivers/usb/core/devio.c (ffffffff81aa7c96)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/input/input.c (ffffffff81b15655)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff81b1b8a8)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff81b1ca67)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff81b23651)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff81b299b1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/pps/pps.c (ffffffff81b3a755)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81b3d44d)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff81b5b3d0)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff81b7a0f1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff81c005db)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81ce8a33)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81d7d522)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff81e04ae3)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
```
In net/xdp/xsk.c (ffffffff81e184af)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
```
```
In net/mptcp/protocol.c (ffffffff81e1cfc3)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107dd65)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_poll
```
```
In kernel/fork.c (ffffffff810e4531)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/build_utility.c (ffffffff8117bc7b)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_poll
```
```
In kernel/printk/printk.c (ffffffff8118eb2d)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff812485f5)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff8124b75a)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff8126279b)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/bpf/ringbuf.c (ffffffff813044e7)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:ringbuf_map_poll_user
  - kernel/bpf/ringbuf.c:ringbuf_map_poll_kern
```
```
In kernel/events/core.c (ffffffff81334705)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff813fb0e1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff81487d3b)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff814daf2a)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0073)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e3623)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff814e6f2f)
Location: include/linux/poll.h:46
Inline: True
```
```
In fs/signalfd.c (ffffffff814e9a6e)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff814ea56b)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff814ebe01)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff814ecc06)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/proc/proc_sysctl.c (ffffffff8154220e)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff815477a5)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff8154d760)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff81615e4f)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff816192e4)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff816227c1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff81648f32)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff816a7554)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff816a8304)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_poll_query
```
```
In security/apparmor/apparmorfs.c (ffffffff816bc023)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:listener_poll
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In io_uring/io_uring.c (ffffffff817862e1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_poll
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c6a09)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_poll
  - drivers/gpio/gpiolib-cdev.c:lineevent_poll
  - drivers/gpio/gpiolib-cdev.c:linereq_poll
```
```
In drivers/pci/vgaarb.c (ffffffff8191e334)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_fpoll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff819e2715)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2afc1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff81a31e75)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff81a4ff10)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81a5dc90)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff81a92f75)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff81a98765)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff81a9a08c)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81aa5fe3)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b6acf7)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff81b70cd7)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff81b9a622)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/net/tun.c (ffffffff81bedff1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfa271)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c0330f)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_poll
```
```
In drivers/usb/core/devio.c (ffffffff81c2ec56)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/input/input.c (ffffffff81ca6ab5)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff81cad688)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff81cae9b7)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff81cb6981)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff81cbd5e1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/pps/pps.c (ffffffff81cd0345)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81cd348d)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff81cf4d90)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff81d18491)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff81dafddb)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81ead0c3)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81f4ad32)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff81fd9c53)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
```
In net/xdp/xsk.c (ffffffff81fef811)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
```
```
In net/mptcp/protocol.c (ffffffff81ff4503)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81080145)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_poll
```
```
In kernel/fork.c (ffffffff810efbc1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/build_utility.c (ffffffff8118c95c)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_poll
```
```
In kernel/printk/printk.c (ffffffff811a02c8)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff8125f9e5)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff812629ea)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff8127977b)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/bpf/ringbuf.c (ffffffff81332e77)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:ringbuf_map_poll_user
  - kernel/bpf/ringbuf.c:ringbuf_map_poll_kern
```
```
In kernel/events/core.c (ffffffff81365445)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff8142e161)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff814bcbfb)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff8150f4da)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81516933)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81519f63)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff8151d76f)
Location: include/linux/poll.h:46
Inline: True
```
```
In fs/signalfd.c (ffffffff8152080e)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff8152130b)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff81522ba1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff815238a6)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/proc/proc_sysctl.c (ffffffff8157a371)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff8157f3c5)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff81585403)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff8164dedf)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff816513a4)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff8165ac01)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff81681495)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff816dff54)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff816e0d54)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_poll_query
```
```
In security/apparmor/apparmorfs.c (ffffffff816f3684)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:listener_poll
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In io_uring/io_uring.c (ffffffff817c9161)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_poll
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81909829)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_poll
  - drivers/gpio/gpiolib-cdev.c:lineevent_poll
  - drivers/gpio/gpiolib-cdev.c:linereq_poll
```
```
In drivers/pci/vgaarb.c (ffffffff819616e4)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_fpoll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff81a2ad15)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a74771)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff81a7b755)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff81a9a200)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81aa82c0)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff81ade7f5)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff81ae3f75)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff81ae58fc)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81af17e3)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbe157)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff81bc4507)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff81bf0bc2)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/net/tun.c (ffffffff81c46521)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c5f8b1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c6865d)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_poll
```
```
In drivers/usb/core/devio.c (ffffffff81c95eb6)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/input/input.c (ffffffff81d0e1f5)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff81d14c68)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff81d15fa7)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff81d1e021)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff81d24ef1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/pps/pps.c (ffffffff81d37d85)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81d3b03d)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff81d5cba0)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff81d81761)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff81e2004b)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81f0b7e5)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81faa9e2)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff82055923)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
```
In net/xdp/xsk.c (ffffffff8206b7d1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
```
```
In net/mptcp/protocol.c (ffffffff82070eb3)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81087c55)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_poll
```
```
In kernel/fork.c (ffffffff810f8fd1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/build_utility.c (ffffffff8119b30c)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_poll
```
```
In kernel/printk/printk.c (ffffffff811af2e8)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff81279b35)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff8127cc2a)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff81294233)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/bpf/ringbuf.c (ffffffff81357567)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:ringbuf_map_poll_user
  - kernel/bpf/ringbuf.c:ringbuf_map_poll_kern
```
```
In kernel/events/core.c (ffffffff8138e565)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff81467c21)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff814ef0ab)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff815439ea)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154ad23)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154e333)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff81551d4f)
Location: include/linux/poll.h:46
Inline: True
```
```
In fs/signalfd.c (ffffffff81554e1e)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff8155594b)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff815571c1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff81557ec6)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_poll
```
```
In fs/proc/proc_sysctl.c (ffffffff815b2c81)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff815b7e05)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff815bdeb3)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff8168743f)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff8168a9b4)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff816948d1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff816bd8c5)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff8171cbd4)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff8171d9d4)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_poll_query
```
```
In security/apparmor/apparmorfs.c (ffffffff81730444)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:listener_poll
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In io_uring/io_uring.c (ffffffff81816f61)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_poll
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff819521c5)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_poll
  - drivers/gpio/gpiolib-cdev.c:lineevent_poll
  - drivers/gpio/gpiolib-cdev.c:linereq_poll
```
```
In drivers/pci/vgaarb.c (ffffffff819aaf24)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_fpoll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff81a75ee5)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac68d1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff81acdc05)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff81aecd30)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81afad80)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff81b31c15)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff81b37345)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff81b38c8c)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81b44d43)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c128a7)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff81c19127)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff81c46482)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c967e1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_poll
```
```
In drivers/gpu/drm/drm_debugfs_crc.c (ffffffff81cbb1ca)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_poll
```
```
In drivers/net/tun.c (ffffffff81cfbe31)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d16251)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff81d4a996)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/input/input.c (ffffffff81dc3e15)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff81dca888)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff81dcbc27)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff81dd3d21)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff81ddac61)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/pps/pps.c (ffffffff81dee005)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81df1956)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff81e140e0)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff81e38dd1)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff81eddf2b)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff81fcf895)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff82077dd2)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff82128243)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
```
In net/xdp/xsk.c (ffffffff8213f561)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
```
```
In net/mptcp/protocol.c (ffffffff821454d3)
Location: include/linux/poll.h:46
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f129c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/psi.c (ffff800010168454)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/printk/printk.c (ffff800010172ea0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffff80001020807c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffff80001020a9dc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffff80001021ce48)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffff8000102939dc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffff8000103227f4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffff80001038f7e4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffff8000103e71bc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ec77c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ee4dc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffff8000103f09a0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffff8000103f3488)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffff8000103f4810)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffff8000103f5b0c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffff8000103f6b5c)
Location: include/linux/poll.h:48
Inline: True
```
```
In fs/io_uring.c (ffff80001040004c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
```
```
In fs/proc/proc_sysctl.c (ffff800010449fa0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffff80001044f94c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffff800010455bb8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (ffff8000104fd880)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffff800010502224)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffff80001050c5a0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffff80001052a60c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffff8000105789e4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffff8000105791dc)
Location: include/linux/poll.h:48
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffff800010589200)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib.c (ffff8000106bd6b4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff800010839d1c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/tty/n_tty.c (ffff800010854c1c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffff800010867b20)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffff8000108abcc0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffff8000108b3d4c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffff8000108b8f14)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffff800010965c78)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffff800010969fe4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffff800010990978)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffff8000109bf988)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffff8000109dce3c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a0168c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffff800010a2be7c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffff800010a33ffc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffff800010a94efc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffff800010a9b4f8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffff800010a9d220)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffff800010aa3c3c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffff800010aaa3a4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/media/cec/cec-api.c (ffff800010ac1e10)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_poll
```
```
In drivers/pps/pps.c (ffff800010ac5414)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffff800010ac855c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffff800010ae2128)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffff800010b067e4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffff800010bbc56c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffff800010c70610)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffff800010cf1c54)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffff800010d6b334)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0350704)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/psi.c (c03b395c)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/printk/printk.c (c03c47a8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (c0446f78)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (c04495dc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (c045b954)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (c04c4a44)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (c053ad74)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (c05764cc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (c05bedc0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (c05c2d1c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (c05c46e0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (c05c6d08)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
  - fs/eventpoll.c:ep_item_poll
```
```
In fs/signalfd.c (c05c88c0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (c05c9138)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (c05ca4e0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (c05cb244)
Location: include/linux/poll.h:48
Inline: True
```
```
In fs/io_uring.c (c05d1ef4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
```
```
In fs/proc/proc_sysctl.c (c060f2b4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (c0612e00)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (c0617e3c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (c06bae28)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (c06bf4a8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (c06c5e9c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (c06e262c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (c072b87c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (c072ca20)
Location: include/linux/poll.h:48
Inline: True
```
```
In security/apparmor/apparmorfs.c (c073a514)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib.c (c085cd18)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/tty/n_tty.c (c095f9c0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (c096db90)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (c09a7aa8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (c09ade04)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (c09b24f4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (c0a3c844)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (c0a40060)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (c0a60a9c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (c0a8d10c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (c0ac24cc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (c0adb560)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (c0b018d8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (c0b07814)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (c0b77bcc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (c0b7ce74)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (c0b7e57c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (c0b834ec)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (c0b89160)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/media/cec/cec-api.c (c0ba3b84)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_poll
```
```
In drivers/pps/pps.c (c0ba5600)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (c0ba7f10)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (c0bc3468)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (c0be5390)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In sound/core/control.c (c0c84cf0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - sound/core/control.c:snd_ctl_poll
```
```
In sound/core/timer.c (c0c8bb04)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - sound/core/timer.c:snd_timer_user_poll
```
```
In sound/core/pcm_native.c (c0c93c2c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_poll
```
```
In sound/core/compress_offload.c (c0c9d768)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - sound/core/compress_offload.c:snd_compr_poll
```
```
In net/core/datagram.c (c0cd8894)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (c0d7ea48)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (c0df7ac4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (c0e69758)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/rtasd.c (c000000000040260)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtasd.c:rtas_log_poll
```
```
In kernel/fork.c (c000000000136e4c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/psi.c (c0000000001c0248)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/printk/printk.c (c0000000001ca6f4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (c000000000285140)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (c000000000287d48)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (c0000000002a0818)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (c00000000033e3d8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (c0000000003f8204)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (c000000000486fd4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (c0000000004ed68c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f35bc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f5b8c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (c0000000004f8120)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (c0000000004fbe18)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (c0000000004fbfb4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (c0000000004fd970)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (c0000000004febd4)
Location: include/linux/poll.h:48
Inline: True
```
```
In fs/io_uring.c (c000000000509560)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
```
```
In fs/proc/proc_sysctl.c (c000000000561b24)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (c0000000005678fc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (c00000000056f7d4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (c000000000640d74)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (c0000000006477ec)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (c00000000064ff80)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (c00000000067657c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (c0000000006e25b4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (c0000000006e3c40)
Location: include/linux/poll.h:48
Inline: True
```
```
In security/apparmor/apparmorfs.c (c0000000006f9f5c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib.c (c000000000838f00)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/tty/n_tty.c (c0000000008f4df8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (c000000000907c2c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (c0000000009434c8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (c00000000094d528)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (c000000000959c80)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (c000000000a1d260)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (c000000000a226fc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (c000000000a504d4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (c000000000a80c28)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (c000000000aa2840)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa5430)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (c000000000ae90d4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (c000000000af1898)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (c000000000b73e58)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (c000000000b7bae8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (c000000000b7dba8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (c000000000b849b0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (c000000000b8c750)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/media/cec/cec-api.c (c000000000ba45c0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_poll
```
```
In drivers/pps/pps.c (c000000000ba6940)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (c000000000ba9dc8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (c000000000bc9b34)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (c000000000bf72e4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (c000000000c94600)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (c000000000d76864)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (c000000000e15868)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (c000000000ea8a80)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000be990)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/psi.c (ffffffe00010981e)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/printk/printk.c (ffffffe00010f010)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffe00016a988)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffe00016c448)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffe00017a678)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffffffe0001c3a1c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffe0002235fa)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffe00025f47e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffe00029c1be)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffe0002a04aa)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a1aaa)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffe0002a31c2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffffffe0002a5322)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffe0002a54ee)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffe0002a6382)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffe0002a6e2a)
Location: include/linux/poll.h:48
Inline: True
```
```
In fs/io_uring.c (ffffffe0002ac758)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
```
```
In fs/proc/proc_sysctl.c (ffffffe0002df77a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffe0002e2dee)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffe0002e76ae)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffe00036bf4a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffe00036f300)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffe000376dcc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffe00038cab8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffe0003cadce)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffe0003cb846)
Location: include/linux/poll.h:48
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffe0003d8064)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a3f86)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/tty/n_tty.c (ffffffe000531e42)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffe00053d25e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffe000560438)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffe000565c68)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffe000569488)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffe0005d294c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffe0005d59d0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffe0005f2a5c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffe000612b7a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffe000627b4c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062b508)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffe00064d2c0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffe000651c54)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffe0006a6d28)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffe0006abbe2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffe0006ad0a2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffe0006b1280)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffe0006b5882)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/media/cec/cec-api.c (ffffffe0006c314a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_poll
```
```
In drivers/pps/pps.c (ffffffe0006c4736)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffe0006c692e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffe0006d8baa)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffe0006f54e2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffe00074a6e0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffe0007d4b74)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffe00083da04)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffe00089dbac)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053175)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_poll
```
```
In kernel/fork.c (ffffffff810968e2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/psi.c (ffffffff810fc662)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/printk/printk.c (ffffffff8110af0a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff811893b4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff8118b352)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff8119af91)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffffffff811ff930)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff81280091)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff812df492)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff813240da)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81327b04)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81329814)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff8132bf2c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffffffff8132e8cc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff8132e9cc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff8132fe81)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff813309b2)
Location: include/linux/poll.h:48
Inline: True
```
```
In fs/io_uring.c (ffffffff813385f1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
```
```
In fs/proc/proc_sysctl.c (ffffffff81375959)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff81379fe5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff8137e87e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff81414916)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff81417d22)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff8141fed4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff81439f10)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff8147ea97)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff8147f644)
Location: include/linux/poll.h:48
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff8148c2a4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib.c (ffffffff8155f211)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81635031)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff8163a2e5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff8164d3e5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff8165a080)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff81680c55)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff81687423)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff816896eb)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81694554)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff8171a152)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff8171d2d9)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff8173c2c2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff81772908)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff81787084)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178b503)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff817b2c36)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffff817b8525)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffff8180af25)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff81810198)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff81811797)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff81815d31)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff8181b361)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/media/cec/cec-api.c (ffffffff81822bdb)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_poll
```
```
In drivers/pps/pps.c (ffffffff81824885)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81826e85)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff81835d6b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff818557b1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff818c1eab)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff8195d9b0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff819d09a2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff81a3a7e5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81043745)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/fork.c (ffffffff81085362)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/psi.c (ffffffff810ec872)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/printk/printk.c (ffffffff810fbd9a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff8117c4f4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff8117e452)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff8118e011)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffffffff811f2680)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff81271f01)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff812d00d2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff81314c7a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813186a4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131a3b4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff8131c68c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffffffff8131f51c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff8131f60c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff81320aa1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff813215a2)
Location: include/linux/poll.h:48
Inline: True
```
```
In fs/io_uring.c (ffffffff81329321)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
```
```
In fs/proc/proc_sysctl.c (ffffffff81366429)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff8136aab5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff8136f30e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff81405396)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff814087a2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff81410954)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff8142a980)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff8146f4b7)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff81470064)
Location: include/linux/poll.h:48
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff8147ccc4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib.c (ffffffff81550061)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/tty/n_tty.c (ffffffff8162d835)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff8163a400)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff8165e925)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff81665013)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff8166716b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81671f44)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff816f35c2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff816f6739)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff8171df62)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff817526b8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff817669d4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817742d3)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff817a4666)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffff817a9f55)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffff817d2695)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff817d78e8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff817d8ed7)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff817dd431)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff817e2a51)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/media/cec/cec-api.c (ffffffff817ea27b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_poll
```
```
In drivers/pps/pps.c (ffffffff817ebf25)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff817ee515)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff817fd3db)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff8181cdc1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff8187bdeb)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff819174a0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff8198d762)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff819f7405)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053aa5)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/fork.c (ffffffff81096892)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/psi.c (ffffffff810f9822)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/printk/printk.c (ffffffff81108dfa)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff81187184)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff81189122)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff81198d61)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffffffff811fd700)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff8127dea1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff812dd2a2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff81321baa)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813255d4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813272e4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff813299fc)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffffffff8132c39c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff8132c49c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff8132d951)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff8132e482)
Location: include/linux/poll.h:48
Inline: True
```
```
In fs/io_uring.c (ffffffff813360c1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
```
```
In fs/proc/proc_sysctl.c (ffffffff81373429)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff81377ab5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff8137c34e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff81411c96)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff81413ec2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff8141c074)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff814360b0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff8147ab37)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff8147b6e4)
Location: include/linux/poll.h:48
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff81488344)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib.c (ffffffff8155dd81)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff816343e5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81662db1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff81668435)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff8167b7a5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81688440)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff816af035)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff816b5763)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff816b795b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816c27c4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81758f22)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff8175c0a9)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff8177ca52)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff817a2c68)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff817b7434)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bb8a3)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff817ef6d6)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffff817f4fc5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffff8184a0a5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff8184f318)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff81850917)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff81857211)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff8185c841)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/media/cec/cec-api.c (ffffffff8186fb1b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_poll
```
```
In drivers/pps/pps.c (ffffffff818717c5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81873dc5)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff8188539b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff818a4de1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff81912eab)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff819c8180)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81a3b422)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff81aa6695)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81054ff5)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/fork.c (ffffffff8109e722)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/fork.c:pidfd_poll
```
```
In kernel/sched/psi.c (ffffffff81104978)
Location: include/linux/poll.h:48
Inline: True
```
```
In kernel/printk/printk.c (ffffffff8111402a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_poll
```
```
In kernel/seccomp.c (ffffffff81194ad4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_notify_poll
```
```
In kernel/relay.c (ffffffff81196a72)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_poll
```
```
In kernel/trace/ring_buffer.c (ffffffff811a69d1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_poll_wait
```
```
In kernel/events/core.c (ffffffff8120c540)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - kernel/events/core.c:perf_poll
```
```
In mm/swapfile.c (ffffffff8128da51)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:swaps_poll
```
```
In fs/pipe.c (ffffffff812ee232)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/pipe.c:pipe_poll
```
```
In fs/proc_namespace.c (ffffffff8133390a)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_poll
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81337084)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81338d94)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
```
In fs/eventpoll.c (ffffffff8133b35c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_eventpoll_poll
```
```
In fs/signalfd.c (ffffffff8133e4ce)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_poll
```
```
In fs/timerfd.c (ffffffff8133ee1c)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_poll
```
```
In fs/eventfd.c (ffffffff813402c1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_poll
```
```
In fs/userfaultfd.c (ffffffff81340eb2)
Location: include/linux/poll.h:48
Inline: True
```
```
In fs/io_uring.c (ffffffff81349191)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
```
```
In fs/proc/proc_sysctl.c (ffffffff813874b9)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_poll
```
```
In fs/proc/kmsg.c (ffffffff8138b565)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/proc/kmsg.c:kmsg_poll
```
```
In fs/kernfs/file.c (ffffffff8138fe2e)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_generic_poll
```
```
In fs/ecryptfs/miscdev.c (ffffffff81427906)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_poll
```
```
In fs/fuse/dev.c (ffffffff8142bae6)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_poll
```
```
In fs/fuse/file.c (ffffffff81431bb4)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_poll
```
```
In ipc/mqueue.c (ffffffff8144c452)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_poll_file
```
```
In security/tomoyo/audit.c (ffffffff81492627)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_poll_log
```
```
In security/tomoyo/common.c (ffffffff814937c4)
Location: include/linux/poll.h:48
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff8149fe84)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_poll
```
```
In drivers/gpio/gpiolib.c (ffffffff81577c11)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_poll
```
```
In drivers/acpi/acpi_dbg.c (ffffffff8164e705)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_poll
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167d381)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_poll
```
```
In drivers/xen/mcelog.c (ffffffff81682a35)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_chrdev_poll
```
```
In drivers/tty/n_tty.c (ffffffff81695e05)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_poll
  - drivers/tty/n_tty.c:n_tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff816a2a30)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_poll
```
```
In drivers/char/random.c (ffffffff816c9455)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/random.c:random_poll
  - drivers/char/random.c:random_poll
```
```
In drivers/char/virtio_console.c (ffffffff816cf443)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_poll
```
```
In drivers/char/hpet.c (ffffffff816d1a2b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_poll
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816dcd94)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_poll
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817743b2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/sync_file.c (ffffffff81777749)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_poll
```
```
In drivers/scsi/sg.c (ffffffff81796882)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_poll
```
```
In drivers/gpu/vga/vgaarb.c (ffffffff817bcae8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_fpoll
```
```
In drivers/net/tun.c (ffffffff817cf4d1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d5af3)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_poll
```
```
In drivers/usb/core/devio.c (ffffffff81809916)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_poll
```
```
In drivers/usb/core/devices.c (ffffffff8180f205)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_poll
```
```
In drivers/input/input.c (ffffffff81865265)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/input.c:input_proc_devices_poll
```
```
In drivers/input/mousedev.c (ffffffff8186a4c8)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_poll
```
```
In drivers/input/evdev.c (ffffffff8186ba97)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_poll
```
```
In drivers/input/misc/uinput.c (ffffffff81872341)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_poll
```
```
In drivers/rtc/dev.c (ffffffff81877ac1)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_poll
```
```
In drivers/media/cec/cec-api.c (ffffffff81889a9b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_poll
```
```
In drivers/pps/pps.c (ffffffff8188d165)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_poll
```
```
In drivers/ptp/ptp_chardev.c (ffffffff8188f775)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_poll
```
```
In drivers/md/md.c (ffffffff818a0e6b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/md.c:mdstat_poll
```
```
In drivers/md/dm-ioctl.c (ffffffff818c1021)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_poll
```
```
In net/core/datagram.c (ffffffff8193402b)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/ipv4/tcp.c (ffffffff819d1cd0)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/unix/af_unix.c (ffffffff81a460a2)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
```
In net/rfkill/core.c (ffffffff81ab2a35)
Location: include/linux/poll.h:48
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_poll
```
</details>
</li>
</ul>

## Differences
