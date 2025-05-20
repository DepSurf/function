# Function: <code>kref_sub</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/nsproxy.c (ffffffff810a1011)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/nsproxy.c:free_nsproxy
```
```
In kernel/sched/auto_group.c (ffffffff810c4a34)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:autogroup_move_group
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:sched_autogroup_exit
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
```
```
In kernel/irq/manage.c (ffffffff810db527)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
```
```
In kernel/time/posix-clock.c (ffffffff810fa791)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_release
  - kernel/time/posix-clock.c:posix_clock_unregister
```
```
In kernel/cgroup.c (ffffffff81115370)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_kill_sb
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/utsname.c (ffffffff8111dbc5)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8111f6ea)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
```
```
In kernel/relay.c (ffffffff8113d1d9)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/relay.c:relay_destroy_buf
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_open
```
```
In mm/zswap.c (ffffffff811d8452)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff811dba98)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_reserve_pages
```
```
In fs/eventfd.c (ffffffff81259289)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/hugetlbfs/inode.c (ffffffff812f47d8)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
```
In fs/fuse/file.c (ffffffff81316416)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_direct_IO
```
```
In security/apparmor/apparmorfs.c (ffffffff81375159)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/context.c (ffffffff813771da)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (ffffffff81379051)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
```
In security/apparmor/domain.c (ffffffff8137a5e7)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_unpack
```
```
In security/apparmor/procattr.c (ffffffff81382d3a)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81387b95)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff813896ce)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
```
```
In security/apparmor/net.c (ffffffff81390ad5)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff81392b20)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_free_ns
  - security/apparmor/policy_ns.c:__aa_remove_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
```
```
In block/bsg.c (ffffffff813d5f20)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - block/bsg.c:bsg_unregister_queue
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_release
```
```
In lib/kobject.c (ffffffff813eb7c7)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
```
In lib/cpu_rmap.c (ffffffff81415ff0)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_release
  - lib/cpu_rmap.c:free_irq_cpu_rmap
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff8141dfda)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81452dca)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/dma/dmaengine.c (ffffffff814be20e)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/tty/tty_io.c (ffffffff814e0820)
Location: include/linux/kref.h:67
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
Direct callers:
  - drivers/tty/tty_io.c:__proc_set_tty
```
```
In drivers/tty/tty_port.c (ffffffff814eba41)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
```
In drivers/char/virtio_console.c (ffffffff81517cb2)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8151a54e)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
```
```
In drivers/base/firmware_class.c (ffffffff8155ef4b)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:fw_free_buf
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8159937e)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815a32fb)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff815c0e9f)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/scsi/sr.c:scsi_cd_put
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:sr_remove
```
```
In drivers/scsi/sg.c (ffffffff815c3326)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_event
```
```
In drivers/usb/core/hcd.c (ffffffff8160cb81)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_put_hcd
```
```
In drivers/usb/core/urb.c (ffffffff816108d5)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81611fd7)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff81616c66)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffff816176ed)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/clk/clk.c (ffffffff816e7293)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_put
```
```
In lib/klist.c (ffffffff81817776)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_put
  - lib/klist.c:klist_prev
```
**Symbols:**

```
ffffffff81394650-ffffffff81394669: kref_sub.constprop.1 (STB_LOCAL)
ffffffff814832df-ffffffff814832f8: kref_sub.constprop.18 (STB_LOCAL)
ffffffff814e0820-ffffffff814e0863: kref_sub.constprop.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/nsproxy.c (ffffffff810a4856)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/sched/auto_group.c (ffffffff810c8d30)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_exit
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff810e0bc4)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
```
```
In kernel/time/posix-clock.c (ffffffff81101a66)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - kernel/time/posix-clock.c:posix_clock_release
```
```
In kernel/utsname.c (ffffffff81125b2c)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8112762a)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
```
```
In kernel/relay.c (ffffffff8114576c)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In mm/zswap.c (ffffffff811f6c1a)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff811fb6b7)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
```
```
In fs/eventfd.c (ffffffff81281c69)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/hugetlbfs/inode.c (ffffffff81327a10)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
```
In fs/fuse/file.c (ffffffff8134d94e)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_aio_complete
```
```
In security/apparmor/apparmorfs.c (ffffffff813abb98)
Location: include/linux/kref.h:67
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
In security/apparmor/capability.c (ffffffff813af9e6)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/context.c (ffffffff813b053a)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (ffffffff813b1df1)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
```
In security/apparmor/domain.c (ffffffff813b8421)
Location: include/linux/kref.h:67
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
In security/apparmor/policy.c (ffffffff813bb329)
Location: include/linux/kref.h:67
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
In security/apparmor/policy_unpack.c (ffffffff813bcd68)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
```
```
In security/apparmor/procattr.c (ffffffff813bcfc6)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813c0cc7)
Location: include/linux/kref.h:67
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
In security/apparmor/resource.c (ffffffff813c20b2)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813c37bf)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/label.c (ffffffff813c8f4a)
Location: include/linux/kref.h:67
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
In security/apparmor/mount.c (ffffffff813cb64e)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff813cc06c)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813ceb11)
Location: include/linux/kref.h:67
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
In security/apparmor/policy_ns.c (ffffffff813d060f)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:aa_free_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
```
```
In block/bsg.c (ffffffff8141bc10)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - block/bsg.c:bsg_unregister_queue
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
```
```
In lib/kobject.c (ffffffff81431bb7)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
```
In lib/cpu_rmap.c (ffffffff8145df6b)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
  - lib/cpu_rmap.c:free_irq_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff814666ee)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149fd74)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/dma/dmaengine.c (ffffffff8150dece)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/tty/tty_io.c (ffffffff81532145)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
```
In drivers/char/virtio_console.c (ffffffff8156af9b)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffff8156d23e)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
```
```
In drivers/base/firmware_class.c (ffffffff815b348b)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:fw_free_buf
```
```
In drivers/nvdimm/core.c (ffffffff815ebf8e)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff815eee5e)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff815fa582)
Location: include/linux/kref.h:67
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
In drivers/dma-buf/reservation.c (ffffffff815fc061)
Location: include/linux/kref.h:67
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
In drivers/dma-buf/fence-array.c (ffffffff815fceb6)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/dma-buf/fence-array.c:fence_array_release
  - drivers/dma-buf/fence-array.c:fence_array_enable_signaling
  - drivers/dma-buf/fence-array.c:fence_array_cb_func
