# Function: <code>kref_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void kref_get(struct kref *kref);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107f362)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (ffffffff8109e28d)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/auto_group.c (ffffffff810c49b3)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:autogroup_move_group
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
```
```
In kernel/irq/manage.c (ffffffff810dc110)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/time/posix-clock.c (ffffffff810fa1b4)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_open
```
```
In kernel/cgroup.c (ffffffff81118dab)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/cgroup.c:pidlist_array_load
```
```
In kernel/utsname.c (ffffffff8111db20)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8111f4d0)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:copy_pid_ns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/relay.c (ffffffff8113d0e6)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffffffff8117ea3f)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/hugetlb.c (ffffffff811dac63)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/eventfd.c (ffffffff81259167)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/root.c (ffffffff8127a0ea)
Location: include/linux/kref.h:40
Inline: True
```
```
In fs/fuse/file.c (ffffffff8131629a)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_async_req_send
  - fs/fuse/file.c:fuse_direct_IO
```
```
In fs/fuse/inode.c (ffffffff8131ac4b)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In security/apparmor/apparmorfs.c (ffffffff81375570)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:p_start
```
```
In security/apparmor/capability.c (ffffffff81376f95)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/context.c (ffffffff81377260)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_get_task_label
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_restore_previous_label
```
```
In security/apparmor/domain.c (ffffffff81379bd0)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
Direct callers:
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/policy.c (ffffffff8137f250)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/policy.c:__lookup_replace
  - security/apparmor/policy.c:__add_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:aa_setup_default_label
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_lookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:policy_admin_capable
  - security/apparmor/policy.c:aa_may_open_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
```
```
In security/apparmor/policy_unpack.c (ffffffff8139bd9b)
Location: include/linux/kref.h:40
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/procattr.c (ffffffff81382cf6)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813837c0)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
```
```
In security/apparmor/resource.c (ffffffff813875e7)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81388c71)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff8138996e)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_alloc_proxy
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:40
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:40
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff8139490a)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
```
```
In block/bsg.c (ffffffff813d65d6)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In lib/kobject.c (ffffffff813eb6a6)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/cpu_rmap.c (ffffffff814160d5)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff8141e3a0)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81452cbc)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff8148426e)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/tty/tty_io.c (ffffffff814e0acd)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:get_current_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:tty_find_polling_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
```
In drivers/tty/tty_port.c (ffffffff814eb32a)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff818243ba)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
```
```
In drivers/tty/pty.c (ffffffff814eca39)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff81518419)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8151a4dd)
Location: include/linux/kref.h:40
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff8155f431)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81598fa5)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dma-buf/reservation.c (ffffffff815a5446)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff815b5d74)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
```
```
In drivers/scsi/sr.c (ffffffff815c0f6d)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff815c4d7c)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/hub.c (ffffffff816052d4)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff8160c66d)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8160ff79)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_anchor_urb
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_get_from_anchor
```
```
In drivers/usb/core/message.c (ffffffff81613012)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff816173b4)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/clk/clk.c (ffffffff816e8cab)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_get
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff817f634a)
Location: include/linux/kref.h:40
Inline: True
```
```
In lib/klist.c (ffffffff8181779b)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
**Symbols:**

```
ffffffff8111f4d0-ffffffff8111f509: kref_get (STB_LOCAL)
ffffffff81379bd0-ffffffff81379c09: kref_get (STB_LOCAL)
ffffffff8139bd9b-ffffffff8139bdd1: kref_get (STB_LOCAL)
ffffffff813837c0-ffffffff813837f9: kref_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void kref_get(struct kref *kref);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081518)
Location: include/linux/kref.h:40
Inline: True
```
```
In kernel/pid.c (ffffffff810a193b)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/auto_group.c (ffffffff810c8cc9)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff810e1820)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/time/posix-clock.c (ffffffff81101454)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_open
```
```
In kernel/cgroup.c (ffffffff81120ae0)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
```
```
In kernel/utsname.c (ffffffff81125b12)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81127795)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffff8112a89f)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff81145636)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffffffff8119051e)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/hugetlb.c (ffffffff811f8dd4)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/eventfd.c (ffffffff81281b47)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/inode.c (ffffffff812a6a24)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_fill_super
```
```
In fs/fuse/file.c (ffffffff8134d8cb)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8134f71b)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In security/apparmor/apparmorfs.c (ffffffff813acbf4)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff813afa47)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/context.c (ffffffff813b065f)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_get_task_label
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
```
```
In security/apparmor/domain.c (ffffffff813b7bfe)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/policy.c (ffffffff813bb278)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookup_replace
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_setup_default_label
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813d8bfb)
Location: include/linux/kref.h:40
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/procattr.c (ffffffff813bcf7a)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813be327)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff813c213e)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813c3889)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff813c8e98)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff813cb4d2)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:40
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:40
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff813d055c)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In block/bsg.c (ffffffff8141c006)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In lib/kobject.c (ffffffff81431a06)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/cpu_rmap.c (ffffffff8145df19)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff81466ac9)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149fb87)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff814d2ce1)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/tty/tty_io.c (ffffffff815351e5)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:get_current_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8153c1aa)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8153cb5e)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/pty.c (ffffffff8153d857)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff8156b132)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8156d1cd)
Location: include/linux/kref.h:40
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff815b3a49)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff815ec121)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff815eea85)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dma-buf/reservation.c (ffffffff815fc7e2)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/dma-buf/fence-array.c (ffffffff815fcf59)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/dma-buf/fence-array.c:fence_array_enable_signaling
```
```
In drivers/dma-buf/sync_file.c (ffffffff815fd134)
Location: include/linux/kref.h:40
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8160e77f)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff816196cd)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8161d55c)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/hub.c (ffffffff81667170)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff8166c21d)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81670776)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff816730da)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff816774a1)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff816eccd2)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/clk/clk.c (ffffffff8174d1fb)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_get
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff8186550a)
Location: include/linux/kref.h:40
Inline: True
```
```
In lib/klist.c (ffffffff8189124b)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
**Symbols:**

