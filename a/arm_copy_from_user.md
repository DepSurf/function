# Function: <code>arm_copy_from_user</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:vfp_set
  - arch/arm/kernel/ptrace.c:vfp_set
  - arch/arm/kernel/ptrace.c:fpa_set
  - arch/arm/kernel/ptrace.c:gpr_set
  - arch/arm/kernel/signal.c:restore_sigframe
  - arch/arm/kernel/signal.c:restore_sigframe
  - arch/arm/kernel/signal.c:restore_vfp_context
  - arch/arm/kernel/signal.c:restore_iwmmxt_context
  - arch/arm/kernel/perf_callchain.c:perf_callchain_user
  - kernel/fork.c:copy_clone_args_from_user
  - kernel/sysctl_binary.c:__se_sys_sysctl
  - kernel/capability.c:__se_sys_capset
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:ptrace_writedata
  - kernel/signal.c:__se_sys_rt_sigsuspend
  - kernel/signal.c:__se_sys_rt_sigaction
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:restore_altstack
  - kernel/signal.c:__se_sys_sigaltstack
  - kernel/signal.c:__se_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:copy_siginfo_from_user
  - kernel/signal.c:__copy_siginfo_from_user
  - kernel/signal.c:__se_sys_rt_sigprocmask
  - kernel/signal.c:set_user_sigmask
  - kernel/sys.c:prctl_set_auxv
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__se_sys_setrlimit
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_setdomainname
  - kernel/sys.c:__se_sys_sethostname
  - kernel/sched/core.c:__se_sys_sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/debug.c:sched_feat_write
  - kernel/power/qos.c:pm_qos_power_write
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/profile.c:write_profile
  - kernel/time/time.c:get_old_itimerspec32
  - kernel/time/time.c:get_old_itimerspec32
  - kernel/time/time.c:get_old_timespec32
  - kernel/time/time.c:get_timespec64
  - kernel/time/time.c:get_old_timex32
  - kernel/time/time.c:__se_sys_settimeofday
  - kernel/time/time.c:__se_sys_settimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:__se_sys_timer_create
  - kernel/time/itimer.c:__se_sys_setitimer
  - kernel/module.c:__se_sys_init_module
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec_core.c:kimage_load_segment
  - kernel/kexec.c:do_kexec_load
  - kernel/user_namespace.c:proc_setgroups_write
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:tracing_clock_write
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:tracing_trace_options_write
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/trace/trace_uprobe.c:process_fetch_insn
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:map_update_elem
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl
  - kernel/events/core.c:perf_copy_attr
  - kernel/events/core.c:perf_output_sample
  - kernel/events/core.c:_perf_ioctl
  - kernel/rseq.c:rseq_ip_fixup
  - kernel/rseq.c:rseq_ip_fixup
  - mm/maccess.c:__probe_user_read
  - mm/maccess.c:__probe_kernel_read
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/util.c:memdup_user_nul
  - mm/util.c:vmemdup_user
  - mm/util.c:memdup_user
  - mm/memory.c:wp_page_copy
  - mm/mmap.c:__se_sys_old_mmap
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/memfd.c:__se_sys_memfd_create
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_sendfile64
  - fs/read_write.c:rw_copy_check_uvector
  - fs/exec.c:copy_strings
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:ioctl_preallocate
  - fs/select.c:do_sys_poll
  - fs/select.c:__se_sys_old_select
  - fs/select.c:kern_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/xattr.c:setxattr
  - fs/libfs.c:simple_attr_write
  - fs/libfs.c:simple_write_to_buffer
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/signalfd.c:__se_sys_signalfd
  - fs/signalfd.c:__se_sys_signalfd4
  - fs/timerfd.c:timerfd_ioctl
  - fs/eventfd.c:eventfd_write
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/userfaultfd.c:userfaultfd_register
  - fs/aio.c:__se_sys_io_pgetevents_time32
  - fs/aio.c:__se_sys_io_pgetevents
  - fs/aio.c:__se_sys_io_submit
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_uring_setup
  - fs/io_uring.c:io_sqe_buffer_register
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_set_policy
  - fs/verity/enable.c:fsverity_ioctl_enable
  - fs/verity/enable.c:enable_verity
  - fs/verity/enable.c:enable_verity
  - fs/binfmt_elf.c:fill_psinfo
  - fs/binfmt_elf_fdpic.c:fill_psinfo
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fhandle.c:__se_sys_open_by_handle_at
  - fs/fhandle.c:do_sys_name_to_handle
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_setquota
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:oom_score_adj_write
  - fs/proc/base.c:oom_adj_write
  - fs/proc/base.c:mem_rw
  - fs/kernfs/file.c:kernfs_fop_write
  - fs/configfs/file.c:configfs_write_file
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/fat/file.c:fat_generic_ioctl
  - fs/pstore/ram_core.c:persistent_ram_update_user
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - fs/efivarfs/file.c:efivarfs_file_write
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:load_msg
  - ipc/msg.c:copy_msqid_from_user
  - ipc/msg.c:copy_msqid_from_user
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:copy_semid_from_user
  - ipc/sem.c:copy_semid_from_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/mqueue.c:__se_sys_mq_getsetattr
  - ipc/mqueue.c:__se_sys_mq_notify
  - ipc/mqueue.c:do_mq_notify
  - ipc/mqueue.c:__se_sys_mq_open
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get_2
  - security/selinux/selinuxfs.c:sel_write_load
  - security/smack/smackfs.c:smk_write_ptrace
  - security/smack/smackfs.c:smk_write_logging
  - security/smack/smackfs.c:smk_write_mapped
  - security/smack/smackfs.c:smk_write_direct
  - security/smack/smackfs.c:smk_write_doi
  - security/apparmor/apparmorfs.c:aa_write_access
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_pr_preempt
  - block/ioctl.c:blk_ioctl_discard
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_fill_hdr
  - block/blk-zoned.c:blkdev_reset_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-mq-debugfs.c:queue_state_write
  - block/sed-opal.c:write_shadow_mbr
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:copyin
  - lib/kfifo.c:kfifo_copy_from_user
  - lib/kfifo.c:kfifo_copy_from_user
  - lib/kstrtox.c:kstrtos8_from_user
  - lib/kstrtox.c:kstrtou8_from_user
  - lib/kstrtox.c:kstrtos16_from_user
  - lib/kstrtox.c:kstrtou16_from_user
  - lib/kstrtox.c:kstrtoint_from_user
  - lib/kstrtox.c:kstrtouint_from_user
  - lib/kstrtox.c:kstrtol_from_user
  - lib/kstrtox.c:kstrtoul_from_user
  - lib/kstrtox.c:kstrtoll_from_user
  - lib/kstrtox.c:kstrtoull_from_user
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbcmap.c:fb_set_user_cmap
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_set_con2fb_map_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:set_termiox
  - drivers/tty/tty_ioctl.c:user_termio_to_kernel_termios
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/selection.c:set_selection_user
  - drivers/tty/vt/selection.c:sel_loadlut
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_kbkeycode_ioctl
  - drivers/tty/vt/consolemap.c:con_set_trans_new
  - drivers/tty/vt/consolemap.c:con_set_trans_old
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:write_mem
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/block/loop.c:loop_set_status64
  - drivers/block/loop.c:loop_set_status_old
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/aat2870-core.c:aat2870_reg_write_file
  - drivers/dma-buf/dma-buf.c:dma_buf_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/dma-buf/udmabuf.c:udmabuf_ioctl
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_host_write
  - drivers/scsi/sg.c:sg_new_write
  - drivers/scsi/sg.c:sg_new_write
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_write
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_write
  - drivers/net/tun.c:tun_set_ebpf
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:get_filter
  - drivers/net/ppp/ppp_generic.c:ppp_write
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_play_blk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_play_msf
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_disconnect_claim
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/host/xhci-debugfs.c:xhci_port_write
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_write
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_write
  - drivers/input/input-compat.c:input_ff_effect_from_user
  - drivers/input/input-compat.c:input_event_from_user
  - drivers/input/evdev.c:evdev_handle_set_keycode_v2
  - drivers/input/evdev.c:evdev_handle_set_keycode
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:evdev_handle_get_keycode
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ff_upload_from_user
  - drivers/input/misc/uinput.c:uinput_dev_setup
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
  - drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_recovery_write
  - sound/core/memory.c:copy_from_user_toio
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_tlv_ioctl
  - sound/core/control.c:snd_ctl_elem_add_user
  - sound/core/control.c:snd_ctl_elem_info_user
  - sound/core/control.c:snd_ctl_elem_list
  - sound/core/info.c:snd_info_text_entry_write
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_sync_ptr
  - sound/core/pcm_native.c:snd_pcm_sw_params_user
  - sound/core/pcm_lib.c:default_write_copy
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_write
  - sound/core/compress_offload.c:snd_compr_write
  - sound/core/compress_offload.c:snd_compr_write
  - sound/soc/soc-generic-dmaengine-pcm.c:dmaengine_copy_user
  - net/socket.c:____sys_sendmsg
  - net/socket.c:copy_msghdr_from_user
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:move_addr_to_kernel
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_timeout
  - net/core/sock.c:sock_set_timeout
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_set_per_queue
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_flash_device
  - net/core/ethtool.c:ethtool_set_channels
  - net/core/ethtool.c:ethtool_set_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_set_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_copy_validate_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:load_link_ksettings_from_user
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_test_init
  - net/ipv4/ip_options.c:ip_options_get_from_user
  - net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_set_dstaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6_flowlabel.c:fl_create
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-priv.c:ioctl_private_iw_point
  - net/rfkill/core.c:rfkill_fop_write
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
c0e7c0cc-c0e7c428: arm_copy_from_user (STB_GLOBAL)
```
</details>
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
