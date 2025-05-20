# Function: <code>_copy_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mcheck/mce.c:__mce_read_apei
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_dostring
  - kernel/capability.c:SyS_capget
  - kernel/ptrace.c:ptrace_readdata
  - kernel/ptrace.c:ptrace_request
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - kernel/signal.c:compat_SyS_rt_sigpending
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:SyS_rt_sigaction
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/sys.c:SYSC_sysinfo
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SyS_times
  - kernel/sys.c:SyS_newuname
  - kernel/sys.c:SyS_newuname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_gethostname
  - kernel/sys.c:SyS_old_getrlimit
  - kernel/sys.c:SyS_getrlimit
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:getrusage
  - kernel/sys.c:SyS_prctl
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:do_syslog
  - kernel/profile.c:read_profile
  - kernel/time/time.c:SYSC_adjtimex
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/time/hrtimer.c:update_rmtp
  - kernel/time/itimer.c:SyS_getitimer
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/time/posix-timers.c:SYSC_clock_adjtime
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/time/posix-timers.c:SyS_timer_gettime
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_clock_gettime
  - kernel/time/posix-timers.c:SyS_clock_getres
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/time/alarmtimer.c:update_rmtp
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/compat.c:compat_SyS_gettimeofday
  - kernel/compat.c:compat_convert_timespec
  - kernel/compat.c:compat_SyS_times
  - kernel/compat.c:C_SYSC_waitid
  - kernel/compat.c:compat_SyS_timer_create
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/relay.c:subbuf_read_actor
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_ioctl
  - mm/backing-dev.c:pdflush_proc_obsolete
  - mm/mincore.c:SyS_mincore
  - mm/mempolicy.c:copy_nodes_to_user
  - mm/mempolicy.c:compat_SyS_set_mempolicy
  - mm/mempolicy.c:compat_SyS_mbind
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:SyS_llseek
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_new_stat
  - fs/pipe.c:SyS_pipe
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:SyS_fcntl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/readdir.c:filldir
  - fs/readdir.c:filldir64
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/dcache.c:SyS_getcwd
  - fs/filesystems.c:SyS_sysfs
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/statfs.c:do_statfs_native
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:SYSC_ustat
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/timerfd.c:SyS_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_gettime
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/aio.c:aio_read_events
  - fs/locks.c:fcntl_getlk
  - fs/compat.c:cp_compat_stat
  - fs/compat.c:compat_filldir
  - fs/compat.c:compat_filldir64
  - fs/compat.c:C_SYSC_ustat
  - fs/compat.c:poll_select_copy_remaining
  - fs/compat.c:compat_SyS_io_getevents
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/quota/quota.c:quota_getinfo
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:SyS_quotactl
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:read_vmcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:compat_SyS_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/sem.c:semctl_main
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_open
  - ipc/compat_mq.c:compat_SyS_mq_notify
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_read
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - lib/seq_buf.c:seq_buf_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:extract_entropy_user
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev.c:tpm_read
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status_old
  - drivers/block/loop.c:loop_get_status64
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:move_addr_to_user
  - net/socket.c:SyS_socketcall
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_get_timestampns
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/filter.c:sk_get_filter
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff813f5fc0-ffffffff813f5fea: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mcheck/mce.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_dostring
  - kernel/capability.c:SyS_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:compat_SyS_rt_sigpending
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - kernel/sys.c:SYSC_sysinfo
  - kernel/sys.c:SyS_prctl
  - kernel/sys.c:getrusage
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_old_getrlimit
  - kernel/sys.c:SyS_getrlimit
  - kernel/sys.c:SyS_gethostname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_newuname
  - kernel/sys.c:SyS_newuname
  - kernel/sys.c:SyS_times
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:SYSC_adjtimex
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/time/hrtimer.c:update_rmtp
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/time/itimer.c:SyS_getitimer
  - kernel/time/posix-timers.c:SyS_clock_getres
  - kernel/time/posix-timers.c:SYSC_clock_adjtime
  - kernel/time/posix-timers.c:SyS_clock_gettime
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_gettime
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/time/alarmtimer.c:update_rmtp
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_timer_create
  - kernel/compat.c:C_SYSC_waitid
  - kernel/compat.c:compat_SyS_times
  - kernel/compat.c:compat_convert_timespec
  - kernel/compat.c:compat_put_timespec
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_SyS_gettimeofday
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/relay.c:subbuf_read_actor
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/backing-dev.c:pdflush_proc_obsolete
  - mm/mincore.c:SyS_mincore
  - mm/mempolicy.c:compat_SyS_mbind
  - mm/mempolicy.c:compat_SyS_set_mempolicy
  - mm/mempolicy.c:copy_nodes_to_user
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_llseek
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:SyS_pipe
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:SyS_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/dcache.c:SyS_getcwd
  - fs/filesystems.c:SyS_sysfs
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/statfs.c:SYSC_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/timerfd.c:SyS_timerfd_gettime
  - fs/timerfd.c:SyS_timerfd_settime
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events
  - fs/locks.c:fcntl_getlk
  - fs/compat.c:poll_select_copy_remaining
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir
  - fs/compat.c:compat_SyS_io_getevents
  - fs/compat.c:C_SYSC_ustat
  - fs/compat.c:cp_compat_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/quota/quota.c:SyS_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:compat_SyS_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/sem.c:semctl_main
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_notify
  - ipc/compat_mq.c:compat_SyS_mq_open
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_read
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - lib/seq_buf.c:seq_buf_to_user
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev.c:tpm_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:SyS_socketcall
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_tunable
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/filter.c:sk_get_filter
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff8143cb20-ffffffff8143cb47: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff8145b6d0)
Location: arch/x86/lib/usercopy.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mcheck/mce.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_dostring
  - kernel/capability.c:SyS_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:compat_SyS_rt_sigpending
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - kernel/sys.c:SYSC_sysinfo
  - kernel/sys.c:SyS_prctl
  - kernel/sys.c:getrusage
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_old_getrlimit
  - kernel/sys.c:SyS_getrlimit
  - kernel/sys.c:SyS_gethostname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_newuname
  - kernel/sys.c:SyS_newuname
  - kernel/sys.c:SyS_times
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/printk/printk.c:do_syslog
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:SYSC_adjtimex
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/time/hrtimer.c:update_rmtp
  - kernel/time/alarmtimer.c:update_rmtp
  - kernel/time/posix-timers.c:SyS_clock_getres
  - kernel/time/posix-timers.c:SYSC_clock_adjtime
  - kernel/time/posix-timers.c:SyS_clock_gettime
  - kernel/time/posix-timers.c:SyS_timer_settime
  - kernel/time/posix-timers.c:SyS_timer_gettime
  - kernel/time/posix-timers.c:SyS_timer_create
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep_restart
  - kernel/time/posix-cpu-timers.c:posix_cpu_nsleep
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/time/itimer.c:SyS_getitimer
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:compat_SyS_timer_create
  - kernel/compat.c:C_SYSC_waitid
  - kernel/compat.c:compat_SyS_times
  - kernel/compat.c:compat_convert_timespec
  - kernel/compat.c:compat_put_timespec
  - kernel/compat.c:compat_put_timeval
  - kernel/compat.c:compat_SyS_gettimeofday
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/backing-dev.c:pdflush_proc_obsolete
  - mm/mincore.c:SyS_mincore
  - mm/mempolicy.c:C_SYSC_mbind
  - mm/mempolicy.c:C_SYSC_set_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_llseek
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:SyS_pipe
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:SyS_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/dcache.c:SyS_getcwd
  - fs/filesystems.c:SyS_sysfs
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:SyS_splice
  - fs/statfs.c:SYSC_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/timerfd.c:SyS_timerfd_gettime
  - fs/timerfd.c:SyS_timerfd_settime
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:compat_SyS_io_getevents
  - fs/aio.c:aio_read_events
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/locks.c:fcntl_getlk
  - fs/compat.c:poll_select_copy_remaining
  - fs/compat.c:compat_filldir64
  - fs/compat.c:compat_filldir
  - fs/compat.c:C_SYSC_ustat
  - fs/compat.c:cp_compat_stat
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/quota/quota.c:SyS_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:compat_SyS_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/sem.c:semctl_main
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_notify
  - ipc/compat_mq.c:compat_SyS_mq_open
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/dh.c:keyctl_dh_compute
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_read
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/seq_buf.c:seq_buf_to_user
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev.c:tpm_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:SyS_socketcall
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_stats
  - net/core/ethtool.c:ethtool_get_stats
  - net/core/ethtool.c:ethtool_self_test
  - net/core/ethtool.c:ethtool_self_test
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/filter.c:sk_get_filter
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/rfkill/core.c:rfkill_fop_read
```
**Symbols:**

```
ffffffff8145b6d0-ffffffff8145b72e: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff8146c620)
Location: lib/usercopy.c:22
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:sys_modify_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:SYSC_wait4
  - kernel/exit.c:SYSC_waitid
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_dostring
  - kernel/capability.c:SyS_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:compat_SyS_sigpending
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:SyS_sigaltstack
  - kernel/signal.c:compat_SyS_rt_sigpending
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - kernel/sys.c:SYSC_sysinfo
  - kernel/sys.c:SyS_prctl
  - kernel/sys.c:SYSC_getrusage
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_old_getrlimit
  - kernel/sys.c:compat_SyS_getrlimit
  - kernel/sys.c:SyS_getrlimit
  - kernel/sys.c:SyS_gethostname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_newuname
  - kernel/sys.c:SyS_newuname
  - kernel/sys.c:compat_SyS_times
  - kernel/sys.c:SyS_times
  - kernel/sched/core.c:SyS_sched_rr_get_interval
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:SYSC_adjtimex
  - kernel/time/time.c:compat_SyS_gettimeofday
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/time/posix-timers.c:SYSC_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/time/itimer.c:SyS_getitimer
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:put_compat_itimerspec64
  - kernel/compat.c:put_compat_itimerspec64
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_itimerval
  - kernel/compat.c:compat_convert_timespec
  - kernel/compat.c:compat_put_timex
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/backing-dev.c:pdflush_proc_obsolete
  - mm/mincore.c:SyS_mincore
  - mm/mempolicy.c:C_SYSC_mbind
  - mm/mempolicy.c:C_SYSC_set_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:SyS_pipe
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:put_compat_flock64
  - fs/fcntl.c:put_compat_flock
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/select.c:compat_poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/dcache.c:SyS_getcwd
  - fs/filesystems.c:SyS_sysfs
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/statfs.c:C_SYSC_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:SYSC_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:compat_SyS_io_getevents
  - fs/aio.c:aio_read_events
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/compat_ioctl.c:do_ioctl_trans
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/quota/quota.c:SyS_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:compat_SyS_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
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
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/compat.c:C_SYSC_shmctl
  - ipc/compat.c:C_SYSC_msgctl
  - ipc/compat.c:do_compat_semctl
  - ipc/compat.c:do_compat_semctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/sem.c:semctl_main
  - ipc/mqueue.c:C_SYSC_mq_getsetattr
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/security.c:security_task_prctl
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_read
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
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
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:SyS_socketcall
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/filter.c:sk_get_filter
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ifname
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
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffffffff8146c620-ffffffff8146c651: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff81498940)
Location: lib/usercopy.c:23
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:SyS_modify_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:C_SYSC_waitid
  - kernel/exit.c:SYSC_wait4
  - kernel/exit.c:SYSC_waitid
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_dostring
  - kernel/capability.c:SyS_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:SyS_rt_sigaction
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:SyS_sigpending
  - kernel/signal.c:SyS_sigaltstack
  - kernel/signal.c:SyS_rt_sigprocmask
  - kernel/sys.c:SYSC_sysinfo
  - kernel/sys.c:SyS_prctl
  - kernel/sys.c:SYSC_getrusage
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_old_getrlimit
  - kernel/sys.c:compat_SyS_getrlimit
  - kernel/sys.c:SyS_getrlimit
  - kernel/sys.c:SyS_gethostname
  - kernel/sys.c:SYSC_olduname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_uname
  - kernel/sys.c:SyS_newuname
  - kernel/sys.c:SyS_newuname
  - kernel/sys.c:compat_SyS_times
  - kernel/sys.c:SyS_times
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/sched/core.c:SyS_sched_getattr
  - kernel/sched/core.c:SyS_sched_getparam
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:SYSC_adjtimex
  - kernel/time/time.c:compat_SyS_gettimeofday
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/time/time.c:SyS_gettimeofday
  - kernel/time/posix-timers.c:SYSC_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:SyS_setitimer
  - kernel/time/itimer.c:SyS_getitimer
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:put_compat_sigset
  - kernel/compat.c:put_compat_itimerspec64
  - kernel/compat.c:put_compat_itimerspec64
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_itimerval
  - kernel/compat.c:compat_put_timex
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:SyS_mincore
  - mm/mempolicy.c:C_SYSC_mbind
  - mm/mempolicy.c:C_SYSC_set_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_copy_file_range
  - fs/read_write.c:SyS_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:SyS_pipe
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:put_compat_flock64
  - fs/fcntl.c:put_compat_flock
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/select.c:compat_poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/dcache.c:SyS_getcwd
  - fs/filesystems.c:SyS_sysfs
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:SyS_splice
  - fs/splice.c:SyS_splice
  - fs/statfs.c:C_SYSC_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:SYSC_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/fhandle.c:SyS_name_to_handle_at
  - fs/quota/quota.c:SyS_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:compat_SyS_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
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
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:C_SYSC_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:SYSC_msgctl
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:C_SYSC_shmctl
  - ipc/shm.c:C_SYSC_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:SYSC_shmctl
  - ipc/mqueue.c:C_SYSC_mq_getsetattr
  - ipc/mqueue.c:SYSC_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/security.c:security_task_prctl
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_read
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
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
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_ifr_data_ioctl
  - net/socket.c:SyS_socketcall
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/filter.c:sk_get_filter
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ifname
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
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffffffff81498940-ffffffff8149896d: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff814cdb90)
Location: lib/usercopy.c:23
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/crash_dump_64.c:copy_oldmem_page
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_dostring
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_read_attr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_itimerval
  - kernel/compat.c:compat_put_timex
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/select.c:compat_poll_select_copy_remaining
  - fs/select.c:poll_select_copy_remaining
  - fs/filesystems.c:fs_name
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:do_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
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
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:ksys_msgctl
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:ksys_shmctl
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_read
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg-lib.c:bsg_transport_complete_rq
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
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
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
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
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffffffff814cdb90-ffffffff814cdbc2: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff814e2460)
Location: lib/usercopy.c:23
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_dostring
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_read_attr
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_itimerval
  - kernel/compat.c:compat_put_timex
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/select.c:poll_select_copy_remaining
  - fs/filesystems.c:fs_name
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:do_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
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
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:ksys_msgctl
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:ksys_shmctl
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg-lib.c:bsg_transport_complete_rq
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
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
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_get_timestampns
  - net/core/sock.c:sock_get_timestamp
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
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
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffffffff814e2460-ffffffff814e2492: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff8150e320)
Location: lib/usercopy.c:23
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_dostring
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_itimerval
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_uring_setup
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:do_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
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
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg-lib.c:bsg_transport_complete_rq
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/filter.c:sk_get_filter
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffffffff8150e320-ffffffff8150e350: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff8152c170)
Location: lib/usercopy.c:24
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_dostring
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_itimerval
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/readdir.c:compat_filldir
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_uring_setup
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:do_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
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
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg-lib.c:bsg_transport_complete_rq
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_rw
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_link_ksettings
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
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffffffff8152c170-ffffffff8152c1a0: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff8158fb40)
Location: lib/usercopy.c:25
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:x32_copy_siginfo_to_user
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/compat.c:put_compat_rusage
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_raw_tp_link_fill_link_info
  - kernel/bpf/syscall.c:bpf_raw_tp_link_fill_link_info
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read_group
  - mm/mincore.c:__do_sys_mincore
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:copy_nodes_to_user
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown_ex
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:ioctl_file_dedupe_range
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/d_path.c:__do_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events_ring
  - fs/io_uring.c:io_uring_create
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
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
  - fs/fhandle.c:do_sys_name_to_handle
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:do_proc_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_file_direct_read
  - fs/dcookies.c:do_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
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
  - fs/fat/file.c:fat_ioctl_fitrim
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_put_cdrom_generic_arg
  - block/scsi_ioctl.c:put_sg_io_hdr
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:blk_complete_sghdr_rq
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg-lib.c:bsg_transport_complete_rq
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_copy_zone_to_user
  - block/sed-opal.c:read_table_data
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/seq_buf.c:seq_buf_to_user
  - drivers/gpio/gpiolib.c:lineinfo_watch_read
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:lineevent_read
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/acpi/acpi_dbg.c:acpi_aml_read_user
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:tty_copy_to_user
  - drivers/tty/n_tty.c:tty_copy_to_user
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:extract_crng_user
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_common
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_get_pci
  - drivers/scsi/scsi_ioctl.c:ioctl_probe
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_get_identity
  - drivers/ata/libata-scsi.c:ata_get_identity
  - drivers/ata/libata-scsi.c:ata_get_identity
  - drivers/ata/libata-scsi.c:ata_get_identity
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_do_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_rw
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_ioctl_volread
  - drivers/cdrom/cdrom.c:cdrom_ioctl_get_subchnl
  - drivers/cdrom/cdrom.c:cdrom_ioctl_get_mcn
  - drivers/cdrom/cdrom.c:cdrom_ioctl_multisession
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_str_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:get_disk_info
  - drivers/md/md.c:get_bitmap_file
  - drivers/md/md.c:get_array_info
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/filter.c:sk_get_filter
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_tunable
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_perm_addr
  - net/ethtool/ioctl.c:ethtool_get_perm_addr
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_get_channels
  - net/ethtool/ioctl.c:ethtool_get_coalesce
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_get_regs
  - net/ethtool/ioctl.c:ethtool_get_regs
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_set_rxnfc
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ethtool/ioctl.c:ethtool_get_features
  - net/ethtool/ioctl.c:ethtool_get_features
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-priv.c:ioctl_private_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
```
**Symbols:**

```
ffffffff8158fb40-ffffffff8158fb6e: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff815ac680)
Location: lib/usercopy.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:x32_copy_siginfo_to_user
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/regset.c:copy_regset_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/compat.c:put_compat_rusage
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_raw_tp_link_fill_link_info
  - kernel/bpf/syscall.c:bpf_raw_tp_link_fill_link_info
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/bpf_iter.c:bpf_iter_link_fill_link_info
  - kernel/bpf/bpf_iter.c:bpf_iter_link_fill_link_info
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read_group
  - mm/mincore.c:__do_sys_mincore
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:copy_nodes_to_user
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_getown_ex
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:ioctl_file_dedupe_range
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/d_path.c:__do_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events_ring
  - fs/io_uring.c:io_uring_create
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
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
  - fs/fhandle.c:do_sys_name_to_handle
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:compat_copy_fs_qfilestat
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:do_proc_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/dcookies.c:do_lookup_dcookie
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/file.c:fat_ioctl_fitrim
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_put_cdrom_generic_arg
  - block/scsi_ioctl.c:put_sg_io_hdr
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:blk_complete_sghdr_rq
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg-lib.c:bsg_transport_complete_rq
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_copy_zone_to_user
  - block/sed-opal.c:read_table_data
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/seq_buf.c:seq_buf_to_user
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_read
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/acpi/acpi_dbg.c:acpi_aml_read_user
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_io_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:extract_crng_user
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_merge
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl_create_fence
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_common
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_get_pci
  - drivers/scsi/scsi_ioctl.c:ioctl_probe
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:put_compat_request_table
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_get_identity
  - drivers/ata/libata-scsi.c:ata_get_identity
  - drivers/ata/libata-scsi.c:ata_get_identity
  - drivers/ata/libata-scsi.c:ata_get_identity
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_do_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_rw
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_ioctl_volread
  - drivers/cdrom/cdrom.c:cdrom_ioctl_get_subchnl
  - drivers/cdrom/cdrom.c:cdrom_ioctl_get_mcn
  - drivers/cdrom/cdrom.c:cdrom_ioctl_multisession
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_str_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:get_disk_info
  - drivers/md/md.c:get_bitmap_file
  - drivers/md/md.c:get_array_info
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/remoteproc/remoteproc_cdev.c:rproc_device_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/filter.c:sk_get_filter
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:get_phy_tunable
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_tunable
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_perm_addr
  - net/ethtool/ioctl.c:ethtool_get_perm_addr
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_get_channels
  - net/ethtool/ioctl.c:ethtool_get_coalesce
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_get_regs
  - net/ethtool/ioctl.c:ethtool_get_regs
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_set_rxnfc
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ethtool/ioctl.c:ethtool_get_features
  - net/ethtool/ioctl.c:ethtool_get_features
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/raw.c:rawv6_getsockopt
  - net/ipv6/raw.c:rawv6_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-priv.c:ioctl_private_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