```
ffffffff81127410-ffffffff8112744a: kref_get (STB_LOCAL)
ffffffff813b29b0-ffffffff813b29ea: kref_get (STB_LOCAL)
ffffffff813d8bfb-ffffffff813d8c31: kref_get (STB_LOCAL)
ffffffff813bdbc0-ffffffff813bdbfa: kref_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void kref_get(struct kref *kref);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81085f62)
Location: include/linux/kref.h:40
Inline: True
```
```
In kernel/pid.c (ffffffff810a69fb)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/auto_group.c (ffffffff810cecd9)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_show_task
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:sched_autogroup_fork
  - kernel/sched/auto_group.c:sched_autogroup_create_attach
  - kernel/sched/auto_group.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff810e816c)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/time/posix-clock.c (ffffffff81109114)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_open
```
```
In kernel/cgroup.c (ffffffff81128fcd)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_pidlist_start
```
```
In kernel/utsname.c (ffffffff8112f522)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8113131c)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffff811345bf)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff8114f496)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffffffff8119f3de)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/hugetlb.c (ffffffff812099c4)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/eventfd.c (ffffffff81295677)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/inode.c (ffffffff812bc304)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_fill_super
```
```
In fs/fuse/file.c (ffffffff813631d7)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff81365035)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In security/apparmor/apparmorfs.c (ffffffff813c3a04)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:ns_rmdir_op
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:rawdata_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff813c6bc7)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/context.c (ffffffff813c77df)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_get_task_label
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
```
```
In security/apparmor/domain.c (ffffffff813cf047)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/policy.c (ffffffff813d263f)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookup_replace
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_setup_default_label
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_null_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813f073f)
Location: include/linux/kref.h:40
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/procattr.c (ffffffff813d43aa)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813d57a7)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff813d95de)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813dae19)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/label.c (ffffffff813e04b4)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff813e2b52)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:40
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:40
Inline: True
```
```
In security/apparmor/policy_ns.c (ffffffff813e7c5c)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
```
```
In block/bsg.c (ffffffff81437149)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In lib/kobject.c (ffffffff8144dc76)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In lib/cpu_rmap.c (ffffffff8147c949)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff81485db9)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c1707)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff814f51b2)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/clk/clk.c (ffffffff81535a6b)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_get
```
```
In drivers/tty/tty_io.c (ffffffff8156190a)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:get_current_tty
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8156880a)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff815691ae)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/pty.c (ffffffff81569ea7)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff815978a2)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8159993d)
Location: include/linux/kref.h:40
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff815e2dc9)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff81618d15)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8161bbc5)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8162a4c9)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/reservation.c (ffffffff8162ab72)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8162bc8f)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8162c412)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8163e01f)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff8164a35d)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8164e15e)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/hub.c (ffffffff81694e90)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81699f1d)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8169e426)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff816a0d8a)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff816a5181)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8171dd88)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff81897bd7)
Location: include/linux/kref.h:40
Inline: True
```
```
In lib/klist.c (ffffffff818c59db)
Location: include/linux/kref.h:40
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
**Symbols:**

```
ffffffff81130fc0-ffffffff81130ffa: kref_get (STB_LOCAL)
ffffffff813c9b70-ffffffff813c9baa: kref_get (STB_LOCAL)
ffffffff813f073f-ffffffff813f0775: kref_get (STB_LOCAL)
ffffffff813d5040-ffffffff813d507a: kref_get (STB_LOCAL)
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
In kernel/fork.c (ffffffff8108298e)
Location: include/linux/kref.h:45
Inline: True
```
```
In kernel/pid.c (ffffffff810a3967)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (ffffffff810cdf89)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff810e75c2)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/time/posix-clock.c (ffffffff8110b00e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_open
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112a4b2)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/utsname.c (ffffffff81130d32)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8113267c)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffff81135a6b)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff811510f0)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffffffff811a5e3c)
Location: include/linux/kref.h:45
Inline: True
```
```
In mm/backing-dev.c (ffffffff811e14d9)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffff81215249)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffff8125355c)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super
```
```
In fs/block_dev.c (ffffffff81292229)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffffffff812a297c)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/inode.c (ffffffff812c96c0)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_fill_super
```
```
In fs/configfs/item.c (ffffffff812e1d4d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff81377c7a)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff81379744)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In security/apparmor/apparmorfs.c (ffffffff813d9eb6)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff813dca6e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/context.c (ffffffff813dcf98)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_get_task_label
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
```
```
In security/apparmor/domain.c (ffffffff813e2d22)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff813e527e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookup_replace
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff813e5f84)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff813e72b2)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff813e9c69)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff813ea719)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813ebccf)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (ffffffff813ec5a6)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff813ef75b)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff813f124d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:45
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:45
Inline: True
```
```
In block/bsg.c (ffffffff814444eb)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In lib/cpu_rmap.c (ffffffff81485cf1)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff8148fc95)
Location: include/linux/kref.h:45
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814cbd36)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff8150379f)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
```
```
In drivers/clk/clk.c (ffffffff81548e3d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8156197d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (0)
Location: include/linux/kref.h:45
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff815752e5)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8157baea)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8157c73e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8157ccb9)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff8157e052)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff815ab8b9)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff815ad93d)
Location: include/linux/kref.h:45
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff815f7c74)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:assign_firmware_buf
```
```
In drivers/nvdimm/core.c (ffffffff8162ce66)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8162fcb9)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81640031)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/reservation.c (ffffffff81640307)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81640bbd)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81641a12)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81652b9f)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff8165e732)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff81662a2f)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/hub.c (ffffffff816aa2de)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff816aeeb1)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff816b35c6)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff816b5e7d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff816ba519)
Location: include/linux/kref.h:45
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81735f00)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff818bdfaf)
Location: include/linux/kref.h:45
Inline: True
```
```
In lib/klist.c (ffffffff818eda35)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff818edea3)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void kref_get(struct kref *kref);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810897ba)
Location: include/linux/kref.h:45
Inline: True
```
```
In kernel/pid.c (ffffffff810aa12b)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (ffffffff810d5859)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff810ef936)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/time/posix-clock.c (ffffffff81116171)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_open
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8113712c)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/utsname.c (ffffffff8113dc82)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8113f779)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
Direct callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffff811427ab)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff8115e680)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffffffff811b9a2c)
Location: include/linux/kref.h:45
Inline: True
```
```
In mm/backing-dev.c (ffffffff811f74f9)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffff8122fdf8)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffff8127565c)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super
```
```
In fs/block_dev.c (ffffffff812b4ffb)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffffffff812c5c2c)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/inode.c (ffffffff812edf40)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_fill_super
```
```
In fs/configfs/item.c (ffffffff8130660d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff8139c9fc)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8139e5e4)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In security/apparmor/apparmorfs.c (ffffffff81400d77)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_readlink
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff814034c2)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/context.c (ffffffff81403b95)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_hat
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_get_task_label
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
  - security/apparmor/context.c:aa_dup_task_context
```
```
In security/apparmor/domain.c (ffffffff81409b8a)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
```
```
In security/apparmor/policy.c (ffffffff8140c44e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8140da5a)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/procattr.c (ffffffff8140e4b2)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8140fd09)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff814121b3)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814137a9)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (ffffffff81413f36)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff81417827)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff8141927d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:45
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:45
Inline: True
```
```
In block/bsg.c (ffffffff8147140b)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In lib/cpu_rmap.c (ffffffff814c1d99)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff814cbe45)
Location: include/linux/kref.h:45
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8150c307)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff81545bfb)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
```
```
In drivers/clk/clk.c (ffffffff815ac3a2)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815c5fa8)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (0)
Location: include/linux/kref.h:45
Inline: False
```
```
In drivers/tty/tty_io.c (ffffffff815d9c9a)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff815e047a)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff815e123e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff815e1969)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff815e2fa2)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff8161225c)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8161433d)
Location: include/linux/kref.h:45
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff8165fc18)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:assign_firmware_buf
```
```
In drivers/nvdimm/core.c (ffffffff816955f3)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816984c9)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff816a88d5)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/reservation.c (ffffffff816a8cb7)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff816a9b1d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816aabf0)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816bbfbf)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff816c8239)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff816cc0b3)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/hub.c (ffffffff8171572e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff8171a4c1)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8171eea6)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff8172170d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff81725ee9)
Location: include/linux/kref.h:45
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817a7d32)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/opp/core.c (ffffffff817d4e48)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff819410df)
Location: include/linux/kref.h:45
Inline: True
```
```
In lib/klist.c (ffffffff81973c6f)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff81974156)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
**Symbols:**

