# Function: <code>kill_fasync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8121f4f0)
Location: fs/fcntl.c:723
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/splice.c:wakeup_pipe_readers
  - fs/splice.c:splice_to_pipe
  - fs/splice.c:wakeup_pipe_writers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:queue_request
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_queue_forget
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff8121f4f0-ffffffff8121f57c: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81246d70)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:splice_to_pipe
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:queue_request
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff81246d70-ffffffff81246dfc: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81259d60)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:queue_request
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff81259d60-ffffffff81259dec: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81266710)
Location: fs/fcntl.c:997
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:queue_request
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff81266710-ffffffff812667a8: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81288fb0)
Location: fs/fcntl.c:1007
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:queue_request
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff81288fb0-ffffffff81289048: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fcntl.c (0)
Location: fs/fcntl.c:1013
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:queue_request
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_xdp_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff812af762-ffffffff812af773: kill_fasync.cold.4 (STB_LOCAL)
ffffffff812af320-ffffffff812af3b4: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fcntl.c (0)
Location: fs/fcntl.c:1017
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:queue_request
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_xdp_xmit
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff812c48e2-ffffffff812c48f3: kill_fasync.cold.5 (STB_LOCAL)
ffffffff812c4450-ffffffff812c44e4: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fcntl.c (ffffffff812e0ebb)
Location: fs/fcntl.c:1017
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/io_uring.c:io_commit_cqring
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:queue_interrupt
  - fs/fuse/dev.c:fuse_queue_forget
  - fs/fuse/dev.c:queue_request
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff812e132e-ffffffff812e133f: kill_fasync.cold (STB_LOCAL)
ffffffff812e0eb0-ffffffff812e0f31: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fcntl.c (ffffffff812f296b)
Location: fs/fcntl.c:1017
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/io_uring.c:io_commit_cqring
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff812f2dc6-ffffffff812f2dd7: kill_fasync.cold (STB_LOCAL)
ffffffff812f2960-ffffffff812f29e1: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fcntl.c (ffffffff8132abfb)
Location: fs/fcntl.c:1019
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/notify/notification.c:fsnotify_add_event
  - fs/io_uring.c:io_commit_cqring
  - fs/locks.c:lease_break_callback
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:crng_reseed
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_uie_update_irq
  - drivers/rtc/interface.c:rtc_aie_update_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff8132b056-ffffffff8132b067: kill_fasync.cold (STB_LOCAL)
ffffffff8132abf0-ffffffff8132ac71: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fcntl.c (ffffffff8133617b)
Location: fs/fcntl.c:1021
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:do_splice
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/notify/notification.c:fsnotify_add_event
  - fs/io_uring.c:io_cqring_ev_posted_iopoll
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/locks.c:lease_break_callback
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:crng_reseed
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/rtc/interface.c:rtc_uie_update_irq
  - drivers/rtc/interface.c:rtc_aie_update_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff81bea65a-ffffffff81bea66b: kill_fasync.cold (STB_LOCAL)
ffffffff81336170-ffffffff813361f6: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fcntl.c (ffffffff8133c32b)
Location: fs/fcntl.c:1026
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/notify/notification.c:fsnotify_add_event
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_cqring_ev_posted
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:crng_reseed
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/rtc/interface.c:rtc_uie_update_irq
  - drivers/rtc/interface.c:rtc_aie_update_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff81bdc696-ffffffff81bdc6a7: kill_fasync.cold (STB_LOCAL)
ffffffff8133c320-ffffffff8133c3a6: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fcntl.c (ffffffff81389ff9)
Location: fs/fcntl.c:1031
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/notify/notification.c:fsnotify_add_event
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:random_ioctl
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/rtc/interface.c:rtc_uie_update_irq
  - drivers/rtc/interface.c:rtc_aie_update_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff81cc3a97-ffffffff81cc3aa8: kill_fasync.cold (STB_LOCAL)
ffffffff81389fe0-ffffffff8138a067: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fcntl.c (ffffffff8140b073)
Location: fs/fcntl.c:1009
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
  - fs/notify/notification.c:fsnotify_insert_event
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:_credit_init_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_uie_update_irq
  - drivers/rtc/interface.c:rtc_aie_update_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff81e762b8-ffffffff81e762c9: kill_fasync.cold (STB_LOCAL)
ffffffff8140b050-ffffffff8140b0fb: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81495920)
Location: fs/fcntl.c:1010
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:__do_sys_vmsplice
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
  - fs/notify/notification.c:fsnotify_insert_event
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_uie_update_irq
  - drivers/rtc/interface.c:rtc_aie_update_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff81495920-ffffffff814959d5: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814ca960)
