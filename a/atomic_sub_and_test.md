# Function: <code>atomic_sub_and_test</code>

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
In kernel/nsproxy.c (ffffffff810a1011)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/sched/auto_group.c (ffffffff810c4a34)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:autogroup_move_group
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:sched_autogroup_exit
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
```
```
In kernel/irq/manage.c (ffffffff810db52c)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
```
```
In kernel/time/posix-clock.c (ffffffff810fa791)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_release
  - kernel/time/posix-clock.c:posix_clock_unregister
```
```
In kernel/cgroup.c (ffffffff81115370)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_kill_sb
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/utsname.c (ffffffff8111dbc5)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8111f6ea)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
```
```
In kernel/relay.c (ffffffff8113d1d9)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_open
```
```
In mm/page_alloc.c (ffffffff811974a8)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_page_frag
```
```
In mm/zswap.c (ffffffff811d8452)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff811dba98)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_reserve_pages
```
```
In fs/eventfd.c (ffffffff81259289)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/aio.c (ffffffff8125c8bc)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/hugetlbfs/inode.c (ffffffff812f47d8)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
```
In fs/fuse/file.c (ffffffff81316416)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff81375159)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_fs_seq_profile_release
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
```
```
In security/apparmor/capability.c (ffffffff81376f87)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/context.c (ffffffff813771da)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
```
```
In security/apparmor/lib.c (ffffffff81378fcc)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (ffffffff81379051)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
```
In security/apparmor/domain.c (ffffffff8137a5e7)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/domain.c:may_change_ptraced_domain
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/policy.c (ffffffff8137f180)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/policy.c:__list_remove_profile
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_may_open_profiles
  - security/apparmor/policy.c:aa_may_open_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_remove_profiles
```
```
In security/apparmor/policy_unpack.c (ffffffff81382792)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In security/apparmor/procattr.c (ffffffff81382d3a)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813839cf)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/resource.c (ffffffff813875cb)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81387b95)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff813896ce)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_proxy_kref
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
```
In security/apparmor/mount.c (0)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
```
```
In security/apparmor/net.c (ffffffff81390ad5)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81392b20)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
```
```
In security/apparmor/policy_ns.c (ffffffff81394650)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In block/bsg.c (ffffffff813d5f20)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - block/bsg.c:bsg_unregister_queue
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_release
```
```
In lib/kobject.c (ffffffff813eb7c7)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
```
In lib/cpu_rmap.c (ffffffff81415ff0)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_release
  - lib/cpu_rmap.c:free_irq_cpu_rmap
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff8141dfda)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81452dca)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
```
```
In drivers/acpi/ec.c (ffffffff814832df)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff814be20e)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/tty/tty_io.c (ffffffff814e0832)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:proc_clear_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
```
In drivers/tty/tty_port.c (ffffffff814eba41)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
```
In drivers/char/virtio_console.c (ffffffff81517cb2)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8151a54e)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
```
```
In drivers/base/firmware_class.c (ffffffff8155ef4b)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:fw_free_buf
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8159937e)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815a32fb)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_release
  - drivers/dma-buf/dma-buf.c:dma_buf_release
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/reservation.c (ffffffff815a50c3)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
```
In drivers/scsi/scsi_scan.c (ffffffff815b35a5)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff815c0e9f)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:sr_remove
```
```
In drivers/scsi/sg.c (ffffffff815c3326)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io_usercontext
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/hub.c (ffffffff81605311)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_event
```
```
In drivers/usb/core/hcd.c (ffffffff8160cb81)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_put_hcd
```
```
In drivers/usb/core/urb.c (ffffffff816108d5)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81611fd7)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff81616c66)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffff816176ed)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/clk/clk.c (ffffffff816e7293)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_put
```
```
In net/core/sock.c (ffffffff817041b6)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - net/core/sock.c:sock_wfree
```
```
In lib/klist.c (ffffffff81817776)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_put
  - lib/klist.c:klist_prev
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
In kernel/nsproxy.c (ffffffff810a4862)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/sched/auto_group.c (ffffffff810c8d30)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_exit
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff810e0bc9)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
```
```
In kernel/time/posix-clock.c (ffffffff81101a66)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - kernel/time/posix-clock.c:posix_clock_release
```
```
In kernel/utsname.c (ffffffff81125b2c)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8112762a)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
```
```
In kernel/relay.c (ffffffff8114576c)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In mm/page_alloc.c (ffffffff811ab3ca)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_page_frag
```
```
In mm/zswap.c (ffffffff811f6c1a)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff811fb6b7)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
```
```
In mm/memcontrol.c (ffffffff8121eee5)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
```
```
In fs/eventfd.c (ffffffff81281c69)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/aio.c (ffffffff8128597c)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/hugetlbfs/inode.c (ffffffff81327a1c)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
```
In fs/fuse/file.c (ffffffff8134d94e)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_aio_complete
```
```
In security/apparmor/apparmorfs.c (ffffffff813abbab)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
  - security/apparmor/apparmorfs.c:rawdata_read
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_abi_show
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profile_release
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/capability.c (ffffffff813af9fd)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/context.c (ffffffff813b054a)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
```
```
In security/apparmor/lib.c (ffffffff813b1d62)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (ffffffff813b1df1)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
```
In security/apparmor/domain.c (ffffffff813b8465)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/policy.c (ffffffff813bb339)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:__list_remove_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813bcd7f)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
```
```
In security/apparmor/procattr.c (ffffffff813bcfd6)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813c0cd7)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/resource.c (ffffffff813c20c2)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813c37cf)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/label.c (ffffffff813c8f4a)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
```
```
In security/apparmor/mount.c (ffffffff813cb695)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff813cc07c)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813ceb21)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In security/apparmor/policy_ns.c (ffffffff813d0622)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:aa_free_ns
```
```
In block/bsg.c (ffffffff8141bc10)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - block/bsg.c:bsg_unregister_queue
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
```
```
In lib/kobject.c (ffffffff81431bb7)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
```
In lib/cpu_rmap.c (ffffffff8145df6b)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
  - lib/cpu_rmap.c:free_irq_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff814666ee)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149fd74)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