```
ffffffff8113fd85-ffffffff8113fd94: kref_get (STB_LOCAL)
ffffffff81405b50-ffffffff81405b5f: kref_get (STB_LOCAL)
ffffffff8140c850-ffffffff8140c85f: kref_get (STB_LOCAL)
ffffffff8140e980-ffffffff8140e98f: kref_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void kref_get(struct kref *kref);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108d176)
Location: include/linux/kref.h:45
Inline: True
```
```
In kernel/pid.c (ffffffff810b0d59)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (ffffffff810dd809)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff810f7d3e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/time/posix-clock.c (ffffffff81122a21)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_open
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81145928)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/utsname.c (ffffffff8114c622)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8114dfc9)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffff8115118a)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff8116d54d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffffffff811d8dbc)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/backing-dev.c (ffffffff81218909)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffff81252246)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffff8129bf2c)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super
```
```
In fs/block_dev.c (ffffffff812dd2a0)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffffffff812eee5c)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/inode.c (ffffffff8131afb0)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_fill_super
```
```
In fs/configfs/item.c (ffffffff8133460d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff813cbe1f)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_send_write
  - fs/fuse/file.c:fuse_send_read
```
```
In fs/fuse/inode.c (ffffffff813cd995)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff813d5f32)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In security/apparmor/apparmorfs.c (ffffffff814320ae)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff8143461d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (ffffffff81434c3e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8143b12c)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
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
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff8143dd8e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8143e70a)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/procattr.c (ffffffff81440036)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814422f6)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In security/apparmor/resource.c (ffffffff814442d7)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814459a2)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (ffffffff814462a0)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff81449c55)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff8144b67f)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:45
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:45
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff814f2cc9)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff814fcdc5)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81541156)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff8157c1d5)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
```
```
In drivers/clk/clk.c (ffffffff815e42f1)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815fe748)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff8160eaa4)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_from_lookup
```
```
In drivers/tty/tty_io.c (ffffffff81612cf1)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8161973a)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8161a4ce)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8161ac29)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff8161c25d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff8164bbd3)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8164e07d)
Location: include/linux/kref.h:45
Inline: True
```
```
In drivers/base/core.c (ffffffff8167ef9a)
Location: include/linux/kref.h:45
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff8169a902)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff816d16b3)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816d4675)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff816e4a50)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/reservation.c (ffffffff816e4d37)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff816e604d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e70da)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816f847f)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff817042d9)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff817089e5)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8170b325)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8173b00a)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/usb/core/hub.c (ffffffff8175453e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff817592cd)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8175db26)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff8176043a)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff81764cab)
Location: include/linux/kref.h:45
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817ef75c)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/opp/core.c (ffffffff8181dbf8)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In lib/klist.c (ffffffff819d03ff)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff819d0676)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
**Symbols:**

```
ffffffff8143e1a0-ffffffff8143e1af: kref_get (STB_LOCAL)
ffffffff81440580-ffffffff8144058f: kref_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void kref_get(struct kref *kref);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81094eaa)
Location: include/linux/kref.h:45
Inline: True
```
```
In kernel/pid.c (ffffffff810b9e50)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (ffffffff810e7f79)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff8110348e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/time/posix-clock.c (ffffffff8112e101)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_open
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811514e8)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/utsname.c (ffffffff81159242)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8115ad79)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffff8115de3e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff8117af8d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffffffff811e92b4)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/backing-dev.c (ffffffff8122b669)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffff812664b6)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffff812b0fbc)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super
```
```
In fs/block_dev.c (ffffffff812f2751)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffffffff813037ec)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/inode.c (ffffffff81332030)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_fill_super
```
```
In fs/configfs/item.c (ffffffff8134b92d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff813e4ee2)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff813e6d75)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff813f05f2)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In security/apparmor/apparmorfs.c (ffffffff8144de60)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff81451171)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (ffffffff81451825)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81458197)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
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
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff8145abee)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8145b5da)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/procattr.c (ffffffff8145cf12)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8145f228)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In security/apparmor/resource.c (ffffffff81461392)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814628bd)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (ffffffff814631c0)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff81466ad4)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff814685ef)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:45
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:45
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff81506ff9)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff81511825)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815584b6)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff81593895)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
```
```
In drivers/clk/clk.c (ffffffff815fe6e1)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81619818)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff8162b294)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_from_lookup
```
```
In drivers/tty/tty_io.c (ffffffff8162fd91)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff816369aa)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8163774e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81637e99)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff816394dd)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff81669de3)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8166c1fd)
Location: include/linux/kref.h:45
Inline: True
```
```
In drivers/base/core.c (ffffffff8169f3cb)
Location: include/linux/kref.h:45
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff816bb36e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff816f2d43)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5fd5)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8170755d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81707fb0)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/reservation.c (ffffffff81708e77)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff817093dd)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8170a46a)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8171ad6f)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff81727099)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8172aed5)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8172d7a5)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8175e5ea)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/usb/core/hub.c (ffffffff8177899e)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff8177d83d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81782206)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff81784a9d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff8178932b)
Location: include/linux/kref.h:45
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff81808e05)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8181b64d)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/opp/core.c (ffffffff818498e8)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/nvmem/core.c (ffffffff81886a93)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_get_from_lookup
```
```
In lib/klist.c (ffffffff81a0995f)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff81a09bd6)
Location: include/linux/kref.h:45
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
**Symbols:**

```
ffffffff8145aed0-ffffffff8145aedf: kref_get (STB_LOCAL)
ffffffff8145d460-ffffffff8145d46f: kref_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void kref_get(struct kref *kref);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81099507)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (ffffffff810bfd3e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (ffffffff810eeefa)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff810f75a7)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110be77)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/time/posix-clock.c (ffffffff81138b11)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_open
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115c7b5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/utsname.c (ffffffff81165982)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8116742f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffff8116a16e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff81187dad)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffffffff812025d2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/backing-dev.c (ffffffff8123b2ce)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffff81281494)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/hmm.c (ffffffff812c2ea1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hmm.c:hmm_range_register
```
```
In fs/super.c (ffffffff812cd95c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super
```
```
In fs/block_dev.c (ffffffff81314190)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffffffff81324d78)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/root.c (ffffffff8135a349)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/configfs/item.c (ffffffff813742ed)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff81410819)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff81412da5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff8141c912)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In security/apparmor/apparmorfs.c (ffffffff8147b7d0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff8147ec2a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (ffffffff8147f29c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81485ab0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
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
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
```
```
In security/apparmor/policy.c (ffffffff81488220)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81488b2a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/procattr.c (ffffffff8148a4c1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8148c6a9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In security/apparmor/resource.c (ffffffff8148e67d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8148fc27)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (ffffffff8149047b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff81491a5a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff81495673)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff81535215)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff8153ff0a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815884c5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff815c47d7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/clk/clk.c (ffffffff81630cf8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8164d53a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff8165f21d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81663c18)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8166abfa)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8166ba1f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8166c138)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff8166d7cd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff8169f402)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff816a1dce)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816d366d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/base/core.c (ffffffff816d7a1b)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff816f5b69)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff8172c1b4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172f795)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81740228)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
```
In drivers/dma-buf/dma-fence.c (ffffffff817427bd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8174324c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81743809)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/reservation.c (ffffffff8174440f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/reservation.c:reservation_object_add_excl_fence
  - drivers/dma-buf/reservation.c:reservation_object_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81744b9e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81745ca4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8175643f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff817627cb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff817665ca)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81768f95)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8179bbf4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/usb/core/hub.c (ffffffff817b680e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff817bbbf1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817c06a9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff817c2c67)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff817c77bd)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff8184aa75)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185d88a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
  - drivers/watchdog/watchdog_dev.c:watchdog_open