```
**Symbols:**

```
ffffffff815ac680-ffffffff815ac6c5: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff815b7330)
Location: lib/usercopy.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:x32_copy_siginfo_to_user
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/regset.c:copy_regset_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/compat.c:put_compat_rusage
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_raw_tp_link_fill_link_info
  - kernel/bpf/syscall.c:bpf_raw_tp_link_fill_link_info
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/bpf_iter.c:bpf_iter_link_fill_link_info
  - kernel/bpf/bpf_iter.c:bpf_iter_link_fill_link_info
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:__do_sys_mincore
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:copy_fsxattr_to_user
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/d_path.c:__do_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events_ring
  - fs/io_uring.c:io_uring_create
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
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
  - fs/fhandle.c:do_sys_name_to_handle
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
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
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - block/scsi_ioctl.c:put_sg_io_hdr
  - block/scsi_ioctl.c:put_sg_io_hdr
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg-lib.c:bsg_transport_complete_rq
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_copy_zone_to_user
  - block/sed-opal.c:read_table_data
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/seq_buf.c:seq_buf_to_user
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_read
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:extract_crng_user
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_common
  - drivers/scsi/scsi_ioctl.c:ioctl_probe
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_do_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_rw
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_str_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:get_array_info
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/remoteproc/remoteproc_cdev.c:rproc_device_ioctl
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:sk_get_filter
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:get_phy_tunable
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_tunable
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_get_channels
  - net/ethtool/ioctl.c:ethtool_get_coalesce
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_set_rxnfc
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/raw.c:rawv6_getsockopt
  - net/ipv6/raw.c:rawv6_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-priv.c:ioctl_private_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
