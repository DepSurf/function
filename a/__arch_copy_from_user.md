# Function: <code>__arch_copy_from_user</code>

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
  - arch/arm64/kernel/ptrace.c:compat_tls_set
  - arch/arm64/kernel/ptrace.c:compat_vfp_set
  - arch/arm64/kernel/ptrace.c:compat_gpr_set
  - arch/arm64/kernel/ptrace.c:pac_generic_keys_set
  - arch/arm64/kernel/ptrace.c:pac_address_keys_set
  - arch/arm64/kernel/ptrace.c:sve_set
  - arch/arm64/kernel/ptrace.c:system_call_set
  - arch/arm64/kernel/ptrace.c:tls_set
  - arch/arm64/kernel/ptrace.c:gpr_set
  - arch/arm64/kernel/ptrace.c:hw_break_set
  - arch/arm64/kernel/ptrace.c:hw_break_set
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_fpsimd_context
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
  - arch/arm64/kernel/perf_callchain.c:perf_callchain_user
  - virt/kvm/kvm_main.c:kvm_read_guest_cached
  - virt/kvm/kvm_main.c:__kvm_read_guest_atomic
  - virt/kvm/kvm_main.c:__kvm_read_guest_page
  - virt/kvm/kvm_main.c:_copy_from_user
  - virt/kvm/arm/arm.c:_copy_from_user
  - virt/kvm/arm/psci.c:kvm_arm_set_fw_reg
  - arch/arm64/kvm/guest.c:_copy_from_user
  - arch/arm64/kvm/sys_regs.c:_copy_from_user
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_set_attr
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sysctl_binary.c:__arm64_compat_sys_sysctl
  - kernel/sysctl_binary.c:__arm64_sys_sysctl
  - kernel/capability.c:__arm64_sys_capset
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_writedata
  - kernel/ptrace.c:_copy_from_user
  - kernel/signal.c:__arm64_sys_rt_sigsuspend
  - kernel/signal.c:__arm64_sys_sigprocmask
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__arm64_sys_sigaltstack
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:_copy_from_user
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__arm64_sys_setrlimit
  - kernel/sys.c:__arm64_sys_prlimit64
  - kernel/sys.c:__arm64_compat_sys_setrlimit
  - kernel/sys.c:__arm64_sys_setdomainname
  - kernel/sys.c:__arm64_sys_sethostname
  - kernel/sys.c:_copy_from_user
  - kernel/sched/core.c:_copy_from_user
  - kernel/sched/debug.c:sched_feat_write
  - kernel/power/qos.c:pm_qos_power_write
  - kernel/kcmp.c:kcmp_epoll_target
  - kernel/profile.c:write_profile
  - kernel/time/time.c:_copy_from_user
  - kernel/time/posix-timers.c:_copy_from_user
  - kernel/time/itimer.c:__arm64_sys_setitimer
  - kernel/module.c:copy_chunked_from_user
  - kernel/kexec_core.c:_copy_from_user
  - kernel/kexec.c:_copy_from_user
  - kernel/compat.c:get_compat_sigset
  - kernel/compat.c:get_compat_itimerval
  - kernel/user_namespace.c:proc_setgroups_write
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/seccomp.c:_copy_from_user
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:_copy_from_user
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/trace_uprobe.c:_copy_from_user
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/syscall.c:_copy_from_user
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:_copy_from_user
  - kernel/bpf/cgroup.c:_copy_from_user
  - kernel/events/core.c:perf_output_sample_ustack
  - kernel/events/core.c:_copy_from_user
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:__rseq_handle_notify_resume
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/util.c:_copy_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:wp_page_copy
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - mm/mempolicy.c:_copy_from_user
  - mm/migrate.c:do_pages_stat
  - mm/memfd.c:__arm64_sys_memfd_create
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_compat_sys_sendfile64
  - fs/read_write.c:__arm64_sys_sendfile64
  - fs/read_write.c:_copy_from_user
  - fs/fcntl.c:_copy_from_user
  - fs/ioctl.c:ioctl_preallocate
  - fs/ioctl.c:_copy_from_user
  - fs/select.c:__arm64_compat_sys_old_select
  - fs/select.c:do_sys_poll
  - fs/select.c:__arm64_sys_select
  - fs/select.c:_copy_from_user
  - fs/xattr.c:setxattr
  - fs/libfs.c:_copy_from_user
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/timerfd.c:timerfd_ioctl
  - fs/eventfd.c:eventfd_write
  - fs/userfaultfd.c:_copy_from_user
  - fs/aio.c:__arm64_compat_sys_io_pgetevents_time64
  - fs/aio.c:__arm64_compat_sys_io_pgetevents
  - fs/aio.c:__arm64_sys_io_pgetevents
  - fs/aio.c:io_submit_one
  - fs/io_uring.c:_copy_from_user
  - fs/crypto/keyring.c:_copy_from_user
  - fs/crypto/policy.c:_copy_from_user
  - fs/verity/enable.c:_copy_from_user
  - fs/compat_binfmt_elf.c:fill_psinfo
  - fs/fhandle.c:_copy_from_user
  - fs/quota/quota.c:_copy_from_user
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:_copy_from_user
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/configfs/file.c:configfs_write_file
  - fs/ext4/ioctl.c:_copy_from_user
  - fs/fat/file.c:fat_generic_ioctl
  - ipc/compat.c:_copy_from_user
  - ipc/msgutil.c:_copy_from_user
  - ipc/sem.c:_copy_from_user
  - ipc/shm.c:_copy_from_user
  - ipc/mqueue.c:_copy_from_user
  - security/keys/keyctl.c:_copy_from_user
  - security/keys/compat_dh.c:compat_keyctl_dh_compute
  - security/keys/dh.c:_copy_from_user
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
  - security/selinux/selinuxfs.c:sel_write_load
  - security/smack/smackfs.c:_copy_from_user
  - security/apparmor/apparmorfs.c:_copy_from_user
  - block/ioctl.c:_copy_from_user
  - block/scsi_ioctl.c:_copy_from_user
  - block/bsg.c:bsg_scsi_fill_hdr
  - block/bsg.c:_copy_from_user
  - block/blk-mq-debugfs.c:queue_state_write
  - block/sed-opal.c:write_shadow_mbr
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:copyin
  - lib/kfifo.c:_copy_from_user
  - lib/kstrtox.c:_copy_from_user
  - lib/checksum.c:csum_partial_copy_from_user
  - drivers/gpio/gpiolib.c:_copy_from_user
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:_copy_from_user
  - drivers/video/fbdev/core/fbcmap.c:_copy_from_user
  - drivers/video/fbdev/imsttfb.c:_copy_from_user
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/tty/tty_io.c:compat_tty_tiocsserial
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:_copy_from_user
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/tty_ioctl.c:_copy_from_user
  - drivers/tty/vt/vt_ioctl.c:_copy_from_user
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/selection.c:_copy_from_user
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
  - drivers/tty/vt/keyboard.c:_copy_from_user
  - drivers/tty/vt/consolemap.c:_copy_from_user
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/serial/serial_core.c:_copy_from_user
  - drivers/char/mem.c:write_mem
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/lightnvm/core.c:_copy_from_user
  - drivers/block/loop.c:_copy_from_user
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/nvdimm/bus.c:_copy_from_user
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/dma-buf/sync_file.c:_copy_from_user
  - drivers/dma-buf/sw_sync.c:_copy_from_user
  - drivers/dma-buf/udmabuf.c:_copy_from_user
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:_copy_from_user
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/net/tun.c:_copy_from_user
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:ppp_set_compress
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/net/ppp/ppp_generic.c:_copy_from_user
  - drivers/cdrom/cdrom.c:_copy_from_user
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:get_urb32
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:_copy_from_user
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/input/input-compat.c:_copy_from_user
  - drivers/input/evdev.c:evdev_handle_set_keycode_v2
  - drivers/input/evdev.c:_copy_from_user
  - drivers/input/misc/uinput.c:_copy_from_user
  - drivers/rtc/dev.c:_copy_from_user
  - drivers/i2c/i2c-dev.c:_copy_from_user
  - drivers/media/cec/cec-api.c:_copy_from_user
  - drivers/pps/pps.c:_copy_from_user
  - drivers/ptp/ptp_chardev.c:_copy_from_user
  - drivers/md/md.c:_copy_from_user
  - drivers/md/dm-ioctl.c:_copy_from_user
  - drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user
  - drivers/mmc/core/block.c:_copy_from_user
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - net/socket.c:routing_ioctl
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:_copy_from_user
  - net/core/sock.c:_copy_from_user
  - net/core/ethtool.c:_copy_from_user
  - net/core/filter.c:_copy_from_user
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:cmsghdr_from_user_compat_to_kern
  - net/compat.c:get_compat_msghdr
  - net/bpf/test_run.c:_copy_from_user
  - net/ipv4/ip_options.c:ip_options_get_from_user
  - net/ipv4/ip_sockglue.c:_copy_from_user
  - net/ipv4/tcp.c:tcp_repair_options_est
  - net/ipv4/tcp.c:_copy_from_user
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/raw.c:raw_seticmpfilter
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/af_inet.c:_copy_from_user
  - net/ipv4/ipmr.c:_copy_from_user
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/ipv6_sockglue.c:_copy_from_user
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/ip6_flowlabel.c:_copy_from_user
  - net/ipv6/ip6mr.c:_copy_from_user
  - net/packet/af_packet.c:_copy_from_user
  - net/wireless/wext-core.c:_copy_from_user
  - net/wireless/wext-priv.c:_copy_from_user
  - net/rfkill/core.c:rfkill_fop_write
  - net/xdp/xsk.c:_copy_from_user
  - arch/arm64/lib/uaccess_flushcache.c:__copy_user_flushcache
  - arch/arm64/lib/uaccess_flushcache.c:__copy_user_flushcache
```
**Symbols:**

```
ffff800010d81fc0-ffff800010d821d8: __arch_copy_from_user (STB_GLOBAL)
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