```
```
In drivers/acpi/ec.c (ffffffff814d1d82)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff8150dece)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/tty/tty_io.c (ffffffff81532145)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:proc_clear_tty
```
```
In drivers/tty/tty_port.c (ffffffff8153c5f1)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
```
In drivers/char/virtio_console.c (ffffffff8156af9b)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffff8156d23e)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
```
```
In drivers/base/firmware_class.c (ffffffff815b348b)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:fw_free_buf
```
```
In drivers/nvdimm/core.c (ffffffff815ebf8e)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff815eee5e)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815fa592)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_release
  - drivers/dma-buf/dma-buf.c:dma_buf_release
```
```
In drivers/dma-buf/reservation.c (ffffffff815fc0d1)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/dma-buf/fence-array.c (ffffffff815fcece)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/fence-array.c:fence_array_release
  - drivers/dma-buf/fence-array.c:fence_array_enable_signaling
  - drivers/dma-buf/fence-array.c:fence_array_cb_func
```
```
In drivers/dma-buf/sync_file.c (ffffffff815fd22c)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
  - drivers/dma-buf/sync_file.c:sync_file_free
```
```
In drivers/scsi/scsi_scan.c (ffffffff8160ba05)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff816197c3)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:scsi_cd_put
```
```
In drivers/scsi/sg.c (ffffffff8161c89b)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io_usercontext
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/hub.c (ffffffff81669fd1)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff8166c701)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_put_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81670807)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81671f4b)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff81676d26)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffff816777a9)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff816ec54c)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
```
```
In drivers/clk/clk.c (ffffffff8174d2d3)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In net/core/sock.c (ffffffff8176ac99)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In lib/klist.c (ffffffff81891226)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
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
In kernel/nsproxy.c (ffffffff810aa4c2)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/sched/auto_group.c (ffffffff810ced40)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_exit
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff810e75d9)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
```
```
In kernel/time/posix-clock.c (ffffffff81109726)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - kernel/time/posix-clock.c:posix_clock_release
```
```
In kernel/utsname.c (ffffffff8112f53c)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff811311fa)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
```
```
In kernel/relay.c (ffffffff8114f8ec)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In mm/page_alloc.c (ffffffff811bb9a4)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/zswap.c (ffffffff812075cb)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8120c1b7)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
```
```
In mm/memcontrol.c (ffffffff812313f5)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
```
```
In fs/eventfd.c (ffffffff81295799)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/aio.c (ffffffff8129a0fc)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/hugetlbfs/inode.c (ffffffff8133d764)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
```
In fs/fuse/file.c (ffffffff8136325a)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_aio_complete
```
```
In security/apparmor/apparmorfs.c (ffffffff813c27e8)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_raw_abi_show
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_show_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profattach_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profmode_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profname_show
  - security/apparmor/apparmorfs.c:aa_fs_seq_profile_release
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/capability.c (ffffffff813c6b7d)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/context.c (ffffffff813c76ca)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
```
```
In security/apparmor/lib.c (ffffffff813c8f22)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (ffffffff813c8fb1)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
```
In security/apparmor/domain.c (ffffffff813cf853)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/policy.c (ffffffff813d271a)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:__list_remove_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813d41ae)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
```
```
In security/apparmor/procattr.c (ffffffff813d4406)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813d8177)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
```
```
In security/apparmor/resource.c (ffffffff813d9562)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813dad5f)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/label.c (ffffffff813e0577)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_proxy_kref
```
```
In security/apparmor/mount.c (ffffffff813e2d15)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff813e36fc)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813e61a1)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In security/apparmor/policy_ns.c (ffffffff813e7d22)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:aa_free_ns
```
```
In block/bsg.c (ffffffff81437440)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - block/bsg.c:bsg_unregister_queue
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff81437f1c)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_softirq_done
```
```
In lib/kobject.c (ffffffff8144de27)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
```
In lib/cpu_rmap.c (ffffffff8147c99b)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
  - lib/cpu_rmap.c:free_irq_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff814859de)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c18f4)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_remove_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_post_dock_fixup
  - drivers/pci/hotplug/acpiphp_glue.c:free_bridge