```
**Symbols:**

```
ffffffff815b7330-ffffffff815b7358: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff8161d960)
Location: lib/usercopy.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:x32_copy_siginfo_to_user
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__x64_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__x64_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__x64_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__x64_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__x64_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/regset.c:copy_regset_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__x64_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__x64_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__x64_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/compat.c:put_compat_rusage
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_raw_tp_link_fill_link_info
  - kernel/bpf/syscall.c:bpf_raw_tp_link_fill_link_info
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/bpf_iter.c:bpf_iter_link_fill_link_info
  - kernel/bpf/bpf_iter.c:bpf_iter_link_fill_link_info
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:__do_sys_mincore
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:copy_fsxattr_to_user
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/d_path.c:__do_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events_ring
  - fs/io_uring.c:io_register_iowq_max_workers
  - fs/io_uring.c:io_register_iowq_max_workers
  - fs/io_uring.c:io_uring_create
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
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
  - fs/fhandle.c:do_sys_name_to_handle
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
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
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_copy_zone_to_user
  - block/sed-opal.c:read_table_data
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/seq_buf.c:seq_buf_to_user
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:gpio_ioctl
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_read
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:read_mem
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:put_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:put_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_ioctl.c:ioctl_probe
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_siocdevprivate
  - drivers/net/ppp/ppp_generic.c:ppp_net_siocdevprivate
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_at_ioctl
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_at_ioctl
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_do_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_rw
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:get_array_info
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/remoteproc/remoteproc_cdev.c:rproc_device_ioctl
  - net/socket.c:put_user_ifreq
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:sk_get_filter
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:get_phy_tunable
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_tunable
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_get_channels
  - net/ethtool/ioctl.c:ethtool_get_coalesce
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_get_regs
  - net/ethtool/ioctl.c:ethtool_get_regs
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_to_user
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_to_user
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/raw.c:rawv6_getsockopt
  - net/ipv6/raw.c:rawv6_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-priv.c:ioctl_private_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
