# Function: <code>__arch_copy_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm64/kernel/ptrace.c:compat_tls_get
  - arch/arm64/kernel/ptrace.c:compat_vfp_get
  - arch/arm64/kernel/ptrace.c:compat_gpr_get
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_get
  - arch/arm64/kernel/ptrace.c:pac_address_keys_get
  - arch/arm64/kernel/ptrace.c:pac_mask_get
  - arch/arm64/kernel/ptrace.c:sve_get
  - arch/arm64/kernel/ptrace.c:system_call_get
  - arch/arm64/kernel/ptrace.c:tls_get
  - arch/arm64/kernel/ptrace.c:fpr_get
  - arch/arm64/kernel/ptrace.c:gpr_get
  - arch/arm64/kernel/ptrace.c:hw_break_get
  - arch/arm64/kernel/ptrace.c:hw_break_get
  - arch/arm64/kernel/signal.c:setup_sigframe
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_sve_context
  - arch/arm64/kernel/signal.c:preserve_fpsimd_context
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/crash_dump.c:copy_oldmem_page
  - virt/kvm/kvm_main.c:kvm_write_guest_offset_cached
  - virt/kvm/kvm_main.c:__kvm_write_guest_page
  - virt/kvm/kvm_main.c:kvm_get_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_get_dirty_log
  - virt/kvm/arm/arm.c:_copy_to_user
  - virt/kvm/arm/psci.c:kvm_arm_get_fw_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/sys_regs.c:reg_to_user
  - arch/arm64/kvm/sys_regs.c:get_wcr
  - arch/arm64/kvm/sys_regs.c:get_wvr
  - arch/arm64/kvm/sys_regs.c:get_bcr
  - arch/arm64/kvm/sys_regs.c:get_bvr
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:_proc_do_string
  - kernel/capability.c:__arm64_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__arm64_sys_rt_sigaction
  - kernel/signal.c:__arm64_sys_sigprocmask
  - kernel/signal.c:__arm64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__arm64_sys_sigaltstack
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__arm64_compat_sys_rt_sigpending
  - kernel/signal.c:__arm64_sys_rt_sigpending
  - kernel/signal.c:__arm64_compat_sys_rt_sigprocmask
  - kernel/signal.c:__arm64_sys_rt_sigprocmask
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__arm64_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__arm64_sys_prlimit64
  - kernel/sys.c:__arm64_compat_sys_getrlimit
  - kernel/sys.c:__arm64_sys_getrlimit
  - kernel/sys.c:__arm64_sys_gethostname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__arm64_compat_sys_times
  - kernel/sys.c:__arm64_sys_times
  - kernel/sched/core.c:__arm64_sys_sched_getaffinity
  - kernel/sched/core.c:__arm64_sys_sched_getattr
  - kernel/sched/core.c:__arm64_sys_sched_getparam
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timespec32
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_itimerval
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:_copy_to_user
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:_copy_to_user
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
  - mm/mincore.c:__do_sys_mincore
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_mbind
  - mm/mempolicy.c:__arm64_compat_sys_set_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_llseek
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/select.c:core_sys_select
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/seq_file.c:seq_read
  - fs/libfs.c:simple_read_from_buffer
  - fs/d_path.c:__arm64_sys_getcwd
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:_copy_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events_ring
  - fs/io_uring.c:io_uring_setup
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:_copy_to_user
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/kcore.c:_copy_to_user
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:do_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/file.c:fat_generic_ioctl
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - ipc/msgutil.c:_copy_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:_copy_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:_copy_to_user
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:_copy_to_user
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg-lib.c:bsg_transport_complete_rq
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:_copy_to_user
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:copyout
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:_copy_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:_copy_to_user
  - drivers/dma-buf/sync_file.c:_copy_to_user
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/ata/libata-scsi.c:_copy_to_user
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:_copy_to_user
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_get
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_str_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/pps/pps.c:_copy_to_user
  - drivers/ptp/ptp_chardev.c:_copy_to_user
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/filter.c:sk_get_filter
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:_copy_to_user
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:_copy_to_user
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffff800010d82580-ffff800010d82798: __arch_copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