```
```
In drivers/acpi/ec.c (ffffffff814f4124)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81535b43)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dma/dmaengine.c (ffffffff8153a02e)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/tty/tty_io.c (ffffffff8155e875)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:proc_clear_tty
```
```
In drivers/tty/tty_port.c (ffffffff81568c51)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
```
In drivers/char/virtio_console.c (ffffffff8159770b)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffff815999ae)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
```
```
In drivers/base/firmware_class.c (ffffffff815e281b)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:fw_free_buf
```
```
In drivers/nvdimm/core.c (ffffffff81618b7e)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8161bfce)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81628862)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_release
  - drivers/dma-buf/dma-buf.c:dma_buf_release
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8162a43e)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/reservation.c (ffffffff8162ace3)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_test_signaled_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8162b50c)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
  - drivers/dma-buf/sync_file.c:sync_file_free
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8162c498)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff8163b2a5)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff8164a453)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:scsi_cd_put
```
```
In drivers/scsi/sg.c (ffffffff8164d4ab)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io_usercontext
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/hub.c (ffffffff81697d01)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff8169a401)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_put_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8169e4b7)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff8169fbfb)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff816a4a06)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffff816a5489)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8171d53f)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
```
```
In net/core/sock.c (ffffffff81797d59)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In lib/klist.c (ffffffff818c59b6)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
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
In mm/page_alloc.c (ffffffff811c3c80)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memcontrol.c (ffffffff8123cc25)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
```
```
In fs/aio.c (ffffffff812a7e3c)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In net/core/sock.c (ffffffff817b5909)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffff81832187)
Location: arch/x86/include/asm/atomic.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
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
In mm/page_alloc.c (ffffffff811d8a20)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memcontrol.c (ffffffff8125c0da)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
```
```
In fs/aio.c (ffffffff812cb3dc)
Location: arch/x86/include/asm/atomic.h:79
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In mm/page_alloc.c (ffffffff811f9c57)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memcontrol.c (ffffffff8127f925)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
```
```
In fs/aio.c (ffffffff812f5c8c)
Location: include/asm-generic/atomic-instrumented.h:328
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In mm/page_alloc.c (ffffffff8120c2fd)
Location: include/asm-generic/atomic-instrumented.h:377
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff8130ad7c)
Location: include/asm-generic/atomic-instrumented.h:377
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In mm/page_alloc.c (ffffffff81272564)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff8132cfd8)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In kernel/padata.c (ffffffff8121d564)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffff812813c4)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff8133fe28)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In kernel/rcu/tree.c (ffffffff811366f2)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
```
```
In kernel/padata.c (ffffffff81249854)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/gup.c (ffffffff81287af8)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page
```
```
In mm/page_alloc.c (ffffffff812b389b)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff81379808)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In kernel/rcu/tree.c (ffffffff81131f5a)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
```
```
In kernel/padata.c (ffffffff812546e4)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffff812bf379)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff81387585)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/iomap/buffered-io.c (ffffffff813bc772)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_page_writeback
  - fs/iomap/buffered-io.c:iomap_read_page_end_io
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
In kernel/rcu/tree.c (ffffffff811326ea)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
```
```
In kernel/padata.c (ffffffff81258c84)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffff812c441d)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In fs/aio.c (ffffffff8138e655)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/io_uring.c (ffffffff813971e0)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
Inline callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/iomap/buffered-io.c (ffffffff813c2de9)
Location: include/asm-generic/atomic-instrumented.h:736
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
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
In kernel/rcu/tree.c (ffffffff81154467)
Location: include/linux/atomic/atomic-instrumented.h:533
Inline: True
```
```
In mm/page_alloc.c (ffffffff813082dd)
Location: include/linux/atomic/atomic-instrumented.h:533
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In fs/aio.c (ffffffff813dbec5)
Location: include/linux/atomic/atomic-instrumented.h:533
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/iomap/buffered-io.c (ffffffff814124a0)
Location: include/linux/atomic/atomic-instrumented.h:533
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
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
In kernel/rcu/update.c (ffffffff8117327e)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff8117a5df)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
```
```
In mm/filemap.c (ffffffff812f2815)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/gup.c (ffffffff8133706c)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_get_folio
```
```
In mm/page_alloc.c (ffffffff813705e9)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In fs/aio.c (ffffffff81465aed)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/iomap/buffered-io.c (ffffffff814885e2)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
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
In kernel/rcu/update.c (ffffffff811aaf08)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811b34a2)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
```
```
In mm/filemap.c (ffffffff8135acc8)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/shmem.c (ffffffff8138ac63)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff813ae52c)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff813ed57b)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In fs/aio.c (ffffffff814f5b6d)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/iomap/buffered-io.c (ffffffff8151c453)
Location: include/linux/atomic/atomic-instrumented.h:564
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
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
In kernel/rcu/update.c (ffffffff811bce28)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811c5002)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
```
```
In mm/filemap.c (ffffffff8138c6ec)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/shmem.c (ffffffff813bd189)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff813e2d7e)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff81422513)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/khugepaged.c (ffffffff814804cb)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff8152c8fd)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/iomap/buffered-io.c (ffffffff8155465f)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
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
In kernel/rcu/update.c (ffffffff811cd248)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811d7fb2)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
```
```
In mm/filemap.c (ffffffff813b624f)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:filemap_free_folio
```
```
In mm/shmem.c (ffffffff813e7ff9)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/gup.c (ffffffff8140d5bb)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/page_alloc.c (ffffffff8144f25c)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
```
```
In mm/khugepaged.c (ffffffff814ae5db)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/aio.c (ffffffff815617dd)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In fs/iomap/buffered-io.c (ffffffff8158a845)
Location: include/linux/atomic/atomic-instrumented.h:1354
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
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
In kernel/padata.c (ffff8000102a9c5c)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffff800010319064)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffff8000103ff808)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In kernel/kthread.c (c037ad60)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_associate_blkcg
```
```
In kernel/cgroup/cgroup.c (c041bcf0)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_get_from_fd
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:css_free_rwork_fn
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
  - kernel/cgroup/cgroup.c:cpu_stat_show
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_kill_sb
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_kn_unlock
```
```
In kernel/cgroup/cgroup-v1.c (c041ed30)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
```
In kernel/cgroup/legacy_freezer.c (c04202b0)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/cgroup/rdma.c (c0421360)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy
```
```
In kernel/cgroup/cpuset.c (c04258c0)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:sched_partition_write
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:update_cpumasks_hier
```
```
In kernel/bpf/arraymap.c (c04ad34c)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr
```
```
In kernel/bpf/cgroup.c (c04bf5dc)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_query
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_detach
  - kernel/bpf/cgroup.c:cgroup_bpf_prog_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_inherit
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
```
In kernel/events/core.c (c04c7bf8)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:perf_event_alloc
  - kernel/events/core.c:_free_event
```
```
In kernel/padata.c (c04d7e9c)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/oom_kill.c (c04e486c)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page-writeback.c (c04e8da4)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In mm/swap.c (0)
Location: include/linux/atomic-fallback.h:1014
Inline: True
```
```
In mm/backing-dev.c (c0504460)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/slab_common.c (c050b988)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:destroy_memcg_params
```
```
In mm/gup.c (0)
Location: include/linux/atomic-fallback.h:1014
Inline: True
```
```
In mm/page_alloc.c (c0533b58)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/slub.c (c054b28c)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c055cafc)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_sk_free
  - mm/memcontrol.c:uncharge_batch
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:memcg_event_remove
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:__memcg_kmem_uncharge
  - mm/memcontrol.c:__memcg_kmem_charge
  - mm/memcontrol.c:memcg_kmem_put_cache
  - mm/memcontrol.c:memcg_kmem_cache_create_func
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:drain_stock
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/hmm.c (c0566904)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/file_table.c (c056e970)
Location: include/linux/atomic-fallback.h:1014
Inline: True
```
```
In fs/inode.c (c058de34)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/fs-writeback.c (c05a70a0)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:wbc_detach_inode
  - fs/fs-writeback.c:inode_switch_wbs
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:locked_inode_to_wb_and_lock_list
  - fs/fs-writeback.c:__inode_attach_wb
  - fs/fs-writeback.c:__inode_attach_wb
```
```
In fs/buffer.c (c05b205c)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/block_dev.c (c05b99d8)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
```
In fs/notify/group.c (c05c067c)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/aio.c (c05cfc54)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:exit_aio
  - fs/aio.c:free_ioctx_users