```
```
In drivers/opp/core.c (ffffffff8188c6f5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/nvmem/core.c (ffffffff818d0e9c)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/klist.c (ffffffff81a792b1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff81a79466)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
**Symbols:**

```
ffffffff81488500-ffffffff8148850a: kref_get (STB_LOCAL)
ffffffff8148a9e0-ffffffff8148a9ea: kref_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void kref_get(struct kref *kref);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109fb01)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (ffffffff810c610e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (ffffffff810fab8a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff81103347)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81118277)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81167f61)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/utsname.c (ffffffff81171842)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff811732ef)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffff8117600e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff81193ced)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffffffff8120f402)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/backing-dev.c (ffffffff812494c5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffff81290f94)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffff812df380)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff81327964)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffffffff81337b08)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/root.c (ffffffff81372579)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/configfs/item.c (ffffffff8138c56d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff8142a429)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8142ca8a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff81436762)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In security/apparmor/apparmorfs.c (ffffffff814954a0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff8149892a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (ffffffff81498f9c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8149f99b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
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
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff814a20d0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814a29da)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/procattr.c (ffffffff814a4381)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814a6569)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In security/apparmor/resource.c (ffffffff814a853d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814a9ae7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (ffffffff814aa33b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff814ab98a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff814af5a3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff81556025)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff81560ca1)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a9ec5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff815e5a17)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/clk/clk.c (ffffffff81652ab8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8166fa37)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff81681940)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81686288)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8168d2ca)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8168e08f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8168e7a8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff8168fe3d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff816c2192)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff816c4b2e)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816f754d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/base/core.c (ffffffff816fbd78)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81719f69)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff81750404)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81753c55)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81764428)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8176688d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff817671dc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81767809)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8176859f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81768d4e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81769df4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8177a6df)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff817867bb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8178a5ba)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8178cf85)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817bf6a4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff817d1d90)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d64a2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
```
```
In drivers/usb/core/hub.c (ffffffff817e6f2e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff817ec421)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817f1029)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff817f35e7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff817f82dd)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff8187c295)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_register
```
```
In drivers/opp/core.c (ffffffff818be865)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff818f7341)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (ffffffff819032a3)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/klist.c (ffffffff81ab0651)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff81ab07c6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
**Symbols:**

```
ffffffff814a23b0-ffffffff814a23ba: kref_get (STB_LOCAL)
ffffffff814a48a0-ffffffff814a48aa: kref_get (STB_LOCAL)
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
In kernel/fork.c (ffffffff810a6b9f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (ffffffff810cdf48)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff810d6205)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/nsproxy.c:validate_nsset
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/sched/autogroup.c (ffffffff8110505a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff8110d453)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81123ab2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/time/namespace.c (ffffffff8115a28f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_for_children_get
  - kernel/time/namespace.c:timens_get
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81179ad8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create
```
```
In kernel/utsname.c (ffffffff81183620)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81185405)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit.c (ffffffff81188590)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff811a8a70)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/bpf/task_iter.c (ffffffff81216328)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:init_seq_pidns
```
```
In kernel/events/core.c (ffffffff8123a5e7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/watch_queue.c (ffffffff8124c671)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/backing-dev.c (ffffffff812777a2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffff812c3ecf)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffff81316766)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff81360c65)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffffffff81371928)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/root.c (ffffffff813ba83c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/configfs/item.c (ffffffff813d7885)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff8147a55f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8147d4e6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff814867e6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In security/apparmor/apparmorfs.c (ffffffff814ed52b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff814f0bf2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff814f1521)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff814f904b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff814fc2d0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:update_to_newest_parent
  - security/apparmor/policy.c:update_to_newest_parent
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814fe505)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff814ff1e3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff82d06795)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff815057c6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8150734c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff81507fc8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_find_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8150a3b5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff8150e7dc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff815df675)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In lib/klist.c (ffffffff815ea6e7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff815eaa64)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In drivers/pinctrl/core.c (ffffffff81603601)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81652ce9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff81690ca1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/clk/clk.c (ffffffff817025f9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8172023e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff817328ae)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81737df3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8173fa61)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8174031f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81740ada)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff817424ad)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff817748b3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:find_port_by_devt
```
```
In drivers/char/hw_random/core.c (ffffffff81779eba)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_unregister
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
  - drivers/char/hw_random/core.c:hwrng_attr_current_show
  - drivers/char/hw_random/core.c:hwrng_attr_current_store
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/lightnvm/core.c (ffffffff817b0379)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/base/core.c (ffffffff817b5542)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d5dba)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff8180ee6a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818126b5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81824580)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818270ed)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81827731)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81827e59)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81828f2e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8182ad38)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182bdee)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8183d7d6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff8184ab42)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8184ee01)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81858db5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81888995)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff8189ceb4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_set_container
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_name
  - drivers/vfio/vfio.c:vfio_device_get_from_name
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a3585)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
```
```
In drivers/usb/core/hub.c (ffffffff818b47ee)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff818bbfbd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff818c0969)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff818c3117)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff818c8487)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/file.c:init_usb_class
```
```
In drivers/opp/core.c (ffffffff81990f9f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819cd480)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (ffffffff819da4f2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810659b8)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/fork.c (ffffffff810a26bb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/autogroup.c (ffffffff811036da)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff8110a492)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8111f902)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/audit.c (ffffffff811858e0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff811a6170)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/watch_queue.c (ffffffff81256ab1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/backing-dev.c (ffffffff81281e52)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffff812cf96f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffff81322197)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff8136ded1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffffffff8137f625)
Location: include/linux/kref.h:43
Inline: True
```
```
In fs/configfs/item.c (ffffffff813e95e5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff81495255)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff81499bcd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
```
```
In security/apparmor/apparmorfs.c (ffffffff8150abab)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff8150de72)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff8150e7c1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81516190)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81519540)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8151a4fa)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8151c423)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff82ff3b35)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff815228f6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff815243fc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff81524fc8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff81527224)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff8152b64c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff815fce15)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In lib/klist.c (ffffffff8160f027)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff8160f384)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In drivers/pinctrl/core.c (ffffffff81628511)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816756a9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff816ae9d1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/clk/clk.c (ffffffff8171a594)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173d19e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff8174ea6e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff817541b3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8175b8e1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8175c24f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8175ca0a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff8175e34d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff8178f613)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:find_port_by_devt
```
```
In drivers/char/hw_random/core.c (ffffffff817944bb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
```
In drivers/lightnvm/core.c (ffffffff817c4f39)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/base/core.c (ffffffff817c9d02)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ea7ce)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff8181ddda)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81821905)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81834aee)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81837b8d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff818381c1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81838a39)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8183958e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8183b8e8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183ce4e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8184dfd6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff8185ac9f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8185f781)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81869015)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81896c25)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff818abae4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_set_container
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_name
  - drivers/vfio/vfio.c:vfio_device_get_from_name
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2235)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
```
```
In drivers/usb/core/hub.c (ffffffff818c314e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff818c8d7d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff818cbd45)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff818cf423)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff818d3637)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/file.c:init_usb_class
```
```
In drivers/opp/core.c (ffffffff8199318f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819cccd0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (ffffffff819d9382)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066335)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/fork.c (ffffffff810a33a5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/autogroup.c (ffffffff811059da)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff8110d03c)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8111fbc2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/audit.c (ffffffff811868d0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff811a70a0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/watch_queue.c (ffffffff8125af51)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/backing-dev.c (ffffffff81286e12)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffff812d66cf)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffff81328257)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff8137486b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffffffff813862a5)
Location: include/linux/kref.h:43
Inline: True
```
```
In fs/configfs/item.c (ffffffff813f0145)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff8149a2ad)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8149edfd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
```
```
In security/apparmor/apparmorfs.c (ffffffff8151132b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff81514823)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff815151c1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8151cb0d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8151fe50)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff81520dfa)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81522c02)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff831fe652)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81528ad6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8152a5dc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff8152b178)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8152cba4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff81531979)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff815dfb85)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In lib/klist.c (ffffffff815f27a7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff815f2ac4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In drivers/pinctrl/core.c (ffffffff8160bff1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81657bd9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff81690ff0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/clk/clk.c (ffffffff81700a49)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81720d0e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff817326ee)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff8173839a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8173f781)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff817400ef)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8174089a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff8174213d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff81774ec9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8177718b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
```
In drivers/lightnvm/core.c (ffffffff817a7de4)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/base/core.c (ffffffff817ad51e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ceec6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff81801049)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81804c25)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81817cbe)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181a8bd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8181b49e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8181bcf9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c81e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8181ec08)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8181fe2e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81831488)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff8183dc8f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8184277b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8184ba45)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff818790d6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff8188ea64)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_set_container
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818956da)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
```
```
In drivers/usb/core/hub.c (ffffffff818a621e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff818ac32d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff818af365)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff818b2a53)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff818b6a9d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/opp/core.c (ffffffff81977a7f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819b1e80)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (ffffffff819bf452)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070455)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/fork.c (ffffffff810b4b32)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/autogroup.c (ffffffff8112366a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff81140062)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/audit.c (ffffffff811aed00)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff811d0900)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/watch_queue.c (ffffffff81296d51)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/backing-dev.c (ffffffff812c63c2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffff8131c949)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffff8137582e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/eventfd.c (ffffffff813d3575)
Location: include/linux/kref.h:43
Inline: True
```
```
In fs/configfs/item.c (ffffffff81442035)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff814f1d33)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff814f64d2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
```
```
In security/apparmor/apparmorfs.c (ffffffff8156ef2b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff815726f9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff81573171)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8157abde)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8157dff0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8157ef9a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81580e72)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff832e5964)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff81586dc6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8158897c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff81589518)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8158af94)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff8158fdcc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff8164b695)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In lib/klist.c (ffffffff8165f687)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff8165fca4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In drivers/pinctrl/core.c (ffffffff8167acfe)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c9c08)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff81706a68)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/clk/clk.c (ffffffff8177b259)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179fb2e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff817b3084)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff817b8e3a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff817bffe1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff817c088f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff817c12fa)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff817c2bfd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff817fac09)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff817fcf1b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
```
In drivers/base/core.c (ffffffff81836885)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81859647)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff8188b459)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188f335)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff818a230e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
```
```
In drivers/dma-buf/dma-buf.c (ffffffff818a4186)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_excl
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a4d5d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff818a590e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff818a6189)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a6c5e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff818a9298)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa4ee)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff818bd4d8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff818ca74f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff818cf88b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff818d8f15)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81909f26)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff819220b4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_set_container
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/usb/core/hub.c (ffffffff8193b07e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff8194137d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff819444b5)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81947d56)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff8194c41d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/opp/core.c (ffffffff81a2097f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81a605e0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (ffffffff81a6eae2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107e64d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In kernel/fork.c (ffffffff810caffe)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:vm_area_dup
```
```
In kernel/sched/build_utility.c (ffffffff8114d242)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff81163966)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/audit.c (ffffffff811e0f3c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff81204d50)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/watch_queue.c (ffffffff812ece69)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/backing-dev.c (ffffffff813243cd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
```
```
In mm/madvise.c (ffffffff81378302)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
```
```
In mm/hugetlb.c (ffffffff81388b90)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffff813f4d5e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/eventfd.c (ffffffff8145cb55)
Location: include/linux/kref.h:43
Inline: True
```
```
In fs/configfs/item.c (ffffffff814bdd01)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff81581794)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff815862f0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
```
```
In security/apparmor/apparmorfs.c (ffffffff8160d5d1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff8160f6e6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff81610461)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81618a91)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8161c75e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8161d44a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff81620010)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8349c6d0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff816271be)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81629036)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff81629d6a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_unconfined
  - security/apparmor/policy_ns.c:alloc_unconfined
```
```
In security/apparmor/label.c (ffffffff8162c4e2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff81630d03)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff81762125)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In lib/klist.c (ffffffff81778dd7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff817797d3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
```
In drivers/pinctrl/core.c (ffffffff817963bb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817efeeb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff81834c05)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_submit_query
```
```
In drivers/clk/clk.c (ffffffff818b1a51)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d95e2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff818eeadb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff818f4c97)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff818fc71f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff818fd0ee)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff818fdcb7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff818ffc2d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff81939ba1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8193bdf6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
```
In drivers/base/core.c (ffffffff81978894)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff819a013c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff819d47b7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d8885)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff819ebb18)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-buf.c (ffffffff819ed438)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819ee70b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff819ef833)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff819f013a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f145e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff819f3dd4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_ioctl_fence_info
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4cde)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81a09659)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sg.c (ffffffff81a1e0a1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81a2a0a5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81a5e1f5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff81a76a33)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_set_container
```
```
In drivers/usb/core/hub.c (ffffffff81a92c9d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81a99aed)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81a9cae5)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81aa07e7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff81aa4f04)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/opp/core.c (ffffffff81b895c3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_bw_floor
  - drivers/opp/core.c:dev_pm_opp_find_bw_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81bd0b00)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (ffffffff81bdfb00)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108fb7d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In kernel/fork.c (ffffffff810e85ab)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:vm_area_dup
```
```
In kernel/sched/build_utility.c (ffffffff8117c2e2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff81197636)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/audit.c (ffffffff81226d7c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff8124cba0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/watch_queue.c (ffffffff813571d9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/backing-dev.c (ffffffff81398ced)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
```
```
In mm/madvise.c (ffffffff813f5d9c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
```
```
In mm/hugetlb.c (ffffffff81406c1b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/memory-tiers.c (ffffffff814376e7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/memory-tiers.c:init_node_memory_type
  - mm/memory-tiers.c:set_node_memory_tier
```
```
In fs/super.c (ffffffff8147deae)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/eventfd.c (ffffffff814ec285)
Location: include/linux/kref.h:43
Inline: True
```
```
In fs/configfs/item.c (ffffffff81555a61)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/hugetlbfs/inode.c (ffffffff815f67f6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
```
In fs/fuse/file.c (ffffffff816275f4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8162c55e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
```
```
In security/apparmor/apparmorfs.c (ffffffff816bf551)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/audit.c (ffffffff816c1b7b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/capability.c (ffffffff816c20e4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff816c2ec1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff816cbd6d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff816cf9fe)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff816d07ea)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff816d350d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff83ed3c09)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff816db1d2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff816dd8fb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff83ed3e6d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_find_ns
```
```
In security/apparmor/label.c (ffffffff816e0f82)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff816e5a3f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/notify.c (ffffffff816eadfb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_register_listener_proxy
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In lib/cpu_rmap.c (ffffffff81890e45)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff818abadb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8191809b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff819687c5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_submit_query
```
```
In drivers/clk/clk.c (ffffffff819fe051)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2c0a2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff81a4673b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81a4d2c2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff81a55d5f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81a567a6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/tty/pty.c (ffffffff81a5965d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff81a99e31)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff81a9c63a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
```
In drivers/base/core.c (ffffffff81ae5171)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b11c9c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81b4f057)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b537c5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81b686e4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81b6a498)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6bddb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81b6ce23)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81b6d7ba)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81b6dedb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6f0be)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81b710b6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b7218e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b83963)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81b88b08)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sg.c (ffffffff81b9f3d1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81bacce5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81be8f35)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c14e4d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81c1dc7d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81c21ad5)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81c25d22)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff81c2b8a4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/opp/core.c (ffffffff81d28dd3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_opp_table_find_key
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/nvmem/core.c (ffffffff81d8b26f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In lib/klist.c (ffffffff82021be7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff82022763)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092a8d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In kernel/fork.c (ffffffff810f420a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:vm_area_dup
```
```
In kernel/sched/build_utility.c (ffffffff8118cf90)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff811a91ed)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/audit.c (ffffffff8123d39c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff81263f20)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/watch_queue.c (ffffffff81388a59)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/backing-dev.c (ffffffff813cbc4d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
```
```
In mm/madvise.c (ffffffff814289da)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
```
```
In mm/hugetlb.c (ffffffff8143a27e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/memory-tiers.c (ffffffff8146d3a7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/memory-tiers.c:init_node_memory_type
  - mm/memory-tiers.c:set_node_memory_tier
```
```
In fs/super.c (ffffffff814b2c3b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/eventfd.c (ffffffff81523445)
Location: include/linux/kref.h:43
Inline: True
```
```
In fs/configfs/item.c (ffffffff8158d801)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e8b9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
```
In fs/fuse/file.c (ffffffff8165f9b7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8166478c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
```
```
In security/apparmor/apparmorfs.c (ffffffff816f8061)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/audit.c (ffffffff816fa9ed)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
  - security/apparmor/audit.c:aa_audit_cache_find
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/capability.c (ffffffff816facfb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff816fba71)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8170454a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8170861e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8170966a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8170c3dd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff836f8a6e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_current_getsecid_subj
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff817148c2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81716f1b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff836f8fad)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_find_ns
```
```
In security/apparmor/label.c (ffffffff8171a582)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff8171f150)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/notify.c (ffffffff817250ca)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_clone_ruleset
  - security/apparmor/notify.c:aa_clone_ruleset
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_register_listener_proxy
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In lib/cpu_rmap.c (ffffffff818d3935)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff818eea1b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195b6bf)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff819aeda5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_submit_query
```
```
In drivers/clk/clk.c (ffffffff81a46cd1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a75842)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff81a908e3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81a975c0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff81aa033f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81aa0d86)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/tty/pty.c (ffffffff81aa3c8d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff81ae56a1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff81ae7f9a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
```
In drivers/base/core.c (ffffffff81b334c4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5ff8c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81ba24a7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba6cc5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81bbbbfd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81bbd8e8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf49b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81bc055b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81bc0fe8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81bc16d1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc298e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81bc48e9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc5b9e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd76c3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bdc9e8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sg.c (ffffffff81bf5aec)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81c03e95)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81c41365)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c7bc4d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81c84b7d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81c88a55)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81c8ccc5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff81c92854)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/opp/core.c (ffffffff81d91f73)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_opp_table_find_key
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/nvmem/core.c (ffffffff81df99ef)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In lib/klist.c (ffffffff820a1c27)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff820a27d3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099ecc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
```
```
In kernel/fork.c (ffffffff810fd5d4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:vm_area_dup
```
```
In kernel/sched/build_utility.c (ffffffff8119b940)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_show_task
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_fork
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_move_group
```
```
In kernel/irq/manage.c (ffffffff811b8d4d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/audit.c (ffffffff812572cc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff8127dd10)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
  - kernel/relay.c:relay_create_buf
```
```
In kernel/watch_queue.c (ffffffff813b24b9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/watch_queue.c:get_watch_queue
  - kernel/watch_queue.c:add_watch_to_object
  - kernel/watch_queue.c:add_watch_to_object
```
```
In mm/backing-dev.c (ffffffff813f65bd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
```
```
In mm/madvise.c (ffffffff8146220a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_update_vma
```
```
In mm/hugetlb.c (ffffffff8147488e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In mm/memory-tiers.c (ffffffff8149c517)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/memory-tiers.c:init_node_memory_type
  - mm/memory-tiers.c:set_node_memory_tier
```
```
In fs/super.c (ffffffff814e40e3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:setup_bdev_super
```
```
In fs/eventfd.c (ffffffff81557b75)
Location: include/linux/kref.h:43
Inline: True
```
```
In fs/configfs/item.c (ffffffff815c6541)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/hugetlbfs/inode.c (ffffffff81667d89)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
```
In fs/fuse/file.c (ffffffff81699826)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8169ea1c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
```
```
In fs/tracefs/event_inode.c (ffffffff816abedf)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
  - fs/tracefs/event_inode.c:eventfs_root_lookup
  - fs/tracefs/event_inode.c:eventfs_root_lookup
```
```
In security/apparmor/apparmorfs.c (ffffffff81734dd4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:policy_get_link
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir_entries
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/audit.c (ffffffff817375fd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_audit_cache_insert
  - security/apparmor/audit.c:aa_audit_cache_find
  - security/apparmor/audit.c:aa_dup_audit_data
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/capability.c (ffffffff8173790b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:audit_caps
```
```
In security/apparmor/task.c (ffffffff817390f9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81741db3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff817460ae)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:aa_new_learning_profile
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_alloc_null
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8174718a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffff8174a123)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8392c05e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:aa_setup_dfa_engine
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getselfattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffff817532d5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81755a7e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:aa_file_perm
```
```
In security/apparmor/policy_ns.c (ffffffff8392c3bd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_alloc_root_ns
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
```
```
In security/apparmor/label.c (ffffffff81759032)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:__label_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:label_merge_insert
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
  - security/apparmor/label.c:aa_get_current_ns
```
```
In security/apparmor/mount.c (ffffffff8175db80)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_inet.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/notify.c (ffffffff8176624b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_clone_ruleset
  - security/apparmor/notify.c:aa_clone_ruleset
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_do_notification
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_register_listener_proxy
  - security/apparmor/notify.c:aa_get_current_ns
```
```
In lib/cpu_rmap.c (ffffffff81925a44)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff819361db)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a4ca7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff819f9254)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_submit_query
```
```
In drivers/clk/clk.c (ffffffff81a92788)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac7a32)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff81ae3355)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81ae9fff)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff81af2d8f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81af37e6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/tty/pty.c (ffffffff81af665b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff81b38a31)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff81b3b40a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_register
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
```
In drivers/base/core.c (ffffffff81b8ae03)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb399c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81bf6667)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfaf75)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81c10386)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c12038)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll_add_cb
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c13c1b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81c14cdb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff81c15768)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_set_deadline
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_find_seqno
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81c15e5c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
  - drivers/dma-buf/dma-fence-unwrap.c:dma_fence_unwrap_first
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c1711e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_replace_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff81c19099)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a5ad)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2c363)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c31718)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sg.c (ffffffff81c4b48b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81c59675)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/gpu/drm/drm_auth.c (ffffffff81c7e5a4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_auth.c:drm_file_get_master
  - drivers/gpu/drm/drm_auth.c:drm_master_open
  - drivers/gpu/drm/drm_auth.c:drm_setmaster_ioctl
  - drivers/gpu/drm/drm_auth.c:drm_new_set_master
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8c574)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_minor_acquire
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9cfe3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap_obj
  - drivers/gpu/drm/drm_gem.c:drm_gem_vm_open
  - drivers/gpu/drm/drm_gem.c:drm_gem_open_ioctl
  - drivers/gpu/drm/drm_gem.c:objects_lookup
  - drivers/gpu/drm/drm_gem.c:drm_gem_handle_create_tail
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca38ca)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81cac9f6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_mmap
  - drivers/gpu/drm/drm_prime.c:drm_gem_dmabuf_export
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb206b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_query_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_fd
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_handle
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_replace_fence
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_add_point
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fence_add_wait
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc2f42)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit_hw_done
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit
```
```
In drivers/gpu/drm/drm_gem_atomic_helper.c (ffffffff81ccb091)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81cf69d5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d3089d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81d3957d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffff81d3d4a5)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81d417e6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/opp/core.c (ffffffff81e498a3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_opp_table_find_key
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/nvmem/core.c (ffffffff81eb02ff)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cae4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_get
```
```
In lib/klist.c (ffffffff82179ca7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff8217a853)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
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
In virt/kvm/arm/vgic/vgic.c (ffff8000100dc40c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:vgic_queue_irq_unlock
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100e9ea0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-its.c:vgic_its_resolve_lpi
```
```
In kernel/fork.c (ffff8000100f4078)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (ffff800010124750)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (ffff80001015f5fc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffff800010168448)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/irq/manage.c (ffff80001017aab0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101daa8c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/utsname.c (ffff8000101e545c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffff8000101e7180)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffff8000101eb078)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffff80001020b014)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffff8000102973b8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/backing-dev.c (ffff8000102deb54)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffff80001032e3cc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffff800010386018)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffff8000103e286c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffff8000103f5d6c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/root.c (ffff80001043c9ac)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/configfs/item.c (ffff80001045e0b0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffff80001050e420)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffff80001051243c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffff80001051cc3c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In security/apparmor/apparmorfs.c (ffff80001058b540)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffff80001058e584)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (ffff80001058ec10)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffff8000105956c0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
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
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffff800010597c54)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffff800010599008)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffff80001059a15c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffff80001146b904)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffff80001059ec60)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffff8000105a054c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (ffff8000105a0f4c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffff8000105a2d88)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffff8000105a6cbc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (ffff800010662738)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffff80001068d7bc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffff800010713214)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffff800010772680)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/clk/clk.c (ffff8000107becbc)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/soc/qcom/smem_state.c (ffff80001081d908)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/soc/qcom/smem_state.c:qcom_smem_state_get
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff80001083a9e4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffff80001084c410)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffff800010853c5c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffff80001085e4b8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffff80001085f294)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffff80001085fcf4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffff8000108616c4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffff8000108b4058)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffff8000108b6e30)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/lightnvm/core.c (ffff8000108e14ac)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/base/core.c (ffff8000108e66a8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffff80001090d764)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffff80001094fe34)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffff800010954688)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffff80001096429c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffff800010966984)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffff800010967fb8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffff8000109689b4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffff8000109694c8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffff800010969f60)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096b800)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (ffff80001097fef4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffff80001098d2a0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffff800010992494)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffff800010997038)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffff8000109d9b28)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/usb/core/hub.c (ffff800010a15e68)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffff800010a1b87c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffff800010a211a8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffff800010a2420c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffff800010a28fc8)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffff800010ac3564)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_register
```
```
In drivers/opp/core.c (ffff800010b1993c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/opp/of.c (ffff800010b1c80c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffff800010b83644)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (ffff800010b9ee50)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In lib/klist.c (ffff800010d89c84)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffff800010d8a63c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
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
In arch/arm/mm/dma-mapping.c (c031bdd0)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/fork.c (c0352b20)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (c0377910)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (c03abe30)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
```
```
In kernel/sched/psi.c (c03b3950)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/irq/manage.c (c03cbd44)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/cgroup/cgroup-v1.c (c041d368)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
```
```
In kernel/utsname.c (c0425cd8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (c0427618)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (c042ac94)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (c0449c44)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (c04c7540)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/backing-dev.c (c0503b74)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (c056eed4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (c05baab8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (c05cac2c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/root.c (c06029e8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/configfs/item.c (c061eb5c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (c06c9b08)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (c06cc128)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (c06d9054)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In security/apparmor/apparmorfs.c (c073c0f4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (c073f3c8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (c073faa8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (c07467e4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
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
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (c0748e40)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (c074a2c4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (c074b274)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (c1544554)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (c074f9fc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (c0751158)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (c07519e4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (c0752fe8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (c0756cc8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (c080b3cc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (c082f838)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/clk/clk.c (c08eb360)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/soc/qcom/smem_state.c (c0938310)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/soc/qcom/smem_state.c:qcom_smem_state_get
```
```
In drivers/reset/core.c (c0958760)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (c095e6dc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (c0965cd8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (c0966768)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (c0967098)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (c0968718)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (c09ae890)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (c09b082c)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/lightnvm/core.c (c09cffc8)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/base/core.c (c09d4ce0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (c09f671c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/dax/bus.c (c0a3accc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
```
In drivers/dma-buf/dma-fence.c (c0a3d420)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (c0a3e444)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (c0a3eba4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (c0a3f104)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (c0a40020)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (c0a41330)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (c0a52bc0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (c0a5f4a0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (c0a6361c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (c0a679e0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/mtd/mtdsuper.c (c0a9115c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/mtd/mtdsuper.c:mtd_set_super
```
```
In drivers/mtd/mtd_blkdevs.c (c0a97e1c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/mtd/mtd_blkdevs.c:blktrans_open
  - drivers/mtd/mtd_blkdevs.c:blktrans_dev_get
```
```
In drivers/net/phy/sfp-bus.c (c0ac0740)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/usb/core/hub.c (c0aee1b4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (c0af3824)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (c0af7e68)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (c0afa710)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (c0afef9c)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (c0ba5084)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_register
```
```
In drivers/opp/core.c (c0bf4660)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/opp/of.c (c0bf6ffc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
```
In drivers/remoteproc/remoteproc_virtio.c (c0c668d0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (c0c80be8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In lib/klist.c (c0e84a18)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (c0e84f98)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
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
In kernel/fork.c (c00000000013a44c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (c00000000016e594)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (c0000000001b4b9c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (c0000000001c0230)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/irq/manage.c (c0000000001d4fb4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/cgroup/cgroup-v1.c (c000000000248bb8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/utsname.c (c0000000002558ac)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (c0000000002578c0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (c00000000025c61c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (c000000000288190)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (c000000000346ca4)
Location: include/linux/kref.h:43
Inline: True
```
```
In mm/backing-dev.c (c00000000039e494)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (c000000000406ed8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (c00000000047be50)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (c0000000004e8594)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (c0000000004fe0a4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/root.c (c00000000055071c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/configfs/item.c (c000000000579f98)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (c00000000065523c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (c000000000658474)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (c000000000665a40)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In security/apparmor/apparmorfs.c (c0000000006fc928)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (c0000000007010ac)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (c000000000701a0c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (c00000000070ac4c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
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
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (c00000000070e358)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookup_replace
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (c0000000007100fc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (c00000000071169c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (c00000000139a3ec)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (c000000000718680)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (c00000000071a70c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (c00000000071b650)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (c00000000071db80)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (c000000000723380)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (c000000000816d48)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (c0000000008277dc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
```
In drivers/reset/core.c (c0000000008eb8f0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (c0000000008f3138)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (c0000000008fd1d0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (c0000000008fe7dc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (c0000000008ff0d4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (c000000000900d40)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (c00000000094e2dc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (c000000000950c64)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/lightnvm/core.c (c0000000009754d4)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/base/core.c (c00000000097c3d8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (c0000000009adc90)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (c0000000009fca74)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a01c68)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (c000000000a1b31c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (c000000000a1e158)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (c000000000a1f8e0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (c000000000a205a0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (c000000000a20f18)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (c000000000a22638)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (c000000000a24044)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (c000000000a3bbac)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (c000000000a4e768)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (c000000000a541fc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (c000000000a58108)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (c000000000a9b9cc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (c000000000aaedfc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab5394)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
```
```
In drivers/usb/core/hub.c (c000000000ace574)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (c000000000ad4b60)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (c000000000adae4c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (c000000000adf098)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (c000000000ae5298)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (c000000000ba5e78)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_register
```
```
In drivers/opp/core.c (c000000000c0b3c8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/opp/of.c (c000000000c0f068)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
```
In drivers/remoteproc/remoteproc_virtio.c (c000000000c60b34)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (c000000000c721b8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In lib/klist.c (c000000000ecadf4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (c000000000ecb6b4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
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
In kernel/fork.c (ffffffe0000c083c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (ffffffe0000dc864)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (ffffffe00010384c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffe000109814)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/irq/manage.c (ffffffe000114898)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000152fec)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/utsname.c (ffffffe00015aeee)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffe00015c72c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffe00015f940)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffe00016c8fa)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffffffe0001c9ec4)
Location: include/linux/kref.h:43
Inline: True
```
```
In mm/backing-dev.c (ffffffe0001f6a86)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffe00022c3c0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffe0002588e0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffe000298d66)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffffffe0002a66b6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/root.c (ffffffe0002d4afc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/configfs/item.c (ffffffe0002edde0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffe000378f70)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffe00037b18c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffe0003845ec)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In security/apparmor/apparmorfs.c (ffffffe0003d9bf4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffe0003dc4e0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (ffffffe0003dc9ea)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffe0003e262c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
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
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffe0003e46e4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__lookup_replace
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e5852)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffe0003e6764)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffe0000268ce)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
```
```
In security/apparmor/resource.c (ffffffe0003e9ff8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffe0003eb3d0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (ffffffe0003ebcce)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffe0003ed16e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffe0003f061c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (ffffffe00048f03e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffe000499990)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/clk/clk.c (ffffffe00050e040)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/reset/core.c (ffffffe00052bc5a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffe000530442)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
```
In drivers/tty/tty_port.c (ffffffe0005369f0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffe000537790)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffe000537e32)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffe000539272)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffe000567174)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffe00056796c)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffe000576bd6)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/base/core.c (ffffffe00057b056)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffe00059219c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffe0005c0268)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c3e34)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffe0005d1630)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d36d4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffe0005d402a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffe0005d4618)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffe0005d48cc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffe0005d5822)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d687e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (ffffffe0005e5fe6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffe0005f1124)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffe0005f4fba)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffe0005f757c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffe000624a26)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/usb/core/hub.c (ffffffe00063b07e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffe00063fa56)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffe000643b8a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffe000646800)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffe00064a9dc)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffe0006c4146)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_register
```
```
In drivers/opp/core.c (ffffffe000702238)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/opp/of.c (ffffffe0007047f6)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/of.c:dev_pm_opp_of_add_table_indexed
  - drivers/opp/of.c:dev_pm_opp_of_add_table
```
```
In drivers/nvmem/core.c (ffffffe00073715a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_get
```
```
In lib/klist.c (ffffffe0008b35de)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffe0008b3bc2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
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
void kref_get(struct kref *kref);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81099421)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (ffffffff810c048e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (ffffffff810f3eda)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff810fc657)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81110857)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81160581)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/utsname.c (ffffffff81169e62)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8116b90f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffff8116e62e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff8118c30d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffffffff81207a22)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/backing-dev.c (ffffffff81241b15)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffff81289574)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffff812d7960)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff8131ff44)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffffffff813300e8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/root.c (ffffffff8136ab59)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/configfs/item.c (ffffffff81384b4d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff81422a09)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8142506a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff8142ed42)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In security/apparmor/apparmorfs.c (ffffffff8148da80)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff81490f0a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (ffffffff8149157c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81497f7b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
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
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8149a6b0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8149afba)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/procattr.c (ffffffff8149c961)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149eb49)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In security/apparmor/resource.c (ffffffff814a0b1d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814a20c7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (ffffffff814a291b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff814a3f6a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff814a7b83)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff8154e605)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff81559291)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159d695)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff815d7907)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/clk/clk.c (ffffffff81618b18)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81635af7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff816473c0)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8164bd08)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff81652d4a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81653b0f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81654228)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff816558bd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff81687be2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff8168a57e)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816bcd3d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/base/core.c (ffffffff816c1568)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff816e0299)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff81704af4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81708345)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81718b18)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8171af7d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8171b8cc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8171bef9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171cc8f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8171d43e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8171e4e4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8172edcf)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff8173aeab)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8173ecaa)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/nvme/host/core.c (ffffffff81746d73)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
Direct callers:
  - drivers/nvme/host/core.c:nvme_dev_ioctl