```
**Symbols:**

```
ffffffff8161d960-ffffffff8161d988: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff816eb3a0)
Location: lib/usercopy.c:26
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_get_report
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:override_release
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/regset.c:copy_regset_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
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
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/compat.c:put_compat_rusage
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_raw_tp_link_fill_link_info
  - kernel/bpf/syscall.c:bpf_raw_tp_link_fill_link_info
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:check_core_relo
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/bpf_iter.c:bpf_iter_link_fill_link_info
  - kernel/bpf/bpf_iter.c:bpf_iter_link_fill_link_info
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:__do_sys_mincore
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:copy_fsxattr_to_user
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/xattr.c:listxattr
  - fs/xattr.c:do_getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/d_path.c:__do_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events_ring
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/read_metadata.c:fsverity_read_buffer
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/fhandle.c:do_sys_name_to_handle
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/file.c:fat_generic_ioctl
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_capabilities
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_copy_zone_to_user
  - block/sed-opal.c:read_table_data
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:io_ringfd_register
  - io_uring/io_uring.c:io_files_update
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/seq_buf.c:seq_buf_to_user
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_ioctl
  - drivers/gpio/gpiolib-cdev.c:lineevent_read
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_read
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
  - drivers/pci/vgaarb.c:vga_arb_read
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_rs485_config
  - drivers/char/mem.c:read_mem
  - drivers/char/virtio_console.c:fill_readbuf
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:put_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:put_sg_io_hdr
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_ioctl.c:ioctl_probe
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_siocdevprivate
  - drivers/net/ppp/ppp_generic.c:ppp_net_siocdevprivate
  - drivers/net/ppp/ppp_generic.c:ppp_net_siocdevprivate
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_at_ioctl
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_at_ioctl
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/vfio/vfio.c:vfio_device_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_ioctl_device_feature_mig_device_state
  - drivers/vfio/vfio.c:vfio_ioctl_device_feature_mig_device_state
  - drivers/vfio/vfio.c:vfio_ioctl_device_feature_mig_device_state
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dma_rw_chunk
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
  - drivers/vfio/vfio_iommu_type1.c:update_user_bitmap
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_do_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_rw
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:get_bitmap_file
  - drivers/md/md.c:get_array_info
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/remoteproc/remoteproc_cdev.c:rproc_device_ioctl
  - net/socket.c:put_user_ifreq
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/filter.c:sk_get_filter
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:get_phy_tunable
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_get_strings
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_get_channels
  - net/ethtool/ioctl.c:ethtool_get_coalesce
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_to_user
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_to_user
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/raw.c:rawv6_getsockopt
  - net/ipv6/raw.c:rawv6_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-priv.c:ioctl_private_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_put_subflow_data
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_getsockopt
```
**Symbols:**

```
ffffffff816eb3a0-ffffffff816eb3fa: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff817dba60)
Location: lib/usercopy.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:override_release
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/regset.c:copy_regset_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
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
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/compat.c:put_compat_rusage
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_raw_tp_link_fill_link_info
  - kernel/bpf/syscall.c:bpf_raw_tp_link_fill_link_info
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/bpf_iter.c:bpf_iter_link_fill_link_info
  - kernel/bpf/bpf_iter.c:bpf_iter_link_fill_link_info
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:__do_sys_mincore
  - mm/mempolicy.c:copy_nodes_to_user
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:copy_fsxattr_to_user
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/xattr.c:listxattr
  - fs/xattr.c:do_getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/d_path.c:__do_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events_ring
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/read_metadata.c:fsverity_read_buffer
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/fhandle.c:do_sys_name_to_handle
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/file.c:fat_generic_ioctl
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_capabilities
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/notify.c:build_unotif
  - security/apparmor/notify.c:build_unotif
  - security/apparmor/notify.c:build_unotif
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_copy_zone_to_user
  - block/sed-opal.c:sed_ioctl
  - block/sed-opal.c:read_table_data
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_uring_create
  - io_uring/net.c:io_recvmsg
  - io_uring/tctx.c:io_ringfd_register
  - io_uring/rsrc.c:io_files_update
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_ioctl_unlocked
  - drivers/gpio/gpiolib-cdev.c:lineevent_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
  - drivers/pci/vgaarb.c:vga_arb_read
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termios_1
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termios
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_rs485_config
  - drivers/char/mem.c:read_mem
  - drivers/char/virtio_console.c:fill_readbuf
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_ioctl.c:ioctl_probe
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_siocdevprivate
  - drivers/net/ppp/ppp_generic.c:ppp_net_siocdevprivate
  - drivers/net/ppp/ppp_generic.c:ppp_net_siocdevprivate
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_at_ioctl
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_at_ioctl
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:get_disk_info
  - drivers/md/md.c:get_bitmap_file
  - drivers/md/md.c:get_array_info
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/remoteproc/remoteproc_cdev.c:rproc_device_ioctl
  - net/socket.c:put_user_ifreq
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/filter.c:sk_get_filter
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:get_phy_tunable
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_get_channels
  - net/ethtool/ioctl.c:ethtool_get_coalesce
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_to_user
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_to_user
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/raw.c:rawv6_getsockopt
  - net/ipv6/raw.c:rawv6_getsockopt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-priv.c:ioctl_private_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_put_subflow_data
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_getsockopt
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffffffff817dba60-ffffffff817dbaba: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff8181ae00)
Location: lib/usercopy.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__do_sys_gethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:override_release
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/regset.c:copy_regset_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch_get_config
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timespec32
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/compat.c:put_compat_rusage
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_raw_tp_link_fill_link_info
  - kernel/bpf/syscall.c:bpf_raw_tp_link_fill_link_info
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/log.c:bpf_vlog_reverse_ubuf
  - kernel/bpf/log.c:bpf_vlog_reverse_ubuf
  - kernel/bpf/log.c:bpf_verifier_vlog
  - kernel/bpf/log.c:bpf_verifier_vlog
  - kernel/bpf/log.c:bpf_verifier_vlog
  - kernel/bpf/log.c:bpf_verifier_vlog
  - kernel/bpf/bpf_iter.c:bpf_iter_link_fill_link_info
  - kernel/bpf/bpf_iter.c:bpf_iter_link_fill_link_info
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mempolicy.c:copy_nodes_to_user
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:copy_fsxattr_to_user
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/xattr.c:listxattr
  - fs/xattr.c:do_getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/d_path.c:__do_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events_ring
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/read_metadata.c:fsverity_read_buffer
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/fhandle.c:do_sys_name_to_handle
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/file.c:fat_generic_ioctl
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_capabilities
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/notify.c:build_v3_unotif
  - security/apparmor/notify.c:append_str
  - crypto/jitterentropy-testing.c:jent_raw_hires_read
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_copy_zone_to_user
  - block/sed-opal.c:sed_ioctl
  - block/sed-opal.c:sed_ioctl
  - block/sed-opal.c:sed_ioctl
  - block/sed-opal.c:read_table_data
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_uring_create
  - io_uring/net.c:io_recvmsg
  - io_uring/tctx.c:io_ringfd_register
  - io_uring/rsrc.c:io_files_update
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_ioctl_unlocked
  - drivers/gpio/gpiolib-cdev.c:lineevent_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_read_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked
  - drivers/pci/vgaarb.c:vga_arb_read
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fb_io_fops.c:fb_io_read
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fb_sys_fops.c:fb_sys_read
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termios_1
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termios
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_rs485_config
  - drivers/char/mem.c:read_mem
  - drivers/char/virtio_console.c:fill_readbuf
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_ioctl.c:ioctl_probe
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_siocdevprivate
  - drivers/net/ppp/ppp_generic.c:ppp_net_siocdevprivate
  - drivers/net/ppp/ppp_generic.c:ppp_net_siocdevprivate
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_at_ioctl
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_at_ioctl
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_read
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:get_disk_info
  - drivers/md/md.c:get_bitmap_file
  - drivers/md/md.c:get_array_info
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/remoteproc/remoteproc_cdev.c:rproc_device_ioctl
  - net/socket.c:put_user_ifreq
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_ioctl_inout
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/filter.c:sk_get_filter
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:get_phy_tunable
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_tunable
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_get_channels
  - net/ethtool/ioctl.c:ethtool_get_coalesce
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_to_user
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_to_user
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/raw.c:rawv6_getsockopt
  - net/ipv6/raw.c:rawv6_getsockopt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-priv.c:ioctl_private_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_put_subflow_data
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_getsockopt
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffffffff8181ae00-ffffffff8181ae61: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff81860170)
Location: lib/usercopy.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:__ia32_sys_get_thread_area
  - arch/x86/kernel/tls.c:__x64_sys_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/capability.c:__do_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__do_sys_gethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:override_release
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/regset.c:copy_regset_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch_get_config
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timespec32
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/compat.c:put_compat_rusage
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:do_seccomp
  - kernel/seccomp.c:seccomp_notify_recv
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_fill_link_info
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_fill_link_info
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_copy_to_user
  - kernel/bpf/syscall.c:bpf_copy_to_user
  - kernel/bpf/syscall.c:map_lookup_and_delete_elem
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_lookup_batch
  - kernel/bpf/syscall.c:generic_map_update_batch
  - kernel/bpf/syscall.c:generic_map_delete_batch
  - kernel/bpf/syscall.c:map_get_next_key
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/log.c:bpf_vlog_reverse_ubuf
  - kernel/bpf/log.c:bpf_vlog_reverse_ubuf
  - kernel/bpf/log.c:bpf_verifier_vlog
  - kernel/bpf/log.c:bpf_verifier_vlog
  - kernel/bpf/log.c:bpf_verifier_vlog
  - kernel/bpf/log.c:bpf_verifier_vlog
  - kernel/bpf/bpf_iter.c:bpf_iter_link_fill_link_info
  - kernel/bpf/bpf_iter.c:bpf_iter_link_fill_link_info
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/bpf_iter.c:bpf_seq_read
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/mprog.c:bpf_mprog_query
  - kernel/bpf/mprog.c:bpf_mprog_query
  - kernel/bpf/mprog.c:bpf_mprog_query
  - kernel/bpf/mprog.c:bpf_mprog_query
  - kernel/bpf/mprog.c:bpf_mprog_query
  - kernel/bpf/mprog.c:bpf_mprog_query
  - kernel/bpf/mprog.c:bpf_mprog_query
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/net_namespace.c:netns_bpf_prog_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mempolicy.c:copy_nodes_to_user
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__do_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:copy_fsxattr_to_user
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/namespace.c:__do_sys_statmount
  - fs/namespace.c:__do_sys_statmount
  - fs/xattr.c:listxattr
  - fs/xattr.c:do_getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:__do_splice
  - fs/splice.c:__do_splice
  - fs/d_path.c:__do_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/inotify/inotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events_ring
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_nonce
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/read_metadata.c:fsverity_read_buffer
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/fhandle.c:do_sys_name_to_handle
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_ioctl_getuuid
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/crypto.c:ext4_ioctl_get_encryption_pwsalt
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/file.c:fat_generic_ioctl
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_capabilities
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/security.c:lsm_fill_user_ctx
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/notify.c:build_v3_unotif
  - security/apparmor/notify.c:append_str
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_copy_zone_to_user
  - block/sed-opal.c:sed_ioctl
  - block/sed-opal.c:sed_ioctl
  - block/sed-opal.c:sed_ioctl
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:opal_discovery0_end
  - io_uring/io_uring.c:io_uring_create
  - io_uring/net.c:io_recvmsg
  - io_uring/tctx.c:io_ringfd_register
  - io_uring/kbuf.c:io_register_pbuf_status
  - io_uring/rsrc.c:io_files_update
  - io_uring/register.c:io_register_iowq_max_workers
  - io_uring/register.c:io_register_iowq_max_workers
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineinfo_get_v1
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:lineevent_ioctl
  - drivers/gpio/gpiolib-cdev.c:lineevent_read
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linereq_read
  - drivers/gpio/gpiolib-cdev.c:linereq_get_values
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_ioctl
  - drivers/pci/vgaarb.c:vga_arb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
  - drivers/video/fbdev/core/fb_chrdev.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/core/fb_io_fops.c:fb_io_read
  - drivers/video/fbdev/core/fb_sys_fops.c:fb_sys_read
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termios_1
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termios
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_get
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_rs485_config
  - drivers/char/mem.c:read_mem
  - drivers/char/virtio_console.c:fill_readbuf
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/dma-buf.c:dma_buf_export_sync_file
  - drivers/dma-buf/dma-heap.c:dma_heap_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_ioctl.c:ioctl_probe
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_read_oxfer
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_get_ioctl
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_get_ioctl
  - drivers/gpu/drm/drm_color_mgmt.c:drm_mode_gamma_get_ioctl
  - drivers/gpu/drm/drm_connector.c:drm_mode_getconnector
  - drivers/gpu/drm/drm_file.c:drm_read
  - drivers/gpu/drm/drm_ioctl.c:drm_ioctl
  - drivers/gpu/drm/drm_ioctl.c:drm_copy_field
  - drivers/gpu/drm/drm_ioctl.c:drm_getunique
  - drivers/gpu/drm/drm_plane.c:drm_mode_getplane
  - drivers/gpu/drm/drm_property.c:drm_mode_getblob_ioctl
  - drivers/gpu/drm/drm_property.c:drm_mode_getproperty_ioctl
  - drivers/gpu/drm/drm_property.c:drm_mode_getproperty_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_ioc32.c:compat_drm_wait_vblank
  - drivers/gpu/drm/drm_ioc32.c:compat_drm_getclient
  - drivers/gpu/drm/drm_ioc32.c:compat_drm_getunique
  - drivers/gpu/drm/drm_ioc32.c:compat_drm_version
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_read
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_siocdevprivate
  - drivers/net/ppp/ppp_generic.c:ppp_net_siocdevprivate
  - drivers/net/ppp/ppp_generic.c:ppp_net_siocdevprivate
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_ioctl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:do_proc_bulk
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:get_disk_info
  - drivers/md/md.c:get_bitmap_file
  - drivers/md/md.c:get_array_info
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/remoteproc/remoteproc_cdev.c:rproc_device_ioctl
  - net/socket.c:put_user_ifreq
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_ioctl_inout
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/sock.c:sk_getsockopt
  - net/core/filter.c:sk_get_filter
  - net/core/dev_ioctl.c:dev_ifsioc
  - net/core/dev_ioctl.c:dev_set_hwtstamp
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/core/sock_map.c:sock_map_bpf_prog_query
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
  - net/bpf/test_run.c:bpf_prog_test_run_raw_tp
  - net/bpf/test_run.c:bpf_prog_test_run_tracing
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:get_phy_tunable
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_dump_data
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_phy_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_get_stats
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_self_test
  - net/ethtool/ioctl.c:ethtool_get_channels
  - net/ethtool/ioctl.c:ethtool_get_coalesce
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
  - net/ethtool/ioctl.c:ethtool_set_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_get_rxfh_indir
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_to_user
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_to_user
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_sset_info
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_link_ksettings
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:compat_ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/ip_sockglue.c:ip_get_mcast_msfilter
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv4/tcp_ao.c:tcp_ao_get_repair
  - net/ipv4/tcp_ao.c:tcp_ao_get_sock_info
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:compat_ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/ipv6_sockglue.c:ipv6_get_msfilter
  - net/ipv6/raw.c:rawv6_getsockopt
  - net/ipv6/raw.c:rawv6_getsockopt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-priv.c:ioctl_private_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
  - net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo
  - net/mptcp/sockopt.c:mptcp_put_subflow_data
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_getsockopt
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffffffff81860170-ffffffff818601b9: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm64/kernel/ptrace.c (ffff80001008abc0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - arch/arm64/kernel/ptrace.c:compat_gpr_get
```
```
In arch/arm64/kernel/signal32.c (ffff8000100a05b4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
  - arch/arm64/kernel/signal32.c:compat_setup_sigframe
```
```
In arch/arm64/kernel/crash_dump.c (ffff8000100ab8f0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - arch/arm64/kernel/crash_dump.c:copy_oldmem_page
```
```
In virt/kvm/kvm_main.c (ffff8000100baef0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_get_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_get_dirty_log_protect
  - virt/kvm/kvm_main.c:kvm_get_dirty_log
  - virt/kvm/kvm_main.c:kvm_get_dirty_log
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/kvm_main.c:kvm_vm_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
```
```
In virt/kvm/arm/arm.c (ffff8000100c32d8)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - virt/kvm/arm/arm.c:kvm_arch_vm_ioctl
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl
  - virt/kvm/arm/arm.c:kvm_arch_vcpu_ioctl
```
```
In virt/kvm/arm/psci.c (ffff8000100ceb3c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - virt/kvm/arm/psci.c:kvm_arm_get_fw_reg
```
```
In arch/arm64/kvm/guest.c (ffff8000100d2c14)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
  - arch/arm64/kvm/guest.c:kvm_arm_get_reg
```
```
In arch/arm64/kvm/sys_regs.c (ffff8000100d802c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - arch/arm64/kvm/sys_regs.c:reg_to_user
  - arch/arm64/kvm/sys_regs.c:reg_to_user
  - arch/arm64/kvm/sys_regs.c:get_wcr
  - arch/arm64/kvm/sys_regs.c:get_wcr
  - arch/arm64/kvm/sys_regs.c:get_wvr
  - arch/arm64/kvm/sys_regs.c:get_wvr
  - arch/arm64/kvm/sys_regs.c:get_bcr
  - arch/arm64/kvm/sys_regs.c:get_bcr
  - arch/arm64/kvm/sys_regs.c:get_bvr
  - arch/arm64/kvm/sys_regs.c:get_bvr
```
```
In virt/kvm/arm/vgic/vgic-kvm-device.c (ffff8000100e5898)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100e8e90)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In kernel/exit.c (ffff8000100fe09c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/sysctl.c (ffff800010102c5c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:_proc_do_string
  - kernel/sysctl.c:_proc_do_string
```
```
In kernel/capability.c (ffff8000101060f8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/capability.c:__arm64_sys_capget
```
```
In kernel/ptrace.c (ffff80001010948c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (ffff800010112ea0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__arm64_sys_rt_sigaction
  - kernel/signal.c:__arm64_sys_rt_sigaction
  - kernel/signal.c:__arm64_sys_sigprocmask
  - kernel/signal.c:__arm64_sys_sigprocmask
  - kernel/signal.c:__arm64_sys_sigpending
  - kernel/signal.c:__arm64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__arm64_sys_sigaltstack
  - kernel/signal.c:__arm64_sys_sigaltstack
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__arm64_compat_sys_rt_sigpending
  - kernel/signal.c:__arm64_compat_sys_rt_sigpending
  - kernel/signal.c:__arm64_sys_rt_sigpending
  - kernel/signal.c:__arm64_sys_rt_sigpending
  - kernel/signal.c:__arm64_compat_sys_rt_sigprocmask
  - kernel/signal.c:__arm64_compat_sys_rt_sigprocmask
  - kernel/signal.c:__arm64_sys_rt_sigprocmask
  - kernel/signal.c:__arm64_sys_rt_sigprocmask
```
```
In kernel/sys.c (ffff8000101163c8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__arm64_sys_prctl
  - kernel/sys.c:__arm64_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__arm64_sys_prlimit64
  - kernel/sys.c:__arm64_sys_prlimit64
  - kernel/sys.c:__arm64_compat_sys_getrlimit
  - kernel/sys.c:__arm64_compat_sys_getrlimit
  - kernel/sys.c:__arm64_sys_getrlimit
  - kernel/sys.c:__arm64_sys_getrlimit
  - kernel/sys.c:__arm64_sys_gethostname
  - kernel/sys.c:__arm64_sys_gethostname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__arm64_compat_sys_times
  - kernel/sys.c:__arm64_compat_sys_times
  - kernel/sys.c:__arm64_sys_times
  - kernel/sys.c:__arm64_sys_times
```
```
In kernel/sched/core.c (ffff80001013c96c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/sched/core.c:__arm64_sys_sched_getaffinity
  - kernel/sched/core.c:__arm64_sys_sched_getaffinity
  - kernel/sched/core.c:__arm64_sys_sched_getattr
  - kernel/sched/core.c:__arm64_sys_sched_getattr
  - kernel/sched/core.c:__arm64_sys_sched_getparam
  - kernel/sched/core.c:__arm64_sys_sched_getparam
```
```
In kernel/printk/printk.c (ffff8000101735b0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:syslog_print
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/profile.c (ffff800010198fc0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/time/time.c (ffff80001019b360)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timespec32
  - kernel/time/time.c:put_old_timespec32
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
  - kernel/time/time.c:__arm64_sys_gettimeofday
```
```
In kernel/time/posix-timers.c (ffff8000101acc5c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/itimer.c (ffff8000101af8c0)
Location: include/linux/uaccess.h:126
Inline: True
Direct callers:
  - kernel/time/itimer.c:__arm64_sys_setitimer
  - kernel/time/itimer.c:__arm64_sys_getitimer
```
```
In kernel/kexec.c (ffff8000101ca4e8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
```
```
In kernel/compat.c (ffff8000101ccca0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_itimerval
```
```
In kernel/seccomp.c (ffff80001020a564)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
Direct callers:
  - kernel/seccomp.c:seccomp_notify_ioctl
```
```
In kernel/relay.c (ffff80001020c318)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/trace/trace.c (ffff80001022737c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_read
```
```
In kernel/trace/blktrace.c (ffff800010236cd8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
```
```
In kernel/trace/bpf_trace.c (ffff80001024d1e8)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/bpf/core.c (ffff80001025f11c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
```
```
In kernel/bpf/syscall.c (ffff8000102623b4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/syscall.c:map_lookup_elem
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In kernel/bpf/verifier.c (ffff800010268a6c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_verifier_vlog
```
```
In kernel/bpf/btf.c (ffff800010285ce8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
```
```
In kernel/bpf/offload.c (ffff80001028ae94)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/bpf/cgroup.c (ffff80001028faac)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
```
```
In kernel/events/core.c (ffff80001029e298)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
```
In mm/mincore.c (ffff8000102fd288)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mempolicy.c (ffff800010337f6c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_mbind
  - mm/mempolicy.c:__arm64_compat_sys_mbind
  - mm/mempolicy.c:__arm64_compat_sys_set_mempolicy
  - mm/mempolicy.c:__arm64_compat_sys_set_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/migrate.c (ffff80001034ecd8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In fs/read_write.c (ffff800010383b58)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_copy_file_range
  - fs/read_write.c:__arm64_sys_llseek
  - fs/read_write.c:__arm64_sys_llseek
```
```
In fs/stat.c (ffff80001038ad7c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat
Direct callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat
```
```
In fs/pipe.c (ffff8000103914a4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
```
```
In fs/namei.c (ffff80001039ad04)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/namei.c:readlink_copy
```
```
In fs/fcntl.c (ffff80001039c784)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (ffff80001039e4ec)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/ioctl.c:fiemap_fill_next_extent
```
```
In fs/readdir.c (ffff8000103a0604)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
```
```
In fs/select.c (ffff8000103a2314)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
```
```
In fs/filesystems.c (ffff8000103b33e4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/filesystems.c:fs_name
```
```
In fs/seq_file.c (ffff8000103bcd4c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
Direct callers:
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (ffff8000103be920)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
```
```
In fs/libfs.c (ffff8000103c1b2c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/libfs.c:simple_read_from_buffer
```
```
In fs/splice.c (ffff8000103cef88)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/splice.c:do_splice
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/d_path.c (ffff8000103d1edc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/d_path.c:__arm64_sys_getcwd
```
```
In fs/statfs.c (ffff8000103d3280)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
```
```
In fs/fsopen.c (ffff8000103d7344)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/fsopen.c:fscontext_read
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ec048)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ef85c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
```
```
In fs/signalfd.c (ffff8000103f3c10)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_copyinfo
```
```
In fs/userfaultfd.c (ffff8000103f8b00)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (ffff8000103fb968)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events_ring
```
```
In fs/io_uring.c (ffff800010403f68)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_setup
```
```
In fs/crypto/keyring.c (ffff80001040e244)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/policy.c (ffff80001041088c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
```
```
In fs/verity/measure.c (ffff8000104126b0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
```
```
In fs/binfmt_elf.c (ffff80001041eaec)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/compat_binfmt_elf.c (ffff8000104225ac)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:create_elf_tables
```
```
In fs/fhandle.c (ffff800010429a30)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
  - fs/fhandle.c:__arm64_sys_name_to_handle_at
```
```
In fs/quota/quota.c (ffff800010436cf4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
Direct callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
```
```
In fs/proc/task_mmu.c (ffff80001043a794)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
```
```
In fs/proc/base.c (ffff800010440b74)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
Direct callers:
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
```
```
In fs/proc/kcore.c (ffff80001044dd68)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffff80001044eb00)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In fs/kernfs/file.c (ffff800010455804)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
```
```
In fs/dcookies.c (ffff80001045f4b0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/dcookies.c:do_lookup_dcookie
```
```
In fs/ext4/ioctl.c (ffff80001048c908)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/ext4/ioctl.c:ext4_getfsmap_format
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/fat/dir.c (ffff8000104e7b28)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_compat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
```
```
In fs/fat/file.c (ffff8000104eb458)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/miscdev.c (ffff8000104fe238)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (ffff80001051bddc)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In ipc/msgutil.c (ffff80001051e278)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
```
```
In ipc/msg.c (ffff800010520514)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
```
In ipc/sem.c (ffff8000105222a4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
Direct callers:
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
```
```
In ipc/shm.c (ffff8000105282f8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
```
```
In ipc/mqueue.c (ffff80001052ad14)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
```
```
In security/keys/keyctl.c (ffff800010531f48)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
```
```
In security/keys/request_key_auth.c (ffff800010536434)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_read
```
```
In security/keys/user_defined.c (ffff800010536c64)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_read
```
```
In security/keys/dh.c (ffff80001053853c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
Direct callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/keyctl_pkey.c (ffff80001053940c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In security/keys/big_key.c (ffff800010539fc0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
Direct callers:
  - security/keys/big_key.c:big_key_read
```
```
In security/keys/trusted.c (ffff80001053b4e8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053d310)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/selinux/hooks.c (ffff80001054fa40)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
```
```
In security/smack/smack_lsm.c (ffff8000105710d0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
```
```
In security/tomoyo/common.c (ffff800010579444)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
```
```
In security/tomoyo/securityfs_if.c (ffff80001058684c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
```
```
In security/apparmor/lsm.c (ffff80001059e568)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
```
In block/ioctl.c (ffff8000105f847c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/scsi_ioctl.c (ffff800010609054)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffff800010609e2c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/bsg-lib.c (ffff80001060b26c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_transport_complete_rq
```
```
In block/compat_ioctl.c (ffff80001061c10c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/compat_ioctl.c:compat_blkdev_ioctl
```
```
In block/blk-zoned.c (ffff80001061fb70)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (ffff8000106327b0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
```
```
In lib/kfifo.c (ffff8000106348f4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
```
```
In drivers/gpio/gpiolib.c (ffff8000106c317c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/gpio/gpiolib.c:linehandle_ioctl
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (ffff8000107447a8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/video/fbdev/core/fbcmap.c (ffff800010748df0)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
```
```
In drivers/video/fbdev/core/fbcon.c (ffff800010753090)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
```
```
In drivers/video/fbdev/imsttfb.c (ffff80001075a88c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
Direct callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff80001083a54c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
```
```
In drivers/tty/tty_io.c (ffff800010851e2c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/tty/n_tty.c (ffff800010856574)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/n_tty.c:copy_from_read_buf
```
```
In drivers/tty/tty_ioctl.c (ffff80001085b48c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
```
```
In drivers/tty/vt/vt_ioctl.c (ffff80001086708c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/vc_screen.c (ffff800010868474)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/tty/vt/keyboard.c (ffff80001086d0b4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
```
```
In drivers/tty/vt/consolemap.c (ffff8000108700bc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
```
```
In drivers/tty/vt/vt.c (ffff800010878fb8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/vt/vt.c:con_get_cmap
```
```
In drivers/tty/serial/serial_core.c (ffff8000108828fc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/char/mem.c (ffff8000108ab534)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffff8000108b0b10)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (ffff8000108b5e48)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In drivers/char/hw_random/core.c (ffff8000108b7830)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/char/tpm/tpm-dev-common.c (ffff8000108b8a50)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
```
```
In drivers/lightnvm/core.c (ffff8000108e0240)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (ffff80001091aae4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
```
In drivers/block/loop.c (ffff8000109241dc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/block/loop.c:loop_get_status_old
```
```
In drivers/nvdimm/bus.c (ffff8000109518c8)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
```
In drivers/dma-buf/sync_file.c (ffff80001096a660)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096ba84)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_ioctl.c (ffff800010970120)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (ffff800010992f4c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
```
```
In drivers/ata/libata-scsi.c (ffff8000109a4440)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
```
In drivers/gpu/vga/vgaarb.c (ffff8000109c0e4c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/net/tun.c (ffff8000109dbac0)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (ffff8000109ed128)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_get
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a01288)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/cdrom/cdrom.c (ffff800010a0f06c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
```
In drivers/usb/core/devio.c (ffff800010a321d4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (ffff800010a348c0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/input/input-compat.c (ffff800010a99208)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In drivers/input/mousedev.c (ffff800010a9c834)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_read
```
```
In drivers/input/evdev.c (ffff800010a9fa64)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/evdev.c:bits_to_user
Direct callers:
  - drivers/input/evdev.c:evdev_do_ioctl
```
```
In drivers/input/misc/uinput.c (ffff800010aa50ac)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_str_to_user
  - drivers/input/misc/uinput.c:uinput_str_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
```
```
In drivers/rtc/dev.c (ffff800010aaadac)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
```
In drivers/i2c/i2c-dev.c (ffff800010ab7fec)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
```
In drivers/media/cec/cec-api.c (ffff800010ac2974)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
Direct callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
```
```
In drivers/pps/pps.c (ffff800010ac5a40)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
```
```
In drivers/ptp/ptp_chardev.c (ffff800010ac7930)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010ae0318)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
```
In drivers/md/md.c (ffff800010af35a8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
Direct callers:
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/dm-ioctl.c (ffff800010b091c4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In drivers/mmc/core/block.c (ffff800010b425f0)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In net/socket.c (ffff800010ba6de4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:compat_sioc_ifmap
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/socket.c:move_addr_to_user
```
```
In net/core/sock.c (ffff800010baf294)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
Direct callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/scm.c (ffff800010bbdf74)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
```
```
In net/core/flow_dissector.c (ffff800010bc3200)
Location: include/linux/uaccess.h:126
Inline: True
Direct callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/sysctl_net_core.c (ffff800010bc5a98)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (ffff800010bdc8f8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/ethtool.c:ethtool_get_features
  - net/core/ethtool.c:ethtool_get_features
Direct callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/ethtool.c:ethtool_get_features
  - net/core/ethtool.c:ethtool_get_features
```
```
In net/core/filter.c (ffff800010c03030)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/compat.c (ffff800010c32b88)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
```
```
In net/bpf/test_run.c (ffff800010c52a90)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffff800010c66a84)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp.c (ffff800010c71ba8)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In net/ipv4/raw.c (ffff800010c97784)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_geticmpfilter
```
```
In net/ipv4/udp.c (ffff800010c9a84c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_getsockopt
```
```
In net/ipv4/arp.c (ffff800010ca33ac)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
```
```
In net/ipv4/devinet.c (ffff800010ca67e0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_gifconf
```
```
In net/ipv4/af_inet.c (ffff800010cabee0)
Location: include/linux/uaccess.h:126
Inline: True
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
```
In net/ipv4/igmp.c (ffff800010cb29f0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_gsfget
Direct callers:
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
```
```
In net/ipv4/ipmr.c (ffff800010ccf688)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1c5a8)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In net/ipv6/raw.c (ffff800010d28f44)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In net/ipv6/mcast.c (ffff800010d2e268)
Location: include/linux/uaccess.h:126
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3ec88)
Location: include/linux/uaccess.h:126
Inline: True
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/ip6mr.c (ffff800010d47848)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (ffff800010d5d4f8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (ffff800010d61cf4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
Direct callers:
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
```
```
In net/wireless/wext-priv.c (ffff800010d625e0)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In net/rfkill/core.c (ffff800010d6d2e8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_read
```
```
In net/xdp/xsk.c (ffff800010d7fcc0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
```
```
In lib/seq_buf.c (ffff800010d8ffdc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffff8000100b8f10-ffff8000100b9070: _copy_to_user (STB_LOCAL)
ffff8000100c32d8-ffff8000100c3438: _copy_to_user (STB_LOCAL)
ffff8000101af8c0-ffff8000101afa20: _copy_to_user.constprop.0 (STB_LOCAL)
ffff800010208b30-ffff800010208c2c: _copy_to_user.part.0 (STB_LOCAL)
ffff80001024d1e8-ffff80001024d348: _copy_to_user (STB_LOCAL)
ffff800010260330-ffff800010260490: _copy_to_user (STB_LOCAL)
ffff80001028d6c8-ffff80001028d828: _copy_to_user (STB_LOCAL)
ffff80001038ab10-ffff80001038ac0c: _copy_to_user.part.0 (STB_LOCAL)
ffff80001039ba50-ffff80001039bbb0: _copy_to_user (STB_LOCAL)
ffff8000103bc650-ffff8000103bc7b0: _copy_to_user (STB_LOCAL)
ffff8000103be2e0-ffff8000103be3dc: _copy_to_user.part.0 (STB_LOCAL)
ffff8000103ce988-ffff8000103cea88: _copy_to_user.part.0.constprop.0 (STB_LOCAL)
ffff8000103cec20-ffff8000103ced80: _copy_to_user.constprop.0 (STB_LOCAL)
ffff8000103d30f8-ffff8000103d31f4: _copy_to_user.part.0 (STB_LOCAL)
ffff8000103ee0b8-ffff8000103ee218: _copy_to_user (STB_LOCAL)
ffff80001040d228-ffff80001040d388: _copy_to_user (STB_LOCAL)
ffff800010435790-ffff80001043588c: _copy_to_user.part.0 (STB_LOCAL)
ffff80001043eec8-ffff80001043efc4: _copy_to_user.part.0 (STB_LOCAL)
ffff80001044dd68-ffff80001044dec8: _copy_to_user (STB_LOCAL)
ffff80001048b090-ffff80001048b1f0: _copy_to_user (STB_LOCAL)
ffff80001051e278-ffff80001051e3d8: _copy_to_user (STB_LOCAL)
ffff80001051fe00-ffff80001051ff60: _copy_to_user (STB_LOCAL)
ffff800010521ee0-ffff800010521fdc: _copy_to_user.part.0 (STB_LOCAL)
ffff800010526900-ffff8000105269fc: _copy_to_user.part.0 (STB_LOCAL)
ffff800010531f48-ffff8000105320a8: _copy_to_user (STB_LOCAL)
ffff800010537f08-ffff800010538004: _copy_to_user.part.0 (STB_LOCAL)
ffff8000105381b8-ffff800010538318: _copy_to_user (STB_LOCAL)
ffff800010539df0-ffff800010539f50: _copy_to_user (STB_LOCAL)
ffff80001053d310-ffff80001053d470: _copy_to_user (STB_LOCAL)
ffff80001061fb70-ffff80001061fcd0: _copy_to_user (STB_LOCAL)
ffff8000106c08c0-ffff8000106c0a20: _copy_to_user (STB_LOCAL)
ffff800010748df0-ffff800010748f50: _copy_to_user (STB_LOCAL)
ffff800010759f38-ffff80001075a034: _copy_to_user.part.0 (STB_LOCAL)
ffff8000108655b0-ffff800010865710: _copy_to_user (STB_LOCAL)
ffff8000109518c8-ffff800010951a28: _copy_to_user (STB_LOCAL)
ffff80001096a660-ffff80001096a7c0: _copy_to_user (STB_LOCAL)
ffff8000109a4440-ffff8000109a45a0: _copy_to_user (STB_LOCAL)
ffff8000109dbac0-ffff8000109dbc20: _copy_to_user (STB_LOCAL)
ffff8000109ff808-ffff8000109ff968: _copy_to_user (STB_LOCAL)
ffff800010a0d348-ffff800010a0d444: _copy_to_user.part.0 (STB_LOCAL)
ffff800010a99208-ffff800010a99304: _copy_to_user.part.0 (STB_LOCAL)
ffff800010a9ee48-ffff800010a9efa8: _copy_to_user (STB_LOCAL)
ffff800010aa4ef8-ffff800010aa5058: _copy_to_user (STB_LOCAL)
ffff800010ac25d8-ffff800010ac26d4: _copy_to_user.part.0 (STB_LOCAL)
ffff800010ac5a40-ffff800010ac5ba0: _copy_to_user (STB_LOCAL)
ffff800010ac7930-ffff800010ac7a90: _copy_to_user (STB_LOCAL)
ffff800010ae7cd8-ffff800010ae7e38: _copy_to_user (STB_LOCAL)
ffff800010bac828-ffff800010bac988: _copy_to_user (STB_LOCAL)
ffff800010bc3200-ffff800010bc3360: _copy_to_user.constprop.0 (STB_LOCAL)
ffff800010bd97e8-ffff800010bd98e4: _copy_to_user.part.0 (STB_LOCAL)
ffff800010bd98e8-ffff800010bd9968: _copy_to_user (STB_LOCAL)
ffff800010c52a90-ffff800010c52b8c: _copy_to_user.part.0 (STB_LOCAL)
ffff800010c66270-ffff800010c663d0: _copy_to_user (STB_LOCAL)
ffff800010c71ba8-ffff800010c71d08: _copy_to_user (STB_LOCAL)
ffff800010cabee0-ffff800010cac040: _copy_to_user.constprop.0 (STB_LOCAL)
ffff800010cae470-ffff800010cae5d0: _copy_to_user (STB_LOCAL)
ffff800010d1c5a8-ffff800010d1c708: _copy_to_user (STB_LOCAL)
ffff800010d2e268-ffff800010d2e3c8: _copy_to_user (STB_LOCAL)
ffff800010d3ec88-ffff800010d3ede8: _copy_to_user.constprop.0 (STB_LOCAL)
ffff800010d610b0-ffff800010d611ac: _copy_to_user.part.0 (STB_LOCAL)
ffff800010d625e0-ffff800010d626dc: _copy_to_user.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/ptrace.c (c030cacc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:arch_ptrace
```
```
In arch/arm/kernel/crash_dump.c (c0315b34)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - arch/arm/kernel/crash_dump.c:copy_oldmem_page
```
```
In kernel/exit.c (c035b230)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/exit.c:__se_sys_wait4
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/sysctl.c (c035edbc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:_proc_do_string
```
```
In kernel/capability.c (c03610a4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capget
```
```
In kernel/ptrace.c (c0362f98)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
```
```
In kernel/signal.c (c036a6e8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigaction
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:__se_sys_sigpending
  - kernel/signal.c:__se_sys_sigaltstack
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__se_sys_rt_sigpending
  - kernel/signal.c:__se_sys_rt_sigprocmask
```
```
In kernel/sys.c (c036eadc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_sysinfo
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__se_sys_getrusage
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_getrlimit
  - kernel/sys.c:__se_sys_gethostname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__se_sys_times
```
```
In kernel/sched/core.c (c038cd20)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_getaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
```
```
In kernel/printk/printk.c (c03c6e34)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_read
```
```
In kernel/profile.c (c03e39e4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/profile.c:read_profile
```
```
In kernel/time/time.c (c03e4e5c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_timespec32
  - kernel/time/time.c:put_timespec64
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__se_sys_gettimeofday
```
```
In kernel/time/posix-timers.c (c03f7518)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/time/itimer.c (c03fada4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/time/itimer.c:__se_sys_setitimer
  - kernel/time/itimer.c:__se_sys_getitimer
```
```
In kernel/seccomp.c (c044934c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
```
```
In kernel/relay.c (c044a0ac)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_read
```
```
In kernel/trace/trace.c (c04649e0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_read
```
```
In kernel/trace/blktrace.c (c0471fc4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
```
```
In kernel/trace/bpf_trace.c (c0481a1c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
```
```
In kernel/bpf/core.c (c0492620)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
```
```
In kernel/bpf/syscall.c (c0497b40)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_task_fd_query_copy
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:map_lookup_elem
```
```
In kernel/bpf/verifier.c (c049aea8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_verifier_vlog
```
```
In kernel/bpf/btf.c (c04b62d8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
```
```
In kernel/bpf/offload.c (c04ba76c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
```
In kernel/bpf/cgroup.c (c04bd5c4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
```
```
In kernel/events/core.c (c04cdaf4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
```
In mm/mincore.c (c051c884)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - mm/mincore.c:__se_sys_mincore
```
```
In fs/read_write.c (c056decc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_llseek
```
```
In fs/stat.c (c057330c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat
```
```
In fs/pipe.c (c0577ec8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/pipe.c:do_pipe2
```
```
In fs/namei.c (c0581240)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/namei.c:readlink_copy
```
```
In fs/fcntl.c (c0582400)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
```
```
In fs/ioctl.c (c0583b44)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
```
```
In fs/select.c (c0584edc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
```
```
In fs/filesystems.c (c05922ac)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/filesystems.c:__se_sys_sysfs
```
```
In fs/seq_file.c (c0599f5c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
```
```
In fs/xattr.c (c059b634)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
```
```
In fs/libfs.c (c059e284)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/libfs.c:simple_read_from_buffer
```
```
In fs/splice.c (c05aa24c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
```
```
In fs/d_path.c (c05acfc0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/d_path.c:__se_sys_getcwd
```
```
In fs/statfs.c (c05ada0c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
```
```
In fs/fsopen.c (c05b0744)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/fsopen.c:fscontext_read
```
```
In fs/notify/inotify/inotify_user.c (c05c32e8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
```
```
In fs/notify/fanotify/fanotify_user.c (c05c4f34)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
```
In fs/signalfd.c (c05c8be0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/signalfd.c:signalfd_copyinfo
```
```
In fs/userfaultfd.c (c05ccc24)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
```
```
In fs/aio.c (c05ce7e4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/aio.c:aio_read_events
```
```
In fs/io_uring.c (c05d6b50)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_setup
```
```
In fs/crypto/keyring.c (c05daf10)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In fs/crypto/policy.c (c05dd038)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
```
```
In fs/verity/measure.c (c05dea6c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
```
```
In fs/binfmt_elf.c (c05e6f28)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/binfmt_elf.c:create_elf_tables
```
```
In fs/binfmt_elf_fdpic.c (c05ea500)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
  - fs/binfmt_elf_fdpic.c:create_elf_fdpic_tables
```
```
In fs/binfmt_flat.c (c05ed100)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
```
```
In fs/fhandle.c (c05f1f78)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/fhandle.c:do_sys_name_to_handle
```
```
In fs/quota/quota.c (c05fe774)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
```
```
In fs/proc/task_mmu.c (c06006d8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
```
```
In fs/proc/base.c (c06047cc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
```
```
In fs/proc/vmcore.c (c0611ec0)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In fs/kernfs/file.c (c0617418)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_read
```
```
In fs/dcookies.c (c061fdac)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/dcookies.c:__se_sys_lookup_dcookie
```
```
In fs/ext4/ioctl.c (c064db64)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
```
```
In fs/fat/dir.c (c06a47e4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
```
```
In fs/fat/file.c (c06a91b0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In fs/ecryptfs/miscdev.c (c06bb528)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
```
```
In fs/efivarfs/file.c (c06d84d0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
```
In ipc/msgutil.c (c06da554)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
```
```
In ipc/msg.c (c06dc03c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:copy_msqid_to_user
  - ipc/msg.c:copy_msqid_to_user
```
```
In ipc/sem.c (c06dde4c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - ipc/sem.c:semctl_main
  - ipc/sem.c:copy_semid_to_user
  - ipc/sem.c:copy_semid_to_user
```
```
In ipc/shm.c (c06e0fb8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
```
In ipc/mqueue.c (c06e4fc8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_getsetattr
```
```
In security/keys/keyctl.c (c06eb18c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
```
```
In security/keys/request_key_auth.c (c06ed848)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_read
```
```
In security/keys/user_defined.c (c06edff4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/keys/user_defined.c:user_read
```
```
In security/keys/dh.c (c06ef4c4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/keyctl_pkey.c (c06efc1c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
```
```
In security/keys/big_key.c (c06f0594)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
```
```
In security/keys/trusted.c (c06f252c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_read
```
```
In security/keys/encrypted-keys/encrypted.c (c06f34fc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
```
```
In security/selinux/hooks.c (c0701124)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
```
```
In security/smack/smack_lsm.c (c072134c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
```
```
In security/tomoyo/common.c (c072cb30)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
```
```
In security/tomoyo/securityfs_if.c (c0737e2c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
```
```
In security/apparmor/lsm.c (c074f4ec)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
```
```
In block/ioctl.c (c07a38a4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
```
In block/scsi_ioctl.c (c07b49f0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (c07b4ed8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
```
```
In block/bsg-lib.c (c07b5b80)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_transport_complete_rq
```
```
In block/blk-zoned.c (c07c7d20)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
```
In lib/iov_iter.c (c07d89bc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
```
```
In lib/kfifo.c (c07da7d4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
```
```
In drivers/gpio/gpiolib.c (c0861620)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
```
```
In drivers/video/fbdev/core/fbmem.c (c08c8c54)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/video/fbdev/core/fbcmap.c (c08cba0c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
```
```
In drivers/video/fbdev/core/fbcon.c (c08d596c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
```
```
In drivers/video/fbdev/imsttfb.c (c08dd6e4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
```
```
In drivers/tty/tty_io.c (c095cecc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
```
```
In drivers/tty/n_tty.c (c0960c80)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
```
```
In drivers/tty/tty_ioctl.c (c0963c54)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:kernel_termios_to_user_termio
```
```
In drivers/tty/vt/vt_ioctl.c (c096bdf8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
```
```
In drivers/tty/vt/vc_screen.c (c096d578)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/tty/vt/keyboard.c (c0971858)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
```
```
In drivers/tty/vt/consolemap.c (c097347c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
```
```
In drivers/tty/vt/vt.c (c097b93c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
```
```
In drivers/tty/serial/serial_core.c (c0982388)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/char/mem.c (c09a744c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (c09aa4d8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
```
```
In drivers/char/virtio_console.c (c09adf00)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In drivers/char/hw_random/core.c (c09b09f8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/char/tpm/tpm-dev-common.c (c09b2224)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
```
```
In drivers/lightnvm/core.c (c09d0234)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
```
```
In drivers/base/regmap/regmap-debugfs.c (c0a00afc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
```
In drivers/block/loop.c (c0a07ddc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
```
```
In drivers/dma-buf/sync_file.c (c0a40a80)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
```
```
In drivers/dma-buf/sw_sync.c (c0a41410)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_ioctl.c (c0a45340)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
```
In drivers/scsi/sg.c (c0a628e4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
```
```
In drivers/ata/libata-scsi.c (c0a756f4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
```
```
In drivers/gpu/vga/vgaarb.c (c0a8d3c0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
```
```
In drivers/mtd/mtdchar.c (c0a96ae4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_ioctl
  - drivers/mtd/mtdchar.c:mtdchar_readoob
  - drivers/mtd/mtdchar.c:mtdchar_writeoob
  - drivers/mtd/mtdchar.c:mtdchar_read
```
```
In drivers/net/tun.c (c0ac7290)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (c0aceeb0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_get
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_set
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad3f6c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (c0adcf50)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
```
In drivers/cdrom/cdrom.c (c0ae728c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
```
In drivers/usb/core/devio.c (c0b0675c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
```
```
In drivers/usb/core/devices.c (c0b081cc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
```
In drivers/input/input-compat.c (c0b7b480)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/input/input-compat.c:input_event_to_user
```
```
In drivers/input/mousedev.c (c0b7d32c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_read
```
```
In drivers/input/evdev.c (c0b7f828)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
```
```
In drivers/input/misc/uinput.c (c0b84474)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
```
In drivers/rtc/dev.c (c0b896f4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
```
In drivers/rtc/rtc-pcf8523.c (c0b8d420)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_ioctl
```
```
In drivers/i2c/i2c-dev.c (c0b979fc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
```
In drivers/media/cec/cec-api.c (c0ba413c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
```
```
In drivers/pps/pps.c (c0ba5960)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
```
```
In drivers/ptp/ptp_chardev.c (c0ba80a4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
```
```
In drivers/watchdog/watchdog_dev.c (c0bc1ac0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
```
```
In drivers/md/md.c (c0bd4bc8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:get_array_info
```
```
In drivers/md/dm-ioctl.c (c0be7a44)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
```
In drivers/mmc/core/block.c (c0c1b3cc)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In sound/core/memory.c (c0c84b38)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - sound/core/memory.c:copy_to_user_fromio
```
```
In sound/core/control.c (c0c8776c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - sound/core/control.c:snd_ctl_read
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_ioctl
  - sound/core/control.c:snd_ctl_tlv_ioctl
  - sound/core/control.c:snd_ctl_elem_add_user
  - sound/core/control.c:snd_ctl_elem_user_tlv
  - sound/core/control.c:snd_ctl_elem_info_user
  - sound/core/control.c:snd_ctl_elem_list
  - sound/core/control.c:snd_ctl_elem_list
```
```
In sound/core/timer.c (c0c8e588)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - sound/core/timer.c:snd_timer_user_read
  - sound/core/timer.c:snd_timer_user_read
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
  - sound/core/timer.c:__snd_timer_user_ioctl
```
```
In sound/core/pcm_native.c (c0c95d18)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_sync_ptr
  - sound/core/pcm_native.c:snd_pcm_status_user
  - sound/core/pcm_native.c:snd_pcm_sw_params_user
  - sound/core/pcm_native.c:snd_pcm_info_user
```
```
In sound/core/pcm_lib.c (c0c98150)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:default_read_copy
```
```
In sound/core/compress_offload.c (c0c9e7ac)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_ioctl
  - sound/core/compress_offload.c:snd_compr_get_caps
```
```
In sound/soc/soc-generic-dmaengine-pcm.c (c0cbb704)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - sound/soc/soc-generic-dmaengine-pcm.c:dmaengine_copy_user
```
```
In net/socket.c (c0cc5460)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:move_addr_to_user
```
```
In net/core/sock.c (c0ccd3fc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
```
```
In net/core/scm.c (c0cda3f4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
```
```
In net/core/flow_dissector.c (c0cde5c4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/sysctl_net_core.c (c0ce0ec8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
```
In net/core/ethtool.c (c0cf72f8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
Direct callers:
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
```
In net/core/filter.c (c0d1c67c)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/core/filter.c:sk_get_filter
```
```
In net/bpf/test_run.c (c0d625ec)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_ctx_finish
  - net/bpf/test_run.c:bpf_ctx_finish
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_finish
  - net/bpf/test_run.c:bpf_test_finish
```
```
In net/ipv4/ip_sockglue.c (c0d75ec0)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In net/ipv4/tcp.c (c0d822e4)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In net/ipv4/raw.c (c0da52dc)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In net/ipv4/udp.c (c0da7c00)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_getsockopt
```
```
In net/ipv4/arp.c (c0db0014)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
```
```
In net/ipv4/devinet.c (c0db2bfc)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_gifconf
```
```
In net/ipv4/af_inet.c (c0db8c74)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
```
In net/ipv4/igmp.c (c0dbe610)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
```
```
In net/ipv4/ipmr.c (c0dd9dec)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
```
```
In net/ipv6/ipv6_sockglue.c (c0e217ec)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In net/ipv6/raw.c (c0e2cfbc)
Location: include/linux/uaccess.h:126
Inline: True
```
```
In net/ipv6/mcast.c (c0e34fa4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
```
```
In net/ipv6/ip6_flowlabel.c (c0e42f28)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
```
```
In net/ipv6/ip6mr.c (c0e494a8)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
```
```
In net/packet/af_packet.c (c0e5d2a0)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_getsockopt
```
```
In net/wireless/wext-core.c (c0e61030)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
```
```
In net/wireless/wext-priv.c (c0e61958)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:ioctl_private_iw_point
```
```
In net/rfkill/core.c (c0e69e00)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_read
```
```
In net/xdp/xsk.c (c0e7a0b4)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
```
```
In lib/seq_buf.c (c0e8a8ac)
Location: include/linux/uaccess.h:126
Inline: True
Inline callers:
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
c0cf36c0-c0cf372c: _copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (c0000000007de1b0)
Location: lib/usercopy.c:24
Inline: False
Direct callers:
  - arch/powerpc/kernel/ptrace.c:arch_ptrace
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/rtas.c:__se_sys_rtas
  - arch/powerpc/kernel/rtasd.c:rtas_log_read
  - arch/powerpc/lib/checksum_wrappers.c:csum_and_copy_to_user
  - arch/powerpc/platforms/pseries/dtl.c:dtl_file_read
  - arch/powerpc/platforms/pseries/dtl.c:dtl_file_read
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:_proc_do_string
  - kernel/capability.c:__se_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_sys_rt_sigaction
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:__se_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__se_sys_sigaltstack
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__se_compat_sys_rt_sigpending
  - kernel/signal.c:__se_sys_rt_sigpending
  - kernel/signal.c:__se_compat_sys_rt_sigprocmask
  - kernel/signal.c:__se_sys_rt_sigprocmask
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_old_getrlimit
  - kernel/sys.c:__se_compat_sys_getrlimit
  - kernel/sys.c:__se_compat_sys_getrlimit
  - kernel/sys.c:__se_sys_getrlimit
  - kernel/sys.c:__se_sys_gethostname
  - kernel/sys.c:__se_sys_olduname
  - kernel/sys.c:__se_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__se_compat_sys_times
  - kernel/sys.c:__se_sys_times
  - kernel/sched/core.c:__do_sys_sched_getaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timespec32
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__se_compat_sys_gettimeofday
  - kernel/time/time.c:__se_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__se_sys_setitimer
  - kernel/time/itimer.c:__se_sys_getitimer
  - kernel/kexec.c:__se_compat_sys_kexec_load
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_itimerval
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:__se_sys_mincore
  - mm/mempolicy.c:__se_compat_sys_migrate_pages
  - mm/mempolicy.c:__se_compat_sys_migrate_pages
  - mm/mempolicy.c:__se_compat_sys_migrate_pages
  - mm/mempolicy.c:__se_compat_sys_mbind
  - mm/mempolicy.c:__se_compat_sys_set_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat64
  - fs/stat.c:cp_new_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/readdir.c:compat_filldir
  - fs/select.c:poll_select_finish
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:__se_sys_sysfs
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/d_path.c:__se_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_uring_setup
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/fhandle.c:__se_sys_name_to_handle_at
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:do_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
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
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:copy_msqid_to_user
  - ipc/msg.c:copy_msqid_to_user
  - ipc/msg.c:copy_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/sem.c:copy_semid_to_user
  - ipc/sem.c:copy_semid_to_user
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
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
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fscreeninfo_to_user
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
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
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/nvram.c:nvram_misc_read
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_npu2_rw
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvgpu_rw
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
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
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/filter.c:sk_get_filter
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
c0000000007de1b0-c0000000007de268: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffe000464f6c)
Location: lib/usercopy.c:24
Inline: False
Direct callers:
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_dostring
  - kernel/capability.c:__se_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__se_sys_rt_sigaction
  - kernel/signal.c:__se_sys_sigaltstack
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__se_sys_rt_sigpending
  - kernel/signal.c:__se_sys_rt_sigprocmask
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__se_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_getrlimit
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__se_sys_times
  - kernel/sched/core.c:__se_sys_sched_getaffinity
  - kernel/sched/core.c:__se_sys_sched_getattr
  - kernel/sched/core.c:__se_sys_sched_getparam
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timespec32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__se_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__se_sys_setitimer
  - kernel/time/itimer.c:__se_sys_getitimer
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:__se_sys_mincore
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/read_write.c:__se_sys_copy_file_range
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:__se_sys_fcntl
  - fs/fcntl.c:__se_sys_fcntl
  - fs/fcntl.c:__se_sys_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:__se_sys_sysfs
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/d_path.c:__se_sys_getcwd
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_uring_setup
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/binfmt_elf.c:create_elf_tables
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/binfmt_flat.c:load_flat_file
  - fs/fhandle.c:__se_sys_name_to_handle_at
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:__se_sys_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_ioc_getfsmap
  - fs/ext4/ioctl.c:ext4_getfsmap_format
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/dir.c:fat_ioctl_filldir
  - fs/fat/file.c:fat_generic_ioctl
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/sem.c:semctl_main
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
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
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
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
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:processcompl
  - drivers/usb/core/devio.c:proc_getdriver
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/filter.c:sk_get_filter
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/wireless/wext-priv.c:ioctl_private_call
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffffffe000464f6c-ffffffe000464f98: _copy_to_user (STB_GLOBAL)
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
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff81524750)
Location: lib/usercopy.c:24
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_dostring
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_itimerval
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/readdir.c:compat_filldir
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_uring_setup
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:do_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
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
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg-lib.c:bsg_transport_complete_rq
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
  - drivers/nvme/host/lightnvm.c:nvme_nvm_user_vcmd
  - drivers/nvme/host/lightnvm.c:nvme_nvm_submit_vio
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_link_ksettings
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
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffffffff81524750-ffffffff81524780: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff81514a30)
Location: lib/usercopy.c:24
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_dostring
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_itimerval
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/readdir.c:compat_filldir
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_uring_setup
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:do_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
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
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg-lib.c:bsg_transport_complete_rq
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_rw
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_link_ksettings
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
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffffffff81514a30-ffffffff81514a60: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff815207e0)
Location: lib/usercopy.c:24
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_dostring
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_itimerval
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/readdir.c:compat_filldir
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_uring_setup
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:do_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
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
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg-lib.c:bsg_transport_complete_rq
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_rw
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_link_ksettings
  - net/core/filter.c:sk_get_filter
  - net/compat.c:get_compat_bpf_fprog
  - net/compat.c:put_cmsg_compat
  - net/compat.c:put_cmsg_compat
  - net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst
  - net/netfilter/nf_conntrack_proto.c:getorigdst
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
  - net/ipv4/raw.c:raw_geticmpfilter
  - net/ipv4/udp.c:udp_lib_getsockopt
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:inet_gifconf
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffffffff815207e0-ffffffff81520810: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int _copy_to_user(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/usercopy.c (ffffffff8153a160)
Location: lib/usercopy.c:24
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:read_ldt
  - arch/x86/kernel/tls.c:do_get_thread_area
  - arch/x86/kernel/tboot.c:tboot_log_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_read
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:__mce_read_apei
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr
  - arch/x86/kernel/uprobes.c:emulate_push_stack
  - arch/x86/kernel/umip.c:fixup_umip_exception
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_wait4
  - kernel/exit.c:__do_sys_waitid
  - kernel/sysctl.c:proc_put_long
  - kernel/sysctl.c:proc_dostring
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_readdata
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__ia32_sys_sigaltstack
  - kernel/signal.c:__x64_sys_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_sys_rt_sigpending
  - kernel/signal.c:__x64_sys_rt_sigpending
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/sys.c:__do_sys_sysinfo
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
  - kernel/sys.c:__do_sys_getrusage
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_old_getrlimit
  - kernel/sys.c:__x64_sys_old_getrlimit
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_sys_getrlimit
  - kernel/sys.c:__x64_sys_getrlimit
  - kernel/sys.c:__ia32_sys_gethostname
  - kernel/sys.c:__x64_sys_gethostname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_uname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__do_sys_newuname
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_sys_times
  - kernel/sys.c:__x64_sys_times
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:__ia32_sys_sched_getparam
  - kernel/sched/core.c:__x64_sys_sched_getparam
  - kernel/printk/printk.c:devkmsg_read
  - kernel/profile.c:read_profile
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_old_itimerspec32
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_itimerspec64
  - kernel/time/time.c:put_old_timex32
  - kernel/time/time.c:__do_sys_adjtimex
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_sys_gettimeofday
  - kernel/time/time.c:__x64_sys_gettimeofday
  - kernel/time/posix-timers.c:__do_sys_clock_adjtime
  - kernel/time/posix-timers.c:do_timer_create
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
  - kernel/time/itimer.c:__ia32_sys_getitimer
  - kernel/time/itimer.c:__x64_sys_getitimer
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/compat.c:put_compat_rusage
  - kernel/compat.c:put_compat_itimerval
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_ioctl
  - kernel/relay.c:relay_file_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/trace/bpf_trace.c:perf_event_query_prog_array
  - kernel/bpf/core.c:bpf_prog_array_copy_to_user
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_obj_get_info_by_fd
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/verifier.c:bpf_verifier_vlog
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/btf.c:btf_get_info_by_fd
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/bpf/cgroup.c:__cgroup_bpf_query
  - kernel/events/core.c:_perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/migrate.c:do_pages_stat
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__x64_sys_copy_file_range
  - fs/read_write.c:__ia32_sys_llseek
  - fs/read_write.c:__x64_sys_llseek
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_statx
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_old_stat
  - fs/pipe.c:do_pipe2
  - fs/namei.c:readlink_copy
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:do_fcntl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:fiemap_fill_next_extent
  - fs/readdir.c:compat_filldir
  - fs/select.c:poll_select_finish
  - fs/filesystems.c:fs_name
  - fs/seq_file.c:seq_read
  - fs/seq_file.c:seq_read
  - fs/xattr.c:listxattr
  - fs/xattr.c:getxattr
  - fs/libfs.c:simple_read_from_buffer
  - fs/splice.c:do_splice
  - fs/splice.c:do_splice
  - fs/d_path.c:__ia32_sys_getcwd
  - fs/d_path.c:__x64_sys_getcwd
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:put_compat_statfs64
  - fs/statfs.c:put_compat_statfs
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:do_statfs64
  - fs/statfs.c:do_statfs_native
  - fs/fsopen.c:fscontext_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
  - fs/signalfd.c:signalfd_copyinfo
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_ioctl
  - fs/userfaultfd.c:userfaultfd_read
  - fs/aio.c:aio_read_events
  - fs/io_uring.c:io_uring_setup
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy_ex
  - fs/crypto/policy.c:fscrypt_ioctl_get_policy
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/verity/measure.c:fsverity_ioctl_measure
  - fs/binfmt_elf.c:create_elf_tables
  - fs/compat_binfmt_elf.c:create_elf_tables
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_getxstatev
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_getinfo
  - fs/proc/task_mmu.c:pagemap_read
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:environ_read
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/kernfs/file.c:kernfs_fop_read
  - fs/dcookies.c:do_lookup_dcookie
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
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
  - fs/efivarfs/file.c:efivarfs_file_ioctl
  - ipc/msgutil.c:store_msg
  - ipc/msgutil.c:store_msg
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/msg.c:copy_compat_msqid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:copy_compat_semid_to_user
  - ipc/sem.c:semctl_main
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/shm.c:copy_compat_shmid_to_user
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__do_sys_mq_getsetattr
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/request_key_auth.c:request_key_auth_read
  - security/keys/user_defined.c:user_read
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_read
  - security/keys/trusted.c:trusted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/smack/smack_lsm.c:smack_socket_getpeersec_stream
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/common.c:tomoyo_flush
  - security/tomoyo/securityfs_if.c:tomoyo_read_self
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - block/ioctl.c:blkdev_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_scsi_complete_rq
  - block/bsg-lib.c:bsg_transport_complete_rq
  - block/compat_ioctl.c:compat_blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
  - lib/kfifo.c:kfifo_copy_to_user
  - lib/kfifo.c:kfifo_copy_to_user
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:lineevent_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:do_fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_read
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcmap.c:fb_cmap_to_user
  - drivers/video/fbdev/core/fbcon.c:fbcon_get_con2fb_map_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_read
  - drivers/xen/mcelog.c:xen_mce_chrdev_read
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:n_tty_read
  - drivers/tty/n_tty.c:copy_from_read_buf
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:get_termio
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_compat_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_event_wait_ioctl
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/consolemap.c:con_get_unimap
  - drivers/tty/vt/consolemap.c:con_get_trans_new
  - drivers/tty/vt/consolemap.c:con_get_trans_old
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_get_cmap
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:read_mem
  - drivers/char/random.c:urandom_read
  - drivers/char/hpet.c:hpet_ioctl
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_read
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/block/loop.c:loop_info64_to_compat
  - drivers/block/loop.c:loop_get_status64
  - drivers/block/loop.c:loop_get_status_old
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
  - drivers/scsi/sg.c:sg_new_read
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_task_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/ata/libata-scsi.c:ata_cmd_ioctl
  - drivers/gpu/vga/vgaarb.c:vga_arb_read
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_net_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_cfg_rw
  - drivers/vfio/pci/vfio_pci_igd.c:vfio_pci_igd_rw
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_auth
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_volume
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:proc_bulk
  - drivers/usb/core/devio.c:proc_control
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:copy_urb_data_to_user
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devio.c:usbdev_read
  - drivers/usb/core/devices.c:usb_device_dump
  - drivers/input/input-compat.c:input_event_to_user
  - drivers/input/mousedev.c:mousedev_read
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_do_ioctl
  - drivers/input/evdev.c:evdev_handle_get_keycode_v2
  - drivers/input/evdev.c:str_to_user
  - drivers/input/evdev.c:bits_to_user
  - drivers/input/misc/uinput.c:uinput_ff_upload_to_user
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus
  - drivers/i2c/i2c-dev.c:i2cdev_read
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/pps/pps.c:pps_cdev_compat_ioctl
  - drivers/pps/pps.c:pps_cdev_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/ptp/ptp_chardev.c:ptp_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - drivers/md/dm-ioctl.c:ctl_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:compat_sock_ioctl
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:sock_do_ioctl
  - net/socket.c:move_addr_to_user
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/sock.c:sock_getsockopt
  - net/core/scm.c:put_cmsg
  - net/core/scm.c:put_cmsg
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_value
  - net/core/ethtool.c:ethtool_get_channels
  - net/core/ethtool.c:ethtool_get_coalesce
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_get_any_eeprom
  - net/core/ethtool.c:ethtool_set_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxfh_indir
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_get_rxnfc
  - net/core/ethtool.c:ethtool_set_rxnfc
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_sset_info
  - net/core/ethtool.c:ethtool_get_drvinfo
  - net/core/ethtool.c:ethtool_get_settings
  - net/core/ethtool.c:ethtool_get_link_ksettings
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
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_gsfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/igmp.c:ip_mc_msfget
  - net/ipv4/ipmr.c:ipmr_compat_ioctl
  - net/ipv4/ipmr.c:ipmr_ioctl
  - net/ipv4/ipmr.c:ip_mroute_getsockopt
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/mcast.c:ip6_mc_msfget
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_compat_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6mr_ioctl
  - net/ipv6/ip6mr.c:ip6_mroute_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/wireless/wext-core.c:compat_wext_handle_ioctl
  - net/wireless/wext-core.c:wext_handle_ioctl
  - net/wireless/wext-core.c:ioctl_standard_iw_point
  - net/rfkill/core.c:rfkill_fop_read
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - net/xdp/xsk.c:xsk_getsockopt
  - lib/seq_buf.c:seq_buf_to_user
```
**Symbols:**

```
ffffffff8153a160-ffffffff8153a190: _copy_to_user (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int n</code> ➡️ <code>long unsigned int n</code>
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