```
```
In fs/io_uring.c (c05d75b4)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:__io_free_req
  - fs/io_uring.c:io_get_req
```
```
In block/bio.c (c07883ec)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-core.c (c07914a4)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_enter
```
```
In block/blk-merge.c (c0798098)
Location: include/linux/atomic-fallback.h:1014
Inline: True
```
```
In block/blk-mq-sched.c (c07a2918)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
```
In block/blk-cgroup.c (c07b92a0)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (c07bc4a0)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/percpu-refcount.c (c07db6a0)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
```
```
In drivers/block/loop.c (c0a07c2c)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio_complete
```
```
In drivers/dax/super.c (0)
Location: include/linux/atomic-fallback.h:1014
Inline: True
```
```
In drivers/scsi/scsi_lib.c (c0a4c104)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
```
In drivers/md/md.c (c0bcccf0)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - drivers/md/md.c:md_write_end
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
In arch/powerpc/mm/pgtable-frag.c (c000000000089078)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable-frag.c:pte_frag_destroy
```
```
In arch/powerpc/mm/book3s64/mmu_context.c (c000000000090658)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/mmu_context.c:arch_exit_mmap
```
```
In kernel/padata.c (c00000000035cde8)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (c0000000003ebadc)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memcontrol.c (c000000000451d1c)
Location: include/linux/atomic-fallback.h:1014
Inline: True
```
```
In fs/aio.c (c0000000005091cc)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In net/core/sock.c (c000000000c8359c)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (c000000000d8d2f8)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (c000000000da677c)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (c000000000db36c8)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (c000000000dd9098)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In kernel/padata.c (ffffffe0001d2f02)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffe00021ee14)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/memcontrol.c (ffffffe0002438e2)
Location: include/linux/atomic-fallback.h:1014
Inline: True
```
```
In fs/aio.c (ffffffe0002ab9a2)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
```
In net/core/sock.c (ffffffe00073fd2a)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
```
```
In net/ipv4/tcp_output.c (ffffffe0007e3ed6)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/ipv4/tcp_offload.c (ffffffe0007f48c4)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
```
In net/ipv4/udp_offload.c (ffffffe0007fd340)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
```
In net/ipv4/inet_fragment.c (ffffffe0008148cc)
Location: include/linux/atomic-fallback.h:1014
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
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
In kernel/padata.c (ffffffff81215bb4)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffff81279a14)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff81338408)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In kernel/padata.c (ffffffff81208914)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffff8126b904)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff81329138)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In kernel/padata.c (ffffffff81213954)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffff812777b4)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff81335ed8)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
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
In kernel/padata.c (ffffffff81222912)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - kernel/padata.c:padata_serial_worker
```
```
In mm/page_alloc.c (ffffffff812873a4)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
```
```
In fs/aio.c (ffffffff81348fa8)
Location: include/asm-generic/atomic-instrumented.h:735
Inline: True
Inline callers:
  - fs/aio.c:exit_aio
```
</details>
</li>
</ul>

## Differences