```
```
In drivers/ata/libata-core.c (ffffffff81752115)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81784174)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/usb/core/hub.c (ffffffff8179f30e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff817a4801)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817a9409)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff817ab9c7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff817b06bd)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff81824805)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_register
```
```
In drivers/opp/core.c (ffffffff81862f85)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81898671)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (ffffffff818a26d3)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/klist.c (ffffffff81a4f4a1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff81a4f616)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
**Symbols:**

```
ffffffff8149a990-ffffffff8149a99a: kref_get (STB_LOCAL)
ffffffff8149ce80-ffffffff8149ce8a: kref_get (STB_LOCAL)
ffffffff8174893a-ffffffff81748944: kref_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void kref_get(struct kref *kref);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81087e71)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (ffffffff810aec92)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (ffffffff810e409a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff810ec867)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81101587)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811537f1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/utsname.c (ffffffff8115d062)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8115eb0f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffff811617ce)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff8117f3ed)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffffffff811fab52)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/backing-dev.c (ffffffff81234b05)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffff8127b414)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffff812c85e0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff81310ae4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffffffff81320d08)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/root.c (ffffffff8135b5e9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/configfs/item.c (ffffffff813755dd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff81413489)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff81415aea)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff8141f7c2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In security/apparmor/apparmorfs.c (ffffffff8147e4a0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff8148192a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (ffffffff81481f9c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8148899b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
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
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff8148b0d0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8148b9da)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/procattr.c (ffffffff8148d381)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8148f569)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In security/apparmor/resource.c (ffffffff8149153d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81492ae7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (ffffffff8149333b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff8149498a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff814985a3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff8153e8e5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff81549751)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158c825)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff815c14c7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/clk/clk.c (ffffffff8160d048)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/reset/core.c (ffffffff81627820)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8162c158)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8163318a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81633eef)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff81634608)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff81635c6d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff81665792)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff81667f7e)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/base/core.c (ffffffff8169c818)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff816ba8d9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff816d8574)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816dbdc5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff816f1048)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816f43dd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff816f4d2c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff816f5359)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f60ef)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff816f689e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816f7934)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff817081ef)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff8171cb4b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8172094a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/nvme/host/core.c (ffffffff817289f3)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
Direct callers:
  - drivers/nvme/host/core.c:nvme_dev_ioctl
```
```
In drivers/ata/libata-core.c (ffffffff81731fb5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81763ac4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff8177be40)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81780552)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
```
```
In drivers/usb/core/hub.c (ffffffff81790f8e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff81796371)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8179ae09)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff8179d3c7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff817a2081)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/media/cec/cec-notifier.c (ffffffff817ebea5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_register
```
```
In drivers/opp/core.c (ffffffff8182bc35)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/nvmem/core.c (ffffffff8185de43)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/klist.c (ffffffff81a0c5a1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff81a0c716)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
**Symbols:**

```
ffffffff8148b3b0-ffffffff8148b3ba: kref_get (STB_LOCAL)
ffffffff8148d8a0-ffffffff8148d8aa: kref_get (STB_LOCAL)
ffffffff8172a55a-ffffffff8172a564: kref_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void kref_get(struct kref *kref);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810993d1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (ffffffff810bf9de)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (ffffffff810f10ba)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff810f9817)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110e747)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115e351)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/utsname.c (ffffffff81167c32)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff811696df)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffff8116c3fe)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff8118a0dd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffffffff812057f2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/backing-dev.c (ffffffff8123f8b5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffff81287384)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffff812d5770)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff8131da14)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffffffff8132dbb8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/root.c (ffffffff81368629)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/configfs/item.c (ffffffff8138261d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff8141eba9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8142120a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff8142aee2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In security/apparmor/apparmorfs.c (ffffffff81489b20)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff8148cfaa)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (ffffffff8148d61c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff8149401b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
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
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff81496750)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff8149705a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/procattr.c (ffffffff81498a01)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff8149abe9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In security/apparmor/resource.c (ffffffff8149cbbd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8149e167)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (ffffffff8149e9bb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff814a000a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff814a3c23)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff8154a345)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff81554fd1)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159dc15)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff815d9cf7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/clk/clk.c (ffffffff816468f8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81663877)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff81675780)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8167a0c8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8168110a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff81681ecf)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff816825e8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff81683c7d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff816b5f22)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff816b87ee)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff816eb20d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/base/core.c (ffffffff816efa38)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff8170d8dc)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff817438c4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81747115)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff817578e8)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81759d4d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff8175a69c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff8175acc9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175ba5f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff8175c20e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8175d2b4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8176db9f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff8177b63b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8177f43a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81781e05)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817b4524)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff817c6c10)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cb322)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
```
```
In drivers/usb/core/hub.c (ffffffff817dbdae)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff817e12a1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817e5ea9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff817e8467)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff817ed15d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff81871745)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_register
```
```
In drivers/opp/core.c (ffffffff818b3d15)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/nvmem/core.c (ffffffff818f3cc3)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/klist.c (ffffffff81abb891)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff81abba06)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
**Symbols:**