Location: fs/fcntl.c:1011
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
  - fs/notify/notification.c:fsnotify_insert_event
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_uie_update_irq
  - drivers/rtc/interface.c:rtc_aie_update_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff814ca960-ffffffff814caa12: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814fd220)
Location: fs/fcntl.c:1012
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:splice_pipe_to_pipe
  - fs/splice.c:vmsplice_to_pipe
  - fs/splice.c:splice_file_to_pipe
  - fs/splice.c:splice_to_socket
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
  - fs/notify/notification.c:fsnotify_insert_event
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:__receive_buf
  - drivers/tty/n_tty.c:n_tty_receive_handle_newline
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_uie_update_irq
  - drivers/rtc/interface.c:rtc_aie_update_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff814fd220-ffffffff814fd2d2: kill_fasync (STB_GLOBAL)
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
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffff80001039cc78)
Location: fs/fcntl.c:1017
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/io_uring.c:io_commit_cqring
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffff80001039cc78-ffff80001039cd70: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c05826e0)
Location: fs/fcntl.c:1017
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/io_uring.c:io_commit_cqring
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - drivers/pps/kapi.c:pps_event
  - sound/core/control.c:snd_ctl_dev_disconnect
  - sound/core/timer.c:snd_timer_user_tinterrupt
  - sound/core/timer.c:snd_timer_user_ccallback
  - sound/core/timer.c:snd_timer_user_interrupt
  - sound/core/pcm_lib.c:snd_pcm_period_elapsed
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
c05826e0-c05827a8: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c000000000497940)
Location: fs/fcntl.c:1017
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/io_uring.c:io_commit_cqring
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
c000000000497940-c000000000497a34: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffe000268fba)
Location: fs/fcntl.c:1017
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/io_uring.c:io_commit_cqring
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffe000268fba-ffffffe000269050: kill_fasync (STB_GLOBAL)
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
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fcntl.c (ffffffff812eaf4b)
Location: fs/fcntl.c:1017
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/io_uring.c:io_commit_cqring
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff812eb3a6-ffffffff812eb3b7: kill_fasync.cold (STB_LOCAL)
ffffffff812eaf40-ffffffff812eafc1: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fcntl.c (ffffffff812dbb8b)
Location: fs/fcntl.c:1017
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/io_uring.c:io_commit_cqring
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff812dbfd6-ffffffff812dbfe7: kill_fasync.cold (STB_LOCAL)
ffffffff812dbb80-ffffffff812dbc01: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fcntl.c (ffffffff812e8d5b)
Location: fs/fcntl.c:1017
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/io_uring.c:io_commit_cqring
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff812e91b6-ffffffff812e91c7: kill_fasync.cold (STB_LOCAL)
ffffffff812e8d50-ffffffff812e8dd1: kill_fasync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kill_fasync(struct fasync_struct **fp, int sig, int band);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fcntl.c (ffffffff812f9d34)
Location: fs/fcntl.c:1017
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_wakeup
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/splice.c:wakeup_pipe_writers
  - fs/splice.c:wakeup_pipe_readers
  - fs/notify/notification.c:fsnotify_add_event
  - fs/io_uring.c:io_commit_cqring
  - fs/locks.c:lease_break_callback
  - fs/coredump.c:do_coredump
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_wake_and_unlock
  - drivers/tty/n_tty.c:n_tty_receive_buf_common
  - drivers/tty/n_tty.c:n_tty_receive_char_special
  - drivers/tty/n_tty.c:n_tty_write_wakeup
  - drivers/tty/vt/vc_screen.c:vcs_notifier
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/random.c:credit_entropy_bits
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/net/tun.c:tun_net_xmit
  - drivers/input/mousedev.c:mousedev_cleanup
  - drivers/input/mousedev.c:mousedev_write
  - drivers/input/mousedev.c:mousedev_notify_readers
  - drivers/input/evdev.c:evdev_cleanup
  - drivers/input/evdev.c:evdev_pass_values
  - drivers/rtc/interface.c:rtc_handle_legacy_irq
  - drivers/pps/kapi.c:pps_event
  - net/socket.c:sock_wake_async
  - net/socket.c:sock_wake_async
```
**Symbols:**

```
ffffffff812fa1b6-ffffffff812fa1c7: kill_fasync.cold (STB_LOCAL)
ffffffff812f9d20-ffffffff812f9da5: kill_fasync (STB_GLOBAL)
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