```
```
In drivers/dma-buf/sync_file.c (ffffffff815fd22c)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
  - drivers/dma-buf/sync_file.c:sync_file_free
```
```
In drivers/scsi/scsi_scan.c (ffffffff8160ba05)
Location: include/linux/kref.h:67
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff816197c3)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:scsi_cd_put
```
```
In drivers/scsi/sg.c (ffffffff8161c89b)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff8166c701)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_put_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81670807)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff81671f26)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff81676d26)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffff816777a9)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff816ec54c)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/clk/clk.c (ffffffff8174d2d3)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In lib/klist.c (ffffffff81891226)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff813cfe00-ffffffff813cfe42: kref_sub.constprop.1 (STB_LOCAL)
ffffffff814d1d82-ffffffff814d1d9b: kref_sub.constprop.19 (STB_LOCAL)
ffffffff816ec000-ffffffff816ec019: kref_sub.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/nsproxy.c (ffffffff810aa4b6)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/sched/auto_group.c (ffffffff810ced40)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_exit
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff810e75d4)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
```
```
In kernel/time/posix-clock.c (ffffffff81109726)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - kernel/time/posix-clock.c:posix_clock_release
```
```
In kernel/utsname.c (ffffffff8112f53c)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff811311fa)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
```
```
In kernel/relay.c (ffffffff8114f8ec)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In mm/zswap.c (ffffffff812075cb)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffff8120c1b7)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
```
```
In fs/eventfd.c (ffffffff81295799)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/hugetlbfs/inode.c (ffffffff8133d758)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
```
```
In fs/fuse/file.c (ffffffff8136325a)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_aio_complete
```
```
In security/apparmor/apparmorfs.c (ffffffff813c27d5)
Location: include/linux/kref.h:67
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
In security/apparmor/capability.c (ffffffff813c6b66)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/context.c (ffffffff813c76ba)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (ffffffff813c8fb1)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
```
In security/apparmor/domain.c (ffffffff813cf80f)
Location: include/linux/kref.h:67
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
In security/apparmor/policy.c (ffffffff813d2703)
Location: include/linux/kref.h:67
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
In security/apparmor/policy_unpack.c (ffffffff813d4197)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:aa_load_ent_free
```
```
In security/apparmor/procattr.c (ffffffff813d43f6)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813d8167)
Location: include/linux/kref.h:67
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
In security/apparmor/resource.c (ffffffff813d9552)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813dad4f)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/label.c (ffffffff813e0577)
Location: include/linux/kref.h:67
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
In security/apparmor/mount.c (ffffffff813e2cce)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (ffffffff813e36ec)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffff813e6191)
Location: include/linux/kref.h:67
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
In security/apparmor/policy_ns.c (ffffffff813e7d0f)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
  - security/apparmor/policy_ns.c:aa_free_ns
Direct callers:
  - security/apparmor/policy_ns.c:aa_free_root_ns
```
```
In block/bsg.c (ffffffff81437440)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - block/bsg.c:bsg_unregister_queue
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff81437f1c)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_softirq_done
```
```
In lib/kobject.c (ffffffff8144de27)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
```
```
In lib/cpu_rmap.c (ffffffff8147c99b)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
  - lib/cpu_rmap.c:free_irq_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff814859de)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_unregister
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c18f4)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_delete_query
  - drivers/acpi/ec.c:acpi_ec_remove_query_handlers
```
```
In drivers/clk/clk.c (ffffffff81535b43)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dma/dmaengine.c (ffffffff8153a02e)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
```
```
In drivers/tty/tty_io.c (ffffffff8155e875)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
```
In drivers/char/virtio_console.c (ffffffff8159770b)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffff815999ae)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
```
```
In drivers/base/firmware_class.c (ffffffff815e281b)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:fw_free_buf
```
```
In drivers/nvdimm/core.c (ffffffff81618b7e)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8161bfce)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81628852)
Location: include/linux/kref.h:67
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
In drivers/dma-buf/dma-fence-array.c (ffffffff8162a426)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/reservation.c (ffffffff8162acda)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
  - drivers/dma-buf/sync_file.c:sync_file_free
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8162c488)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
```
In drivers/scsi/scsi_scan.c (ffffffff8163b2a5)
Location: include/linux/kref.h:67
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff8164a453)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:scsi_cd_put
```
```
In drivers/scsi/sg.c (ffffffff8164d4ab)
Location: include/linux/kref.h:67
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
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff8169a401)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_put_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8169e4b7)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffff8169fbd6)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffff816a4a06)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffff816a5489)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8171d53f)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In lib/klist.c (ffffffff818c59b6)
Location: include/linux/kref.h:67
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
**Symbols:**

```
ffffffff813e74e0-ffffffff813e7522: kref_sub.constprop.3 (STB_LOCAL)
ffffffff814f4124-ffffffff814f413d: kref_sub.constprop.22 (STB_LOCAL)
ffffffff8171cff0-ffffffff8171d009: kref_sub.constprop.10 (STB_LOCAL)
```
</details>
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