```
ffffffff81496a30-ffffffff81496a3a: kref_get (STB_LOCAL)
ffffffff81498f20-ffffffff81498f2a: kref_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void kref_get(struct kref *kref);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a100a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/pid.c (ffffffff810c7e0a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (ffffffff810fc0ba)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_fork
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffff81104969)
Location: include/linux/kref.h:43
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81119c77)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116b781)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/utsname.c (ffffffff81175312)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_get
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81176def)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_get_parent
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:pidns_get
  - kernel/pid_namespace.c:copy_pid_ns
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit.c (ffffffff81179bbe)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/audit.c:audit_get_tty
```
```
In kernel/relay.c (ffffffff81197a4d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_open
```
```
In kernel/events/core.c (ffffffff81214662)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/backing-dev.c (ffffffff8124f035)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In mm/hugetlb.c (ffffffff81297ac4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_vm_op_open
```
```
In fs/super.c (ffffffff812e65c0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff8132f714)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/eventfd.c (ffffffff81340998)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
```
In fs/proc/root.c (ffffffff8137bc79)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/configfs/item.c (ffffffff8139613d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_find_item
```
```
In fs/fuse/file.c (ffffffff81435909)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_async_req_send
```
```
In fs/fuse/inode.c (ffffffff8143808a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In ipc/util.c (ffffffff81441da2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_open
```
```
In security/apparmor/apparmorfs.c (ffffffff814a17a5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
```
```
In security/apparmor/capability.c (ffffffff814a4df5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (ffffffff814a5484)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff814ac047)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
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
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:find_attach
```
```
In security/apparmor/policy.c (ffffffff814ae820)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_new_null_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffff814af12a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/apparmor/procattr.c (ffffffff814b0b57)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffff814b3435)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_sock_graft
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_sk_clone_security
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_task_alloc
  - security/apparmor/lsm.c:apparmor_cred_transfer
  - security/apparmor/lsm.c:apparmor_cred_prepare
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In security/apparmor/resource.c (ffffffff814b504f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814b6668)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
```
In security/apparmor/policy_ns.c (ffffffff814b6feb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:aa_prepare_ns
  - security/apparmor/policy_ns.c:__aa_find_or_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:__aa_create_ns
  - security/apparmor/policy_ns.c:aa_lookupn_ns
  - security/apparmor/policy_ns.c:aa_findn_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff814b849d)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:aa_vec_find_or_create_label
  - security/apparmor/label.c:__label_insert
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (ffffffff814bc4ab)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:build_pivotroot
```
```
In security/apparmor/net.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In security/apparmor/af_unix.c (0)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff81564195)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In drivers/pinctrl/core.c (ffffffff8156ee61)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b8045)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_grab_context
```
```
In drivers/acpi/ec.c (ffffffff815f3bb7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/clk/clk.c (ffffffff81660e88)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_create_clk
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167de37)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/reset/core.c (ffffffff8168fde0)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81694728)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_standard_install
  - drivers/tty/tty_io.c:tty_find_polling_driver
```
```
In drivers/tty/tty_port.c (ffffffff8169b75a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_tty_set
  - drivers/tty/tty_port.c:tty_port_tty_get
```
```
In drivers/tty/tty_mutex.c (ffffffff8169c50f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_mutex.c:tty_lock_interruptible
  - drivers/tty/tty_mutex.c:tty_lock
```
```
In drivers/tty/tty_jobctrl.c (ffffffff8169cc48)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/tty_jobctrl.c:get_current_tty
  - drivers/tty/tty_jobctrl.c:__proc_set_tty
```
```
In drivers/tty/pty.c (ffffffff8169e6cd)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/char/virtio_console.c (ffffffff816cfc22)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_open
```
```
In drivers/char/hw_random/core.c (ffffffff816d2dbe)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffff81705a4d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/base/core.c (ffffffff8170a278)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff817285c7)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/nvdimm/core.c (ffffffff8175ed14)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81762555)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:get_ndd
```
```
In drivers/dax/bus.c (ffffffff81772d88)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dax/bus.c:__devm_create_dev_dax
```
```
In drivers/dma-buf/dma-fence.c (ffffffff817752cb)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffff81775c5c)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffff817762a9)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81776d2f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
```
```
In drivers/dma-buf/sync_file.c (ffffffff817778ae)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_get_fence
  - drivers/dma-buf/sync_file.c:sync_file_create
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81778954)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8178933f)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
```
In drivers/scsi/sr.c (ffffffff8179546b)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
```
```
In drivers/scsi/sg.c (ffffffff8179923a)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8179bbf5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_get
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817ce4f4)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/vfio/vfio.c (ffffffff817e0eb0)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e55c2)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_find
```
```
In drivers/usb/core/hub.c (ffffffff817f603e)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffff817fb5e1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_get_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81800109)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_get_from_anchor
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
  - drivers/usb/core/urb.c:usb_anchor_urb
```
```
In drivers/usb/core/message.c (ffffffff818026b5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_set_configuration
```
```
In drivers/usb/core/file.c (ffffffff8180739d)
Location: include/linux/kref.h:43
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff8188b705)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_register
```
```
In drivers/opp/core.c (ffffffff818cffc5)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
  - drivers/opp/core.c:_find_opp_table_unlocked
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81908dd1)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/nvmem/core.c (ffffffff81914d63)
Location: include/linux/kref.h:43
Inline: True
```
```
In lib/klist.c (ffffffff81ac7d11)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
```
```
In lib/kobject.c (ffffffff81ac7f26)
Location: include/linux/kref.h:43
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get
```
**Symbols:**

```
ffffffff814aeb00-ffffffff814aeb0a: kref_get (STB_LOCAL)
ffffffff814b10a0-ffffffff814b10aa: kref_get (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
