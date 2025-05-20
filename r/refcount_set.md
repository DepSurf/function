# Function: <code>refcount_set</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104aeaa)
Location: include/linux/refcount.h:28
Inline: True
```
```
In kernel/sched/autogroup.c (ffffffff810cdb92)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff810e6167)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/posix-clock.c (ffffffff8110af68)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/cgroup/cgroup.c (ffffffff81123c81)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81128ef7)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81130bbe)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81132cd7)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_watch.c (ffffffff8113d127)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff8113f62c)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/seccomp.c (ffffffff8115058d)
Location: include/linux/refcount.h:28
Inline: True
```
```
In kernel/relay.c (ffffffff8115247a)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (ffffffff811e17b7)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff81212686)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8121647b)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/eventfd.c (ffffffff812a29df)
Location: include/linux/refcount.h:28
Inline: True
```
```
In fs/configfs/item.c (ffffffff812e1be5)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffff8136c49a)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_init
```
```
In fs/fuse/file.c (ffffffff81377b07)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff813795dd)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In security/keys/key.c (ffffffff8138f10a)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff813bde17)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (ffffffff813db2a9)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff813ddd1a)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff813de6b4)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff813e6bd8)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff813ed183)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg.c (ffffffff81444027)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In block/bsg-lib.c (ffffffff81445921)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_request_fn
```
```
In lib/cpu_rmap.c (ffffffff814858b7)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff8148fbb5)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814cbce2)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff8150211a)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff815489c8)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff8154d145)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81561d1d)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (0)
Location: include/linux/refcount.h:28
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81574eae)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8157bc51)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff815aba62)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff815adf78)
Location: include/linux/refcount.h:28
Inline: True
```
```
In drivers/base/firmware_class.c (ffffffff815f7d33)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff8162cdb6)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff8163022b)
Location: include/linux/refcount.h:28
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8163ec16)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81641c6c)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8164f5a5)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8165e856)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff816622d4)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/hub.c (ffffffff816ae99d)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff816b07d6)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff816b2b63)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff816b88f2)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff816ba699)
Location: include/linux/refcount.h:28
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81735ded)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In net/core/sock.c (ffffffff817b2c32)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff817ba422)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb_head
```
```
In net/core/net_namespace.c (ffffffff817c32c6)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff817cd855)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/neighbour.c (ffffffff817dbf4f)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/filter.c (ffffffff817ec32b)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/netpoll.c (ffffffff817f2622)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff817f44f1)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/sched/sch_generic.c (ffffffff817fd41f)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff81814664)
Location: include/linux/refcount.h:28
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8181fa46)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818204a8)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffffffff818283ee)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81841105)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff81851ff1)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81858117)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff8185d9ea)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81862b26)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/syncookies.c (ffffffff8186df7a)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8186ff8c)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81873b3b)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff8187aad1)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff8187df65)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_dup
```
```
In net/unix/af_unix.c (ffffffff81882d1c)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/anycast.c (ffffffff81886fe0)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8189018b)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/addrlabel.c (ffffffff81896d19)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a3af2)
Location: include/linux/refcount.h:28
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff818b2bbc)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff818bb89b)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/calipso.c (ffffffff818c8cb4)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff818d233d)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In lib/klist.c (ffffffff818edbd3)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff818eec50)
Location: include/linux/refcount.h:28
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104e89b)
Location: include/linux/refcount.h:29
Inline: True
```
```
In kernel/sched/autogroup.c (ffffffff810d5412)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff810ee3fb)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/posix-clock.c (ffffffff811160c8)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/cgroup/cgroup.c (ffffffff81130150)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81135b7f)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8113db0f)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8113faa0)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_watch.c (ffffffff81149ee7)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff8114c46c)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/seccomp.c (ffffffff8115c7d3)
Location: include/linux/refcount.h:29
Inline: True
```
```
In kernel/relay.c (ffffffff8115ecea)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In mm/backing-dev.c (ffffffff811f77d7)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff8122cd76)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8123112b)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/notify/group.c (ffffffff812bc4a4)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff812bc891)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff812c5c8f)
Location: include/linux/refcount.h:29
Inline: True
```
```
In fs/configfs/item.c (ffffffff81306515)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffff8139107a)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_init
```
```
In fs/fuse/file.c (ffffffff8139c8a6)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8139e47d)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff813a2554)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff813a712d)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff813ad601)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:do_semtimedop
```
```
In ipc/namespace.c (ffffffff813b2ee0)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff813b45ed)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff813e3fb7)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (ffffffff81401d21)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff814046ba)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81405044)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8140dd58)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff81414b8f)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In block/bsg.c (ffffffff81470dd3)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In block/bsg-lib.c (ffffffff81472438)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_request_fn
```
```
In lib/cpu_rmap.c (ffffffff814c1ac6)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff814cbd65)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8150c2b2)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff8154447a)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff815abf8d)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff815b06c5)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815c5a8d)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (0)
Location: include/linux/refcount.h:29
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff815d969e)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff815e05e1)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81612402)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff81614949)
Location: include/linux/refcount.h:29
Inline: True
```
```
In drivers/connector/cn_queue.c (ffffffff8163d2b0)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/base/firmware_class.c (ffffffff8165fd04)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff81695546)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff81698a4b)
Location: include/linux/refcount.h:29
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816a7a1d)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816aa691)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff816b8845)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff816c7c66)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff816cb549)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81705eb6)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hub.c (ffffffff81719fad)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8171bde6)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8171e233)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81724203)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81726051)
Location: include/linux/refcount.h:29
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817a7b67)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/md/dm.c (ffffffff817c08e1)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff817c2d1e)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffff817d5795)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
```
```
In net/core/sock.c (ffffffff8182af16)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8183505b)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff8183ce16)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff818471fa)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81853ddd)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff818563cf)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/rtnetlink.c (ffffffff827145b7)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnetlink_init
```
```
In net/core/filter.c (ffffffff8186810b)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/netpoll.c (ffffffff8186dbe7)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff8186fc65)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_newrule
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/sched/sch_generic.c (ffffffff8187aea3)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff81893788)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189e9ac)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8189f45e)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffffffff818a7902)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffff818c0874)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff818d1de1)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff818d7c5a)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff818dd174)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2c4f)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/ipmr.c (ffffffff818ecaa6)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff818ee8f0)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff818f093c)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f44e5)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff818fb5c1)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff818fee0f)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_dup
```
```
In net/unix/af_unix.c (ffffffff819050cc)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/anycast.c (ffffffff81908206)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81911735)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819259bc)
Location: include/linux/refcount.h:29
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8193592e)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff8193e95b)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/calipso.c (ffffffff8194c354)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81957279)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In lib/klist.c (ffffffff81973a87)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81974f10)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81051313)
Location: include/linux/refcount.h:29
Inline: True
```
```
In kernel/sched/autogroup.c (ffffffff810dd3fa)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff810f67fd)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/posix-clock.c (ffffffff81122965)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/cgroup/cgroup.c (ffffffff8113e807)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81144485)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8114c4a3)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8114e2d8)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_watch.c (ffffffff811588d8)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff8115aebc)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/seccomp.c (ffffffff8116bb42)
Location: include/linux/refcount.h:29
Inline: True
```
```
In kernel/relay.c (ffffffff8116c62c)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/bpf/btf.c (ffffffff811c925a)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/bpf/sockmap.c (ffffffff811cd322)
Location: include/linux/refcount.h:29
Inline: True
```
```
In mm/backing-dev.c (ffffffff81218c05)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff8124f94e)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81254027)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In fs/notify/group.c (ffffffff812e50c4)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff812e5302)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff812eeeb1)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/posix_acl.c (ffffffff8130ad27)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/proc/generic.c (ffffffff813203fd)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff813345a8)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffff813c00eb)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_init
```
```
In fs/fuse/file.c (ffffffff813cbcbb)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff813cd827)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff813d1984)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff813d6246)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff813dd07e)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:do_semtimedop
```
```
In ipc/namespace.c (ffffffff813e360d)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff813e4d87)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff814147ac)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (ffffffff81432c81)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8143576a)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81436131)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8143f9c2)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff81446f8f)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff81458764)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff8145957a)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-mq.c (ffffffff8148edcc)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg-lib.c (ffffffff814a6984)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_request_fn
```
```
In lib/cpu_rmap.c (ffffffff814f2a03)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff814fccd0)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81541101)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff8157a315)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff815e3f0e)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff815e8adf)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815fe17d)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8160eb48)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_from_lookup
```
```
In drivers/tty/tty_io.c (ffffffff8161262b)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff816198a2)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff8164be3b)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff8164e561)
Location: include/linux/refcount.h:29
Inline: True
```
```
In drivers/connector/cn_queue.c (ffffffff816788d0)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/base/core.c (ffffffff8167f04f)
Location: include/linux/refcount.h:29
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff8169a9aa)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff816d1619)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff816d4cbf)
Location: include/linux/refcount.h:29
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816e3af9)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816e6baa)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff816f3990)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8170463a)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81707f40)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8170c614)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8173afb8)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81743bbc)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hub.c (ffffffff81758d53)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8175ab20)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8175d6cf)
Location: include/linux/refcount.h:29
Inline: True
```
```
In drivers/usb/core/config.c (ffffffff8176300b)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81764def)
Location: include/linux/refcount.h:29
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817ef5b2)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/md/dm.c (ffffffff81808d98)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff8180b5cd)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffff8181e48f)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
```
```
In net/core/sock.c (ffffffff81875007)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8187f2ec)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff81887e59)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff8189070a)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff8189f546)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff818a518f)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:__neigh_create
```
```
In net/core/filter.c (ffffffff818b827f)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/netpoll.c (ffffffff818bed54)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff818c20df)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/sched/sch_generic.c (ffffffff818cd27f)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/ipv4/inetpeer.c (ffffffff818e7b46)
Location: include/linux/refcount.h:29
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f32e3)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f3e99)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffffffff818fca95)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81916432)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff819282e8)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff8192e5fb)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81933cfc)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff8193944f)
Location: include/linux/refcount.h:29
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81942853)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81945200)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8194724d)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194aac5)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81950e9a)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/xfrm/xfrm_input.c (ffffffff819558d6)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_dup
```
```
In net/unix/af_unix.c (ffffffff8195a71b)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/anycast.c (ffffffff8195f3d9)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81968b5e)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/route.c (ffffffff8197290f)
Location: include/linux/refcount.h:29
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff8197b424)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197d9f6)
Location: include/linux/refcount.h:29
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff8198e28f)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81997869)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff8199f047)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff819a658b)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff819b3cf8)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff819cd0f5)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/klist.c (ffffffff819cfe5d)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff819d1448)
Location: include/linux/refcount.h:29
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8104e9ca)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/user.c (ffffffff810a416e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/sched/autogroup.c (ffffffff810e7b4a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/irq/manage.c (ffffffff81101f6d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/posix-clock.c (ffffffff8112e045)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/cgroup/cgroup.c (ffffffff8114a221)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8114ff95)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811590c3)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8115afb8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_watch.c (ffffffff811657f8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff81167c1c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/seccomp.c (ffffffff811793a2)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/relay.c (ffffffff8117a05c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/bpf/btf.c (ffffffff811dcb7a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In mm/backing-dev.c (ffffffff8122b980)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff81263c6e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81268407)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (ffffffff81294110)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/notify/group.c (ffffffff812f9ba4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff812f9f72)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff81303841)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81304233)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff8130952d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
```
```
In fs/crypto/keyinfo.c (ffffffff8131167d)
Location: include/linux/refcount.h:30
Inline: True
```
```
In fs/posix_acl.c (ffffffff81320567)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/proc/generic.c (ffffffff813374e4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff8134b8c8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffff813d96a3)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff813e4d75)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff813e6c01)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff813ec084)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff813f0895)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff813f76de)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:do_semtimedop
```
```
In ipc/namespace.c (ffffffff813fdf81)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff813ff5a2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff81430d90)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (ffffffff8144f931)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8145235a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81452d51)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8145c8b2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff81463ebc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff81475ba4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff81476caa)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-mq.c (ffffffff814a880e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff814bffaa)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff814c09b9)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff814c14d2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/cpu_rmap.c (ffffffff81506d33)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff81511730)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81558461)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff81591b65)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff815fe2fc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
```
In drivers/dma/dmaengine.c (ffffffff8160292f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8161924d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8162b338)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_from_lookup
```
```
In drivers/tty/tty_io.c (ffffffff8162f6cb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff81636b12)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81669fab)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff8166c7f1)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/connector/cn_queue.c (ffffffff816979b0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/base/core.c (ffffffff8169f48f)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff816bb1a0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff816f2ca9)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff816f6a07)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81706d93)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81709dba)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8171752c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff81726aaa)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81729050)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8172ea94)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8175e598)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8176686c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hub.c (ffffffff8177d2c3)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8177f050)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81781d0f)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/usb/core/config.c (ffffffff8178764b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff8178946f)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff81808d47)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8181b47f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/md/dm.c (ffffffff81835048)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff818375cd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffff8184a28d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/nvmem/core.c (ffffffff818870e2)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff818958d4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8189d240)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff818a8969)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff818b105a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff818c1f06)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff818c4994)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffff818decdf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/skmsg.c (ffffffff818e6325)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff818e7b4f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff818eaf9f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/sched/sch_generic.c (ffffffff818f85df)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff818ff5fc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81902453)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffff819149f6)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920e03)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819219b9)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffffffff8192ac07)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81944bd2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff81957548)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff8195db2f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/igmp.c:__ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81963c32)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81969042)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv4/metrics.c (ffffffff8196c716)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81972923)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff819754f0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81978e1d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197d5ed)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff819843ea)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff8198f40b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/anycast.c (ffffffff81993fcc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8199e481)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff819b1104)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b4d4c)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c4b82)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff819ce139)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff819d5b67)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff819dd0eb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff819ead65)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81a06345)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/klist.c (ffffffff81a0949d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81a0aa08)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81051a8e)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/fork.c (ffffffff81098426)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810a8e4e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffff810bfd49)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/fair.c (ffffffff810deb3a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/autogroup.c (ffffffff810eeabf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff810f720f)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110b219)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/posix-clock.c (ffffffff81138a55)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_register
```
```
In kernel/futex.c (ffffffff8113e6a3)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81155666)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8115be91)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811657f8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81167668)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_watch.c (ffffffff81172368)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff81174857)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/seccomp.c (ffffffff81186232)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff81186e9d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff8119a541)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/btf.c (ffffffff811f22bc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffffffff811ffabc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8120b3cd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff8120deae)
Location: include/linux/refcount.h:30
Inline: True
```
```
In mm/backing-dev.c (ffffffff8123b5f5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff8127ebf6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812836e8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (ffffffff812b0341)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In mm/hmm.c (ffffffff812c420a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/hmm.c:hmm_mirror_register
```
```
In fs/exec.c (ffffffff812d4a21)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/fsopen.c (ffffffff8130bf68)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff8131a241)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff8131a602)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff81324de5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81325510)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff8132b5bd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/io_uring.c (ffffffff8132ff1e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
```
```
In fs/crypto/keyinfo.c (ffffffff81338bb3)
Location: include/linux/refcount.h:30
Inline: True
```
```
In fs/posix_acl.c (ffffffff81347e27)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/proc/generic.c (ffffffff8135f615)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff81374248)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffff81405241)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff81410678)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81412c31)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff814182aa)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8141cd75)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff81423be2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff8142a5b2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff8142bcba)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff8145e7a9)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (ffffffff8147d611)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8147fd1a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81480707)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff81489e3d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff81491172)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff814a3a98)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff814a49ad)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (ffffffff814cad35)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff814d61ef)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff814ee6de)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff814ef19d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff814efc6d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/cpu_rmap.c (ffffffff81534f53)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff8153fd33)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81588471)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff815c2a34)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff8162f852)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81635148)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8164cf44)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8165f2b3)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8166358b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8166ad62)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff8169f79a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff816a242b)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/connector/cn_queue.c (ffffffff816d0537)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffffffff816d1bb6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff816d7ac5)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff816f5a22)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff8172c27f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff81730307)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dax/bus.c (ffffffff817404d0)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81741efb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff817455ca)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8175221d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff817621dd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8176439e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8176a284)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff8179bc18)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817a56bd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hub.c (ffffffff817bb83c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817bc1bf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817bf9cf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817c60a4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817c791f)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff8184a5d2)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185d6c2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/md/dm.c (ffffffff81876a98)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff8187a254)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffff8188d11b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/nvmem/core.c (ffffffff818d12c6)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff818dfe01)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff818e7ac6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff818f3fb6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff818fe065)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff8190e646)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff819143a4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffff8192cc1f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (ffffffff81934575)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81935cc5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff819374cf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff8193aa3e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81947a62)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff81957dae)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff8196222c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff819636d0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffff81976e1d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819837cc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81984365)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffffffff8198de63)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819a9238)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff819bbf68)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff819c2edb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff819c9702)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfa03)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff819d341c)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819d591b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffffffff819dc3c2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff819df0af)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819e2936)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e6a42)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee0df)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff819fac1d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/anycast.c (ffffffff819ffabb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a0a522)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1f484)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a2345b)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a339ea)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81a3cd48)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff81a44c39)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81a4bcfe)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81a59e8c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81a75c54)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/klist.c (ffffffff81a78e1e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81a7a3b6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810523a9)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/fork.c (ffffffff8109ea00)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810af41e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffff810c6119)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/fair.c (ffffffff810e908a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/autogroup.c (ffffffff810fa6bf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff81102f9f)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81117c39)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/futex.c (ffffffff8114a263)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81161297)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81167ab1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811716b8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81173528)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_watch.c (ffffffff8117e218)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff811806c7)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/seccomp.c (ffffffff81191f02)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff81192dbd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff811a5df1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/btf.c (ffffffff811fe9cc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffffffff8120cc1c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff812186ad)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff8121b4de)
Location: include/linux/refcount.h:30
Inline: True
```
```
In mm/backing-dev.c (ffffffff81249b15)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff8128e636)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81293288)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (ffffffff812c1e31)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (ffffffff812e65a1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/fsopen.c (ffffffff8131ef78)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff8132d061)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff8132d422)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff81337b75)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff813382a0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff8133e40d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/io_uring.c (ffffffff81341304)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keyring.c (ffffffff8134c805)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e69f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/posix_acl.c (ffffffff813600c7)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/proc/generic.c (ffffffff81377875)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff8138c4c8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffff8141f366)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff8142a288)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8142c91b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff8143216a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81436bc5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff8143d922)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff814442e2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff81445a0a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff81478559)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (ffffffff814972e1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81499a1a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff8149a407)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff814a3cfd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff814ab022)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff814be6c8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff814bf63d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (ffffffff814e3f15)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff814ef548)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff81507b3e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff8150864d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff8150911d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/cpu_rmap.c (ffffffff81555d63)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff81560bd3)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a9e71)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff815e3de4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff81651c4f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81656e58)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8166f684)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff816819ed)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81685bfb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8168d432)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff816c253a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff816c51cc)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/connector/cn_queue.c (ffffffff816f4357)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffffffff816f5aa6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff816fbbaa)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81719e22)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff817504cf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff81754397)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dax/bus.c (ffffffff817646d0)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff817667db)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8176974a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8177649d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff817861cd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8178838e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8178e2e4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817bf6c8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817c7d1d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff817d0670)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d775c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (ffffffff817ec04a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817ec9ef)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817f034f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817f6b58)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817f843f)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff8187bdc2)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/md/dm.c (ffffffff818a8898)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff818ac034)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff818bcff2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff818bf35b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f482a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff819036c6)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff81911fb1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81919f96)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff81925f76)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81930395)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81940d46)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81946a14)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffff8195ef1f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (ffffffff819671a5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81968d85)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff8196a38f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff8196d8fe)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81984381)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff8198e24e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81999400)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff8199a250)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffff819ad7ad)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819b9fbc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bab15)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffffffff819c4a33)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819dfddf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff819f2c68)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff819f9a7b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81a002e5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06593)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81a09f8c)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a0c48b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffffffff81a133b2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81a1613f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a19926)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1da32)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81a24f4f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81a318ad)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/anycast.c (ffffffff81a3669b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a411d2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff81a56104)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a59e40)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a6a53a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81a739c8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff81a7b829)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81a828ce)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81a8ff9c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81aacad5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/klist.c (ffffffff81ab01c2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81ab1716)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/ioport.c (ffffffff8103721f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056594)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In kernel/fork.c (ffffffff810a4c7b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/user.c (ffffffff810b712e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffff810cdf6f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/fair.c (ffffffff810ef1d7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/autogroup.c (ffffffff81104a9f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff8110cbb8)
Location: include/linux/refcount.h:134
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81122f39)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/namespace.c (ffffffff81159c0a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/futex.c (ffffffff8115ad43)
Location: include/linux/refcount.h:134
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81172756)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81179410)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811832e5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/pid_namespace.c (ffffffff81185007)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_watch.c (ffffffff81191874)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff8119298b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/seccomp.c (ffffffff811a7112)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff811a7bfd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff811bc0ec)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/trampoline.c (ffffffff8121ef98)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff81224ada)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/dispatcher.c (ffffffff8122639a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8122f90f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff81235627)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8124426e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff812465ee)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/watch_queue.c (ffffffff8124d52c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff81277d73)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
  - mm/backing-dev.c:wb_congested_get_create
```
```
In mm/zswap.c (ffffffff812c12ea)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812c6458)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (ffffffff812f61f5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (ffffffff8131db9b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/fsopen.c (ffffffff81358def)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff81366de4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff8136724b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff813716e7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81372099)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff81378271)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/io_uring.c (ffffffff8137e818)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:io_init_req
```
```
In fs/io-wq.c (ffffffff8138b5db)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:create_io_worker
```
```
In fs/crypto/keyring.c (ffffffff8139208b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff81394509)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/posix_acl.c (ffffffff813a5e36)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/proc/generic.c (ffffffff813c06e5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff813d7818)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffff8146e842)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (ffffffff8147a2e6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8147d37b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff81482577)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81486e75)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff8148e44d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff81494f13)
Location: include/linux/refcount.h:134
Inline: True
```
```
In security/keys/key.c (ffffffff81496d6a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff814cda22)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (ffffffff814eef71)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff814f210a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff814f2eb3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff814feb64)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff81509a24)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff8151ecf8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff81520b2d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (ffffffff81542795)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff8154e4f9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/bsg.c (ffffffff81568c87)
Location: include/linux/refcount.h:134
Inline: True
```
```
In block/bsg-lib.c (ffffffff8156973d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff8156a259)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/refcount.c (ffffffff8158f770)
Location: include/linux/refcount.h:134
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff815df473)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/klist.c (ffffffff815ea082)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff815eb7e3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff8160354a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81652c91)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff8168f3c4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff81700cf6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff817071d8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171f4a4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff81732929)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff8173765b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8173f4a2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81776119)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81779235)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/connector/cn_queue.c (ffffffff817ac9e0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/lightnvm/core.c (ffffffff817ae5a6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff817b53b5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d4f29)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff8180ec51)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff81812f66)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81824240)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8182703b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8182b99e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff818397a3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8184acea)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8184ed39)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff818524a4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff8188491d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff818889d4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81892460)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff8189b6b0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a3cf0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach
```
```
In drivers/usb/core/hub.c (ffffffff818bb661)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff818bc4e4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff818c0650)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff818c6e46)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff818c84d8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/file.c:init_usb_class
```
```
In drivers/md/dm.c (ffffffff819776bc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff8197c8d2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff8198d645)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff81990b4c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca95a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff819db043)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock.c (ffffffff819e3f58)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff819f4352)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff819f9f25)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81a048ea)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81a10a46)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81a1315b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81a3223f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81a36d7c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/page_pool.c (ffffffff81a3a4c5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/skmsg.c (ffffffff81a3cb49)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff81a3e236)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81a4029e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81a543bc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff81a65ed4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81a6c6ae)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_create
  - net/sched/cls_api.c:tcf_proto_create
```
```
In net/sched/act_api.c (ffffffff81a728f0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffff81a9774e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4a3c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa53a5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0b3e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81acd12b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/devinet.c (ffffffff81ae0d6e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81ae7809)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81aef62d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81af6250)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81afa822)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81afd575)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_add
```
```
In net/ipv4/ipmr.c (ffffffff81b038ee)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81b0711d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b0af73)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0dfa2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81b16b7f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81b25db7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/anycast.c (ffffffff81b2b78f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b36cbe)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4e61a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b523fa)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b609e8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mca_alloc
```
```
In net/ipv6/exthdrs.c (ffffffff81b6dbf6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff81b766e5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81b7dbae)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81b8a4cf)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81ba84a7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In arch/x86/kernel/ioport.c (ffffffff810382df)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810554a4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff810656bb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/fork.c (ffffffff810a038b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/user.c (ffffffff810b22ee)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffff810c8a51)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/core.c (ffffffff810e018d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff810ed1b1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/autogroup.c (ffffffff8110311f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff81109d78)
Location: include/linux/refcount.h:134
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8111ef29)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/namespace.c (ffffffff81155c1a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/futex.c (ffffffff81156c63)
Location: include/linux/refcount.h:134
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8116f417)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81176123)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811801d5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81181875)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81182173)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_watch.c (ffffffff8118ea24)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff8118fadb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/kprobes.c (ffffffff81194be9)
Location: include/linux/refcount.h:134
Inline: True
```
```
In kernel/seccomp.c (ffffffff811a47fd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff811a5fed)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff811b9cfc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/trampoline.c (ffffffff812225ee)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff81224153)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/dispatcher.c (ffffffff8122cf8a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81237e0a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff8123e0d7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8124e90f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81250c5e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/watch_queue.c (ffffffff8125799c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff81282387)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/zswap.c (ffffffff812cce0a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812d2048)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (ffffffff81301fc5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (ffffffff813289fb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/namespace.c (ffffffff81346d85)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff8136576f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff81374134)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff813745ab)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff8137f4a7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff8137fedc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff81385f76)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/io_uring.c (ffffffff81393f78)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:io_init_identity
```
```
In fs/io-wq.c (ffffffff8139c7c7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:create_io_worker
```
```
In fs/crypto/keyring.c (ffffffff813a3407)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a59f7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/posix_acl.c (ffffffff813b6b86)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/proc/generic.c (ffffffff813d2535)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff813e94b8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffff81488fc2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (ffffffff81494fe0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8149872a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff8149cab7)
Location: include/linux/refcount.h:134
Inline: True
```
```
In fs/debugfs/file.c (ffffffff8149fc07)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814a4495)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff814abb8d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff814b28a3)
Location: include/linux/refcount.h:134
Inline: True
```
```
In security/keys/key.c (ffffffff814b47da)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff814eb088)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff814f4a1e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/apparmor/apparmorfs.c (ffffffff8150c3f1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8150f30a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81510083)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8151bdc4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff81526894)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff8153bb48)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff8153d9bd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (ffffffff8155ee45)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff8156a917)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/bsg.c (ffffffff815835b7)
Location: include/linux/refcount.h:134
Inline: True
```
```
In block/bsg-lib.c (ffffffff81583e8d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff81584ca9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/refcount.c (ffffffff815ac2a0)
Location: include/linux/refcount.h:134
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff815fcc13)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/klist.c (ffffffff8160e9c2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81610103)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff8162845a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81675651)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff816ad094)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff81704e83)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/clk/clk.c (ffffffff8171e216)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81724617)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173c404)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8174eae9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81753a1b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8175b3d2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81790e49)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81793a41)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_init
```
```
In drivers/iommu/ioasid.c (ffffffff817bfb92)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_alloc
```
```
In drivers/connector/cn_queue.c (ffffffff817c15b0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/lightnvm/core.c (ffffffff817c3136)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff817c9ab3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff817e9ff5)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff8181d7c1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff81822196)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/dax/bus.c (ffffffff818340ed)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81837ae1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8183c803)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/scsi/scsi_scan.c (ffffffff8184a023)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8185b0ec)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8185f6b9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81862804)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff8189304d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81896c64)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff818a097b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff818aa110)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b2cc0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach
```
```
In drivers/usb/core/hub.c (ffffffff81c1c18a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff818c9244)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff818cc56c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff818d2a86)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff818d3688)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/file.c:init_usb_class
```
```
In drivers/md/dm.c (ffffffff8197c2cd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81980f0d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff819912ef)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff819948ec)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9e5a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff819da684)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock.c (ffffffff819e3898)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff819f4372)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff819f9aa5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81a0566a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81a10df6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81a1353b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81a3457f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81a3912c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/page_pool.c (ffffffff81a3ca55)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/skmsg.c (ffffffff81a3e71b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff81a40fdc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81a42f9e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81a5a61e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff81a6dfd8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81a74f6e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_create
  - net/sched/cls_api.c:tcf_proto_create
```
```
In net/sched/act_api.c (ffffffff81a7b4b0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffff81aa16f4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf09c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aaf9a7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffffffff81abbb8e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ad913b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/devinet.c (ffffffff81aedbee)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81af46e9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81afc526)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81b030c0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81b07fe2)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81b0b750)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffffffff81b11a63)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81b1530e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b19353)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1c492)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81b24d5f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81b34758)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/anycast.c (ffffffff81b3a1af)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b459ee)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5d285)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b6106d)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b6f158)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mca_alloc
```
```
In net/ipv6/exthdrs.c (ffffffff81b7c6a6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff81b854aa)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81b8ccde)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81b9ab05)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81bb8216)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9a54)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/kernel/ioport.c (ffffffff81039e1f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81056b94)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81065d8b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/fork.c (ffffffff810a114b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/user.c (ffffffff810b392e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffff810ca4eb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/core.c (ffffffff810e1f74)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff810f0ad6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/autogroup.c (ffffffff8110545f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff8110ba77)
Location: include/linux/refcount.h:134
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8111f1a9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/namespace.c (ffffffff811571f9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex.c (ffffffff81158073)
Location: include/linux/refcount.h:134
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81170043)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81176c9b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811813ba)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811829c5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811832c3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_watch.c (ffffffff8118f854)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff81190a1b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/kprobes.c (ffffffff81195be9)
Location: include/linux/refcount.h:134
Inline: True
```
```
In kernel/seccomp.c (ffffffff811a52ed)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff811a699d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff811ba395)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/trampoline.c (ffffffff8122707c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
```
In kernel/bpf/btf.c (ffffffff81228c23)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/dispatcher.c (ffffffff81231de6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123c61b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff81241317)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8125321a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81255109)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/watch_queue.c (ffffffff8125bdfc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff81287497)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/zswap.c (ffffffff812d39aa)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff812d89b8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (ffffffff81308655)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (ffffffff8132fc1e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namespace.c (ffffffff8134d285)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff8136c1af)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff8137aa85)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/group.c:__fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff8137af5b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff81386127)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81386b8c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff8138d0c6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/io_uring.c (ffffffff8139254b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_get_sq_data
```
```
In fs/io-wq.c (ffffffff813a395c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:create_io_worker
```
```
In fs/crypto/keyring.c (ffffffff813aa647)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff813aca57)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/posix_acl.c (ffffffff813bdbe6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/proc/generic.c (ffffffff813d9335)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff813f0028)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffff8148e8c7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (ffffffff8149a040)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8149d7ba)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff814a2ae7)
Location: include/linux/refcount.h:134
Inline: True
```
```
In fs/debugfs/file.c (ffffffff814a5bff)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff814aa465)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff814b1a1d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff814b8b00)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff814ba591)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff814f1d81)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff814fb98e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/apparmor/apparmorfs.c (ffffffff81512d71)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81515cfa)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81516917)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff81522494)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff8152c224)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/landlock/object.c (ffffffff81537947)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_create_object
```
```
In security/landlock/ruleset.c (ffffffff81538294)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_create_ruleset
```
```
In crypto/api.c (ffffffff81544238)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff8154609d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (ffffffff81567695)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff8157284f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/bsg.c (ffffffff8158a3c7)
Location: include/linux/refcount.h:134
Inline: True
```
```
In block/bsg-lib.c (ffffffff8158ac8d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff8158b969)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/refcount.c (ffffffff815b6f70)
Location: include/linux/refcount.h:134
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff815df982)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/klist.c (ffffffff815f2152)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff815f3843)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff8160bf3a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81657b81)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff8168f6b4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff816e6550)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/clk/clk.c (ffffffff816ff269)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff817058d7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171ff64)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8173276d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff817378bb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8173f272)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81773f19)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81776bfa)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/iommu/ioasid.c (ffffffff817a2db2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_alloc
```
```
In drivers/connector/cn_queue.c (ffffffff817a4b87)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffffffff817a64d6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff817ad2ac)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ce705)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff81800a31)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff818054a6)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/dax/bus.c (ffffffff818172d9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8181a71f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8181fb4a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8182d7a3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8183e0dc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff818426b9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81845604)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff818754dd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81879115)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81883007)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff8188d660)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81897377)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (ffffffff81c0e070)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff818ac7a4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff818afa9b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff818b6016)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff818b6bf7)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/md/dm.c (ffffffff81963019)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81965119)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff81975852)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff8197981b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819aee6a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff819c00bb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock.c (ffffffff819c9918)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff819da532)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:msg_zerocopy_alloc
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/net_namespace.c (ffffffff819dfc66)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff819ede8a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff819f7c66)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff819f964b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81a1b5ef)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81a203dc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/page_pool.c (ffffffff81a239ae)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/netpoll.c (ffffffff81a25c98)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81a27bee)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81a3c94e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_health_reporter_create
```
```
In net/core/skmsg.c (ffffffff81a4c928)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81a56848)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81a62665)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81a64230)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffff81a8c65d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a3aa)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9acb9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6b4e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ac3f9b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/devinet.c (ffffffff81ad93be)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81adfd25)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae7d3b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81aed718)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81af3842)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af9380)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffffffff81b00312)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81b0311e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81b06dd3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0a182)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1297f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81b22567)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/anycast.c (ffffffff81b27e9b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81b3372c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4b4c0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4f33d)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81b60076)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81b6b266)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff81b7401a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81b7bb8e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81b89a34)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81ba73d8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8a34)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/kernel/ioport.c (ffffffff8103f7cf)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8105f7b0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8106feab)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/fork.c (ffffffff810b256b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/user.c (ffffffff810c5ace)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffff810dd33b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/core.c (ffffffff810f8222)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff81109556)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/autogroup.c (ffffffff811230cf)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/core_sched.c (ffffffff8112c5a9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
```
```
In kernel/irq/manage.c (ffffffff8113f639)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/namespace.c (ffffffff8117c049)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex.c (ffffffff8117cfa3)
Location: include/linux/refcount.h:134
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81196483)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8119e51b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811a932a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811aa995)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811ab37d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_watch.c (ffffffff811b8734)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff811b98fb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/kprobes.c (ffffffff811beb52)
Location: include/linux/refcount.h:134
Inline: True
```
```
In kernel/seccomp.c (ffffffff811cea3d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff811d018d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff811e4bbc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/trampoline.c (ffffffff8125f17c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
```
In kernel/bpf/btf.c (ffffffff81260f13)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/dispatcher.c (ffffffff8126ae66)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81276fd5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff8127bd4b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8128eb1b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81290b49)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff81293e4b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/watch_queue.c (ffffffff81297cac)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff812c6e17)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
```
```
In mm/zswap.c (ffffffff8131962c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8131ecc8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (ffffffff81352725)
Location: include/linux/refcount.h:134
Inline: True
```
```
In fs/exec.c (ffffffff8137d247)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namespace.c (ffffffff8139b255)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff813bae7f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff813c7766)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/group.c:__fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff813c7bbb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff813d33f7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff813d3e8c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff813da826)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/io_uring.c (ffffffff813e0567)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_get_sq_data
```
```
In fs/io-wq.c (ffffffff813f166e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
```
```
In fs/crypto/keyring.c (ffffffff813f9ed7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc3c7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/posix_acl.c (ffffffff8140d9ec)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/proc/generic.c (ffffffff8142aa65)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff81441f18)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffff814e6337)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (ffffffff814f1a69)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff814f526a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff814fab81)
Location: include/linux/refcount.h:134
Inline: True
```
```
In fs/debugfs/file.c (ffffffff814fdd9f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81502985)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff81509fcd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff81511330)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff81512dc1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff8154c45e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff815565fe)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/apparmor/apparmorfs.c (ffffffff81570971)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81573cfa)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81574917)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff815806e4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff8158a612)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/landlock/object.c (ffffffff81596147)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_create_object
```
```
In security/landlock/ruleset.c (ffffffff8159695a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_create_ruleset
```
```
In crypto/api.c (ffffffff815a49d8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff815a686d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-flush.c (ffffffff815d0679)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-mq.c (ffffffff815d6e7f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/bsg-lib.c (ffffffff815efd5d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff815f0c84)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/refcount.c (ffffffff8161d520)
Location: include/linux/refcount.h:134
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff8164b5c2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/klist.c (ffffffff8165f4e4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff81660a13)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff8167ac4a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c9bb0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff816de956)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff81705114)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff8175f8a0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/clk/clk.c (ffffffff81779b30)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81780e27)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179f024)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff817b305f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff817b834b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff817bfa02)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff817fa2f9)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff817fc5ca)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/iommu/ioasid.c (ffffffff8182c0f2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/iommu/ioasid.c:ioasid_alloc
```
```
In drivers/connector/cn_queue.c (ffffffff81830507)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/base/core.c (ffffffff818365a2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81858fb5)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff8188ae31)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff8188fb36)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/dax/bus.c (ffffffff818a1929)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff818a49fb)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff818aa20a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff818b91f3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff818cab9b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff818cf7c9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff818d2094)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff81905fad)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81909f65)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff819149a7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff81920bc0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/usb/core/hub.c (ffffffff81d1514a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff819417f4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81944beb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffff8194b66d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff8194c59a)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/md/dm.c (ffffffff81a0a03e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81a0d099)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff81a1e56a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff81a2282b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5d46a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff81a6f80b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock.c (ffffffff81a78cd1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81a8a542)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:msg_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/net_namespace.c (ffffffff81a90066)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81a9f12a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81aa9896)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81aac69b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81aceccf)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81ad45b5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/page_pool.c (ffffffff81ad7fde)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/netpoll.c (ffffffff81ada9f8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81adc98e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81af6122)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:__devlink_health_reporter_create
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
```
```
In net/core/skmsg.c (ffffffff81b060c8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81b0f644)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81b1b966)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81b1d5d0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffff81b4779d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b5581a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b574cb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_input.c (ffffffff81b6314e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81b8262b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/devinet.c (ffffffff81b98423)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81b9f2b3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba7bd6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81badad8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81bb3d62)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb9ed0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffffffff81bc2402)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81bc535e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81bc9c48)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bccfb1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd681f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81be9270)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/anycast.c (ffffffff81bedddb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81bf9d9c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/ip6_fib.c (ffffffff81c12800)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c1664d)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81c27946)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81c330c6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e8c9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81c4688e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81c55b44)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81c74f38)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c76784)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
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
In arch/x86/kernel/ioport.c (ffffffff81046efb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8106c076)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8107d7bd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/fork.c (ffffffff810ca86c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/user.c (ffffffff810dd0ce)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffff810f6c52)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/core.c (ffffffff811144e7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff8111da2a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/build_utility.c (ffffffff81144d4e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/sched/build_utility.c:sched_core_share_pid
```
```
In kernel/irq/manage.c (ffffffff811630cd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/namespace.c (ffffffff811b1799)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex/pi.c (ffffffff811b4af9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/futex/pi.c:refill_pi_state_cache
```
```
In kernel/cgroup/cgroup.c (ffffffff811c63d3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff811ce948)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811da475)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811dbff0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811dcae6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_watch.c (ffffffff811eb661)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff811eca1a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/seccomp.c (ffffffff81202b67)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff81205367)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff8121bf33)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/rethook.c (ffffffff812690dc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_alloc
```
```
In kernel/bpf/trampoline.c (ffffffff812a97e3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
```
In kernel/bpf/btf.c (ffffffff812ac5bb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/dispatcher.c (ffffffff812b99f1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c6c14)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff812cfabd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff812e3a1f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff812e5980)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff812e9e77)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/watch_queue.c (ffffffff812edf8c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff81324206)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
```
```
In mm/madvise.c (ffffffff81377f50)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/zswap.c (ffffffff81384918)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8138b4c7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (ffffffff813cb6e6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (ffffffff813fce3b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/namespace.c (ffffffff8141eab9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff81440c69)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff8144eb69)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff8144f2eb)
Location: include/linux/refcount.h:134
Inline: True
```
```
In fs/eventfd.c (ffffffff8145c9c5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff8145d88c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/userfaultfd.c:__do_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff81465222)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/crypto/keyring.c (ffffffff8146d0a4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_new_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f84e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/posix_acl.c (ffffffff81482f3c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/proc/generic.c (ffffffff814a403d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff814bdb6c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/page-io.c (ffffffff81508dbb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/fuse/dev.c (ffffffff81574ec2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (ffffffff815814d5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8158531a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff8158b17c)
Location: include/linux/refcount.h:134
Inline: True
```
```
In fs/debugfs/file.c (ffffffff8158e9ab)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81593f05)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff8159bd25)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff815a3162)
Location: include/linux/refcount.h:134
Inline: True
```
```
In security/keys/key.c (ffffffff815a51d3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff815e52ee)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff815f09da)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/apparmor/apparmorfs.c (ffffffff8160d2ad)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff816115f9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff816123f1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8161f8cb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff8162ba7c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/landlock/object.c (ffffffff816384c7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_create_object
```
```
In security/landlock/ruleset.c (ffffffff81638e5c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_create_ruleset
```
```
In crypto/api.c (ffffffff8164b82c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff8164c90d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/bsg-lib.c (ffffffff816a0d0a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff816a211a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In io_uring/io_uring.c (ffffffff81e8ebe7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_alloc_task_context
  - io_uring/io_uring.c:io_get_sq_data
```
```
In io_uring/io-wq.c (ffffffff816da74e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
```
```
In lib/refcount.c (ffffffff816eb36b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/cpu_rmap.c (ffffffff81762022)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/klist.c (ffffffff81778c17)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff8177a54b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In drivers/pinctrl/core.c (ffffffff81796308)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817efe94)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff818087c1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff818331d4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff81893203)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/clk/clk.c (ffffffff818afe6c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff818b75c8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d8c14)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff818eeaa6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff818f42e5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff818fc022)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff819376cf)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff8193b225)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/connector/cn_queue.c (ffffffff81971807)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/base/core.c (ffffffff819785a2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff8199f7a1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff819d456d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff819d9574)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/dax/bus.c (ffffffff819eb062)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff819ee60d)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff819f4a3a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff81a04e63)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sg.c (ffffffff81a1dfde)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81a22614)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff81a58d70)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81a5d662)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69fbd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff81a772e0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:__vfio_register_dev
  - drivers/vfio/vfio.c:vfio_create_group
```
```
In drivers/usb/core/hub.c (ffffffff81edfcec)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81a9a1f0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81a9c65f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81ee1a4d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81aa5093)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/md/dm.c (ffffffff81b73520)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81b759f9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff81b86ce5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff81b8b8d9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcd59a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff81be0bf3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock.c (ffffffff81bec748)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81bff9a2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
```
```
In net/core/net_namespace.c (ffffffff81c05e85)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81c0f38a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81c21cc6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81c25577)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81c4c369)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81c52b57)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/page_pool.c (ffffffff81c58d52)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/netpoll.c (ffffffff81c5c107)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81c5ddce)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81c7e993)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_linecard_create
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:__devlink_health_reporter_create
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
```
```
In net/core/skmsg.c (ffffffff81c8b418)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81c96811)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81ca2ce6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81ca4baf)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffff81cd49b3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3514)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5458)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1df2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d08c5e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81d12b59)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/devinet.c (ffffffff81d2a270)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81d316c8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3a57a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81d4223a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81d475c3)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81d4ded5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffffffff81d571e2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81d5a522)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81d5f2da)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62ed3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6d0ef)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81d7ff0f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create_addr
```
```
In net/ipv6/anycast.c (ffffffff81d86339)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81d93175)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/ip6_fib.c (ffffffff81dadcfe)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db1d27)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81dc4cc5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81dd0825)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff81ddd07b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81de531d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81df1b7d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81e19164)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1a61c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
```
In net/mctp/device.c (ffffffff81e38368)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
```
```
In net/mctp/route.c (ffffffff81e399f2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_key_alloc
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
In arch/x86/kernel/ioport.c (ffffffff8105105b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107c090)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff8108ed1d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/fork.c (ffffffff810e4ebb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/user.c (ffffffff810fd3ee)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffff81119332)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/core.c (ffffffff8113b827)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff81144dcd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/build_utility.c (ffffffff8117113e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/sched/build_utility.c:sched_core_share_pid
```
```
In kernel/irq/manage.c (ffffffff81196cdd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/namespace.c (ffffffff811f24e9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex/pi.c (ffffffff811f5bb9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/futex/pi.c:refill_pi_state_cache
```
```
In kernel/cgroup/cgroup.c (ffffffff81208ea3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff812121c8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8121fa35)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81221850)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81222446)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_watch.c (ffffffff81231a61)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff81232f5a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/seccomp.c (ffffffff8124a9c7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff8124d438)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff81265c04)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/rethook.c (ffffffff812bb41c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_alloc
```
```
In kernel/bpf/trampoline.c (ffffffff8130867c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff8130bf3b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/dispatcher.c (ffffffff8131cbbc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132c484)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/events/core.c (ffffffff83eb950a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8134c0cf)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff8134f528)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff81353dda)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/watch_queue.c (ffffffff813583bc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff81398b06)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
```
```
In mm/madvise.c (ffffffff813f5850)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/zswap.c (ffffffff81402548)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81408ba7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memory-tiers.c (ffffffff83ec697e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
```
```
In mm/memcontrol.c (ffffffff814503b6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (ffffffff81483e2e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/namespace.c (ffffffff814ab529)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff814cfb69)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff814dd2fe)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff814ddb1b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff814ec0a5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff814ecd85)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff814f5262)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/crypto/keyring.c (ffffffff814fe827)
Location: include/linux/refcount.h:134
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff8150101e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/posix_acl.c (ffffffff815161a8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/proc/generic.c (ffffffff8153944d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff8155589c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/page-io.c (ffffffff815a392b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/fuse/dev.c (ffffffff81619563)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff81627335)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8162b51a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff8163197c)
Location: include/linux/refcount.h:134
Inline: True
```
```
In fs/debugfs/file.c (ffffffff81635a3b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8163cac5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff81645115)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff8164cd12)
Location: include/linux/refcount.h:134
Inline: True
```
```
In security/keys/key.c (ffffffff8164efc3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff8169473e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff816a0e0a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/apparmor/apparmorfs.c (ffffffff816bf21d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff816c4299)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff816c50a1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff816d2cdb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff816e035b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/notify.c (ffffffff816ea702)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_new_listener
```
```
In security/landlock/object.c (ffffffff816ef927)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_create_object
```
```
In security/landlock/ruleset.c (ffffffff816f037c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_create_ruleset
```
```
In crypto/api.c (ffffffff817048cc)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff81705153)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (ffffffff817354d0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
```
```
In block/bsg-lib.c (ffffffff8175f8aa)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff817617ec)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In io_uring/sqpoll.c (ffffffff8179a0da)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/tctx.c (ffffffff8179bbf6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In io_uring/notif.c (ffffffff817a5312)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
```
```
In io_uring/io-wq.c (ffffffff817a683e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
```
```
In lib/refcount.c (ffffffff817dba1b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/cpu_rmap.c (ffffffff818911e3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff818ab9be)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81918044)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff819368aa)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff81966cb4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff819dabee)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/clk/clk.c (ffffffff819fc1bf)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81a044f8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2b674)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff81a46706)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81a4cb54)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff81a55592)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81a97bdf)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81a9b8fc)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/connector/cn_queue.c (ffffffff81adc89c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/base/core.c (ffffffff81ae4e5c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b11241)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81b4edbd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff81b54654)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81b67bc2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81b6baad)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81b71e9a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/hosts.c (ffffffff81b76e66)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81b83b13)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sg.c (ffffffff81b9f30e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81ba3d54)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff81be2af0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81be8212)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfcbbd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hub.c (ffffffff81c1cb36)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81c1e770)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81c215cf)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81c2a6d9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81c2ba33)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/md/dm.c (ffffffff81d10027)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81d12d29)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff81d25cc6)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/opp/core.c (ffffffff81d2aff1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/nvmem/core.c (ffffffff81d8c4dd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock.c (ffffffff81d9a5c6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81da4eef)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
```
```
In net/core/net_namespace.c (ffffffff81db5785)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81dbf10d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81dd3f06)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81dd8907)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81e010e9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81e08117)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/page_pool.c (ffffffff81e0ec42)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/netpoll.c (ffffffff81e125b2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81e145be)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81e376a3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_linecard_create
  - net/core/devlink.c:devlink_alloc_ns
  - net/core/devlink.c:__devlink_health_reporter_create
  - net/core/devlink.c:devlink_nl_cmd_rate_new_doit
```
```
In net/core/skmsg.c (ffffffff81e47823)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81e52420)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81e6051b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81e6196f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffff81e94c93)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea59e4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8648)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_input.c (ffffffff81eb6662)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecd7f8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ed8a01)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/devinet.c (ffffffff81ef1d60)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81ef9ea7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02eda)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f0b07a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81f10a43)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f17815)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffffffff81f2087f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81f24952)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f2997a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2daa1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3855f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81f4bc71)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create_addr
```
```
In net/ipv6/anycast.c (ffffffff81f53e89)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81f61905)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7d7b2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f80b32)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/mcast.c (ffffffff81f95815)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81fa1bf5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff81fae501)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81fb7aed)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81fc5b4d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/xdp/xdp_umem.c (ffffffff81ff0304)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff1b39)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
```
In net/mctp/device.c (ffffffff820115c8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
```
```
In net/mctp/route.c (ffffffff82012ac2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_key_alloc
```
```
In lib/klist.c (ffffffff82021a07)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff820230ae)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
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
In arch/x86/kernel/ioport.c (ffffffff81051d8c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107e3f8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81091c0d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/fork.c (ffffffff810f055b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/user.c (ffffffff8110941e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffff81126802)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/core.c (ffffffff8114ec96)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff811552e6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/build_utility.c (ffffffff8118193e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/sched/build_utility.c:sched_core_share_pid
```
```
In kernel/irq/manage.c (ffffffff811a878d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/namespace.c (ffffffff81206c69)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex/pi.c (ffffffff8120a3b9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/futex/pi.c:refill_pi_state_cache
```
```
In kernel/cgroup/cgroup.c (ffffffff8121e5b2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff81227b0c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81235c25)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81237d05)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81238a7d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_watch.c (ffffffff812486f1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_to_watch
```
```
In kernel/audit_tree.c (ffffffff81249be1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/seccomp.c (ffffffff81261cc7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff812647b8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff8127cf74)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/trace_events_user.c (ffffffff812c67b4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
  - kernel/trace/trace_events_user.c:delayed_destroy_user_event
```
```
In kernel/trace/rethook.c (ffffffff812df03c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_alloc
```
```
In kernel/bpf/syscall.c (ffffffff812f28ac)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff81320ca6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_obj_new_impl
```
```
In kernel/bpf/hashtab.c (ffffffff8132b523)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
```
```
In kernel/bpf/arraymap.c (ffffffff8132d176)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff81332478)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/trampoline.c (ffffffff8133745c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff8133af9b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/dispatcher.c (ffffffff8134c8c1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135d1b4)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/bpf/cpumask.c (ffffffff8135d57b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_create
```
```
In kernel/events/core.c (ffffffff836deb3a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8137d11f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff813806f8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff81384fda)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/watch_queue.c (ffffffff81389c4c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/backing-dev.c (ffffffff813cba66)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
```
```
In mm/madvise.c (ffffffff814285a0)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/zswap.c (ffffffff81435401)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8143c217)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memory-tiers.c (ffffffff836eb96e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
```
```
In mm/memcontrol.c (ffffffff81485ea6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (ffffffff814b866e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/namespace.c (ffffffff814e0329)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff81505e26)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/mnt_idmapping.c (ffffffff81506d63)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/mnt_idmapping.c:alloc_mnt_idmap
```
```
In fs/notify/group.c (ffffffff81513b5e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff815142fb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventpoll.c (ffffffff8151e849)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/eventfd.c (ffffffff81523265)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81523ab5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff8152c032)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/crypto/keyring.c (ffffffff81535cf7)
Location: include/linux/refcount.h:134
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff815386ae)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/posix_acl.c (ffffffff8154db28)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/proc/generic.c (ffffffff8157168d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff8158d63c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/page-io.c (ffffffff815da3bb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/fuse/dev.c (ffffffff816516b3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff8165f6f5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8166374a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/fuse/dax.c (ffffffff81669bbc)
Location: include/linux/refcount.h:134
Inline: True
```
```
In fs/debugfs/file.c (ffffffff8166dd43)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81674fd5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff8167d600)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff8168551b)
Location: include/linux/refcount.h:134
Inline: True
```
```
In security/keys/key.c (ffffffff8168782c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff816ccc31)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff816d974a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/apparmor/apparmorfs.c (ffffffff816f7d2d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/audit.c (ffffffff816fa678)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/lib.c (ffffffff816fce69)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff816fdae7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy.c (ffffffff8170614e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_pdb
```
```
In security/apparmor/policy_unpack.c (ffffffff8170bcdb)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff8171998c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/notify.c (ffffffff817245a2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_new_listener
```
```
In security/landlock/object.c (ffffffff81729dd7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_create_object
```
```
In security/landlock/ruleset.c (ffffffff8172a737)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_create_ruleset
```
```
In crypto/api.c (ffffffff8173e968)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/api.c:__crypto_alloc_tfmgfp
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff8173f423)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (ffffffff81771a53)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
```
```
In block/bsg-lib.c (ffffffff8179e78d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff817a09d9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In io_uring/sqpoll.c (ffffffff817db13a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/tctx.c (ffffffff817dcd26)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In io_uring/notif.c (ffffffff817e62e2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
```
```
In io_uring/io-wq.c (ffffffff817e77b5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
```
```
In lib/refcount.c (ffffffff8181ac8b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/cpu_rmap.c (ffffffff818d3443)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff818ee8fe)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195b666)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8197a93a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff819ad251)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff81a2280a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/clk/clk.c (ffffffff81a44c64)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81a4d358)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a74e14)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff81a908b7)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81a96e44)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff81a9fb72)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81ae33f9)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81ae7254)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/connector/cn_queue.c (ffffffff81b2ab0c)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/base/core.c (ffffffff81b331fe)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5f576)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81ba220d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff81ba7ba4)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81bbad4a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81bbf30f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc559f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/scsi/hosts.c (ffffffff81bcaaf6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81bd786e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sg.c (ffffffff81bf5a2e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81bfa454)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3a741)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81c405b2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81c6223d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hub.c (ffffffff81c83a3a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81c85670)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81c8854f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81c9166e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff81c929e3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/md/dm.c (ffffffff81d79487)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff82148904)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff81d8eedc)
Location: include/linux/refcount.h:134
Inline: True
```
```
In drivers/opp/core.c (ffffffff81d94276)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/nvmem/core.c (ffffffff81dfab70)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In net/core/sock.c (ffffffff81e08e26)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81e13aaf)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
```
```
In net/core/net_namespace.c (ffffffff81e25d55)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81e2eddd)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dev.c:dev_kfree_skb_irq_reason
```
```
In net/core/dst.c (ffffffff81e44b66)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81e49667)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81e72ba9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81e7aa37)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/page_pool.c (ffffffff81e822c9)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/netpoll.c (ffffffff81e85df2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81e87ece)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/skmsg.c (ffffffff81ea1cb3)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81eadc90)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81ebb60b)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81ebde1f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffff81ef3463)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f04176)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06ec8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_input.c (ffffffff81f14a82)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c4ae)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81f37b11)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/devinet.c (ffffffff81f51850)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81f59947)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81f628d1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81f6ac3e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81f70733)
Location: include/linux/refcount.h:134
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81f774f5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffffffff81f8109f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81f844e2)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81f8952a)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8d771)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81f97f4f)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81faba21)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create_addr
```
```
In net/ipv6/anycast.c (ffffffff81fb3879)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81fc1737)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdd9bf)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe09a6)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/mcast.c (ffffffff81ff61c5)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff82002475)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff8200f981)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff8201828d)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff8202a097)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/devlink/leftover.c (ffffffff8203e942)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_cmd_rate_new_doit
```
```
In net/devlink/core.c (ffffffff820420ed)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
```
```
In net/xdp/xdp_umem.c (ffffffff8206c4af)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206dd37)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
```
In net/mctp/device.c (ffffffff8208e3a8)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
```
```
In net/mctp/route.c (ffffffff8208f8c1)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_key_alloc
```
```
In lib/klist.c (ffffffff820a1a47)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff820a311e)
Location: include/linux/refcount.h:134
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
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
In arch/x86/kernel/ioport.c (ffffffff81058fac)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/ioport.c:ksys_ioperm
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81085907)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81098fec)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In kernel/fork.c (ffffffff810f98bb)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/fork.c:copy_signal
  - kernel/fork.c:copy_sighand
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/user.c (ffffffff81112db1)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffff81130df2)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/nsproxy.c (ffffffff8113bda1)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/groups.c (ffffffff81143ae3)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/groups.c:__do_sys_setgroups
```
```
In kernel/sched/core.c (ffffffff8115ab21)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
```
In kernel/sched/fair.c (ffffffff81161d46)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_group
```
```
In kernel/sched/build_utility.c (ffffffff8119021d)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:autogroup_init
  - kernel/sched/build_utility.c:sched_core_share_pid
```
```
In kernel/irq/manage.c (ffffffff811b820d)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/time/namespace.c (ffffffff8121de79)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/futex/pi.c (ffffffff81221902)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/futex/pi.c:refill_pi_state_cache
```
```
In kernel/cgroup/cgroup.c (ffffffff81236245)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8123f91c)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8124f8a5)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81251805)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8125274d)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In kernel/audit_watch.c (ffffffff8126239e)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff81263af1)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/audit_tree.c:alloc_tree
```
```
In kernel/seccomp.c (ffffffff8127bef6)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff8127e5db)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff81297eb0)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/trace/trace_events_user.c (ffffffff812e326a)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_events_user.c:user_event_parse
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
  - kernel/trace/trace_events_user.c:user_event_mm_alloc
  - kernel/trace/trace_events_user.c:delayed_destroy_user_event
```
```
In kernel/bpf/syscall.c (ffffffff8131174f)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
```
In kernel/bpf/helpers.c (ffffffff813431ac)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_obj_new_impl
```
```
In kernel/bpf/hashtab.c (ffffffff8134f9d9)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
```
```
In kernel/bpf/arraymap.c (ffffffff813514dc)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
```
```
In kernel/bpf/local_storage.c (ffffffff81356a2e)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
```
In kernel/bpf/trampoline.c (ffffffff8135d33a)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff81361129)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/dispatcher.c (ffffffff81373dda)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff813858c4)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_sys_lookup_elem
```
```
In kernel/bpf/cpumask.c (ffffffff813862db)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/bpf/cpumask.c:bpf_cpumask_create
```
```
In kernel/events/core.c (ffffffff8391117a)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff813a637f)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff813a9aa7)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/events/uprobes.c:alloc_uprobe
```
```
In kernel/padata.c (ffffffff813ae349)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/watch_queue.c (ffffffff813b36cb)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
  - kernel/watch_queue.c:init_watch
```
```
In mm/shrinker.c (ffffffff813e3abe)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - mm/shrinker.c:shrinker_register
```
```
In mm/backing-dev.c (ffffffff813f63a6)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_init
```
```
In mm/madvise.c (ffffffff81461e50)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - mm/madvise.c:anon_vma_name_alloc
```
```
In mm/zswap.c (ffffffff8146e617)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff814769ce)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memory-tiers.c (ffffffff8149afa1)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - mm/memory-tiers.c:alloc_memory_type
```
```
In mm/memcontrol.c (ffffffff814b4e3f)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (ffffffff814eab7e)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/exec.c:unshare_sighand
```
```
In fs/namespace.c (ffffffff815135f5)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In fs/fsopen.c (ffffffff8153aacb)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/fsopen.c:fscontext_alloc_log
```
```
In fs/mnt_idmapping.c (ffffffff8153bb2f)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/mnt_idmapping.c:alloc_mnt_idmap
```
```
In fs/notify/group.c (ffffffff81547ff5)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff815487cb)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventpoll.c (ffffffff81552e4a)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/eventfd.c (ffffffff81557994)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81558035)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/userfaultfd.c:new_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff81560f12)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/crypto/keyring.c (ffffffff8156acf4)
Location: include/linux/refcount.h:123
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d82d)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
```
In fs/backing-file.c (ffffffff815818ae)
Location: include/linux/refcount.h:123
Inline: True
```
```
In fs/posix_acl.c (ffffffff81583974)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
  - fs/posix_acl.c:posix_acl_clone
```
```
In fs/proc/generic.c (ffffffff815aa03d)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff815c637c)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/ext4/page-io.c (ffffffff81612b7b)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_init_io_end
```
```
In fs/fuse/dev.c (ffffffff8168acc3)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff81699564)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8169d83a)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/dax.c (ffffffff816a3ef0)
Location: include/linux/refcount.h:123
Inline: True
```
```
In fs/debugfs/file.c (ffffffff816a84d8)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In fs/tracefs/event_inode.c (ffffffff816abe29)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
  - fs/tracefs/event_inode.c:eventfs_create_dir
```
```
In ipc/util.c (ffffffff816b1395)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff816b99d0)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff816c193b)
Location: include/linux/refcount.h:123
Inline: True
```
```
In security/keys/key.c (ffffffff816c3d3c)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff81709249)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/smack/smack_access.c (ffffffff817161c5)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/apparmor/apparmorfs.c (ffffffff81734a9d)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/audit.c (ffffffff81737288)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - security/apparmor/audit.c:aa_dup_audit_data
```
```
In security/apparmor/lib.c (ffffffff8173a3c9)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff8173b075)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy.c (ffffffff81743a8a)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_pdb
```
```
In security/apparmor/policy_unpack.c (ffffffff817499ba)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff8175842c)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/notify.c (ffffffff817658e9)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_new_listener
```
```
In security/landlock/object.c (ffffffff8176b147)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - security/landlock/object.c:landlock_create_object
```
```
In security/landlock/ruleset.c (ffffffff8176bdd7)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_merge_ruleset
  - security/landlock/ruleset.c:landlock_create_ruleset
```
```
In crypto/api.c (ffffffff8177f7e8)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - crypto/api.c:__crypto_alloc_tfmgfp
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff817802a3)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (ffffffff817b3d97)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - block/blk-core.c:blk_alloc_queue
```
```
In block/bsg-lib.c (ffffffff817e2209)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff817e4538)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In io_uring/sqpoll.c (ffffffff8181f459)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/tctx.c (ffffffff8182103a)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In io_uring/notif.c (ffffffff8182a502)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
```
```
In io_uring/io-wq.c (ffffffff8182d5c4)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
```
```
In lib/refcount.c (ffffffff8186000b)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - lib/refcount.c:refcount_dec_and_lock_irqsave
  - lib/refcount.c:refcount_dec_and_lock
  - lib/refcount.c:refcount_dec_and_mutex_lock
```
```
In lib/cpu_rmap.c (ffffffff81925523)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In lib/stackdepot.c (ffffffff81928287)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - lib/stackdepot.c:depot_alloc_stack
  - lib/stackdepot.c:depot_alloc_stack
```
```
In drivers/pinctrl/core.c (ffffffff819360bd)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a4c4a)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff819c409b)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/acpi/ec.c (ffffffff819f76d0)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/thermal.c (ffffffff81a6d155)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/clk/clk.c (ffffffff81a90774)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81a98ff8)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
  - drivers/dma/dmaengine.c:dma_async_device_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac6fa3)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff81ae3329)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81ae9864)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff81af25c2)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81b367e8)
Location: include/linux/refcount.h:123
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff81b3a624)
Location: include/linux/refcount.h:123
Inline: True
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b81080)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_bind_device
```
```
In drivers/connector/cn_queue.c (ffffffff81b81dbb)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/base/core.c (ffffffff81b8ab3d)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb2f85)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/nvdimm/core.c (ffffffff81bf63cc)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/dimm.c (ffffffff81bfbf33)
Location: include/linux/refcount.h:123
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81c0f554)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c13a8e)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
  - drivers/dma-buf/dma-fence.c:dma_fence_get_stub
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c19dbe)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/scsi/hosts.c (ffffffff81c1f726)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2c50e)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sg.c (ffffffff81c4b3cd)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
```
```
In drivers/ata/libata-core.c (ffffffff81c4fe74)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7b275)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_state_init
```
```
In drivers/gpu/drm/drm_auth.c (ffffffff81c7e897)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_auth.c:drm_master_create
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c87331)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tile_group
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8b7e2)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9b73c)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_private_object_init
```
```
In drivers/gpu/drm/drm_mode_object.c (ffffffff81ca3e70)
Location: include/linux/refcount.h:123
Inline: True
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cafd80)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc3ed1)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf03c0)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81cf5c11)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/refcount.h:123
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18c6c)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hub.c (ffffffff81d38419)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff81d3a2b4)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff81d3cf9f)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81d4622e)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/md/dm.c (ffffffff81e30626)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff8222b336)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff81e467ec)
Location: include/linux/refcount.h:123
Inline: True
```
```
In drivers/opp/core.c (ffffffff81e4bd96)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_add_opp_table_indexed
```
```
In drivers/nvmem/core.c (ffffffff81eb1bef)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb6bad)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_pin_get
  - drivers/dpll/dpll_core.c:dpll_device_get
  - drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add
```
```
In net/core/sock.c (ffffffff81ec5896)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data_uid
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81ed0c6f)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:__skb_ext_alloc
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:slab_build_skb
```
```
In net/core/net_namespace.c (ffffffff81ee3ce4)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81eeda5d)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/core/dev.c:dev_kfree_skb_irq_reason
```
```
In net/core/dst.c (ffffffff81f037e5)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81f08355)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/core/filter.c (ffffffff81f3231c)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/flow_offload.c (ffffffff81f3ac06)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/core/page_pool.c (ffffffff81f432a8)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_init
```
```
In net/core/netpoll.c (ffffffff81f47e04)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81f49eda)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/skmsg.c (ffffffff81f65f66)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/sched/sch_generic.c (ffffffff81f70720)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81f7e82d)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff81f8102f)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffff81fb73f3)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc84c6)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb1e8)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8fa3)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff1431)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffdbe1)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child
```
```
In net/ipv4/devinet.c (ffffffff82017b0f)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff8201fe37)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff82028ea1)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff820312ee)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff82036e92)
Location: include/linux/refcount.h:123
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff8203dcc5)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffffffff8204771f)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff8204ae8d)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204cf53)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
```
```
In net/ipv4/cipso_ipv4.c (ffffffff82050c8a)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/ipv4/tcp_ao.c (ffffffff8205438d)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_alloc_info
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205b118)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff820652bf)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff82078e40)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create_addr
```
```
In net/ipv6/anycast.c (ffffffff8208111e)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8208ec6f)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_dev
```
```
In net/ipv6/ip6_fib.c (ffffffff820ab03d)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820aefb9)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/mcast.c (ffffffff820c3e04)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff820d1275)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff820de911)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff820e725d)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff820f9b95)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/devlink/core.c (ffffffff820fec27)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_alloc_ns
  - net/devlink/core.c:devlink_rel_nested_in_add
```
```
In net/devlink/rate.c (ffffffff82119501)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/devlink/rate.c:devlink_nl_rate_new_doit
```
```
In net/xdp/xdp_umem.c (ffffffff821402ad)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82141db6)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
  - net/xdp/xsk_buff_pool.c:xp_create_and_assign_umem
```
```
In net/mctp/device.c (ffffffff8216489b)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
```
```
In net/mctp/route.c (ffffffff82165dd0)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_key_alloc
```
```
In lib/klist.c (ffffffff82179ac7)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - lib/klist.c:klist_add_before
  - lib/klist.c:klist_add_behind
  - lib/klist.c:klist_add_tail
  - lib/klist.c:klist_add_head
```
```
In lib/kobject.c (ffffffff8217b199)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
```
```
In lib/objpool.c (ffffffff82191cf2)
Location: include/linux/refcount.h:123
Inline: True
Inline callers:
  - lib/objpool.c:objpool_init
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
In virt/kvm/kvm_main.c (ffff8000100bca3c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_create_vm
```
```
In virt/kvm/arm/vgic/vgic-init.c (ffff8000100dde00)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_vcpu_init
```
```
In virt/kvm/arm/vgic/vgic-its.c (ffff8000100e8780)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/fork.c (ffff8000100f39c0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:dup_task_struct
```
```
In kernel/user.c (ffff80001010a564)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffff800010124758)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/fair.c (ffff800010148f7c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/autogroup.c (ffff80001015f0dc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffff800010167e9c)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/irq/manage.c (ffff800010179e8c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/futex.c (ffff8000101b67a0)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffff8000101d2670)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffff8000101da3a4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffff8000101e52d4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffff8000101e785c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_watch.c (ffff8000101f30ac)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffff8000101f5b3c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/seccomp.c (ffff800010209880)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffff80001020aa98)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffff800010220e30)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/btf.c (ffff800010285a64)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffff800010293704)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffff8000102a3130)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffff8000102a6be8)
Location: include/linux/refcount.h:30
Inline: True
```
```
In mm/backing-dev.c (ffff8000102df344)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffff80001032b2b4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffff800010331020)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (ffff800010366304)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (ffff80001038e77c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/fsopen.c (ffff8000103d70a0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fsopen.c:__arm64_sys_fspick
  - fs/fsopen.c:__arm64_sys_fsopen
```
```
In fs/notify/group.c (ffff8000103e8e38)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffff8000103e92b4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffff8000103f5dfc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffff8000103f6d80)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/userfaultfd.c:__arm64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffff8000103fd98c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/io_uring.c (ffff800010401e64)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keyring.c (ffff80001040d620)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (ffff80001040fa68)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/posix_acl.c (ffff8000104262c4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/proc/generic.c (ffff8000104434f8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffff80001045df7c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffff8000105015e4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffff80001050e288)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffff80001051234c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffff800010517044)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffff80001051d1d4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffff8000105257ac)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffff80001052cd08)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffff80001052eb30)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffff80001056862c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (ffff80001058d04c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffff80001058f820)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffff8000105904d4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffff800010599a74)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffff8000105a1fcc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffff8000105b76a4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffff8000105b8bb0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (ffff8000105e0158)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffff8000105ef990)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffff800010609a6c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffff80001060b120)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffff80001060ba50)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/cpu_rmap.c (ffff8000106625a4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001147314c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_irq_nmi_setup
```
```
In drivers/pinctrl/core.c (ffff80001068d5a8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b6298)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pmx_request
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffff8000107131cc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffff80001076ffa0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffff8000107c27a0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffff8000107fcda8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/soc/qcom/smem_state.c (ffff80001081dab0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/soc/qcom/smem_state.c:qcom_smem_state_register
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff800010839efc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffff80001084c3ec)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffff800010853678)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffff80001085ddf8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffff8000108b5300)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffff8000108b71c8)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/connector/cn_queue.c (ffff8000108dd354)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffff8000108dee94)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffff8000108e64fc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffff80001090d5a8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffff80001094feec)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffff800010954f0c)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dax/bus.c (ffff800010964080)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffff800010966400)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (ffff80001096ae80)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffff80001097bb58)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffff80001098c894)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffff800010991720)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffff80001099700c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffff8000109d9b50)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffff800010a00358)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hub.c (ffff800010a1a1f0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffff800010a1bcb0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffff800010a1ff6c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffff800010a27eb4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffff800010a29110)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffff800010ac37a0)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/md/dm.c (ffff800010afca88)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffff800010b02a04)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/edac/ghes_edac.c (ffff800010b15434)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffff800010b1a66c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:_opp_get_opp_table
```
```
In drivers/opp/of.c (ffff800010b1bf48)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b809b8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffff800010b9fb58)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/core/sock.c (ffff800010ba9aa4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffff800010bb26ac)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffff800010bc1fb8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffff800010bce0a0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffff800010be06c0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffff800010be24c4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffff800010c02304)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (ffff800010c0c7a0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffff800010c0f824)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffff800010c106f8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffff800010c12c9c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffff800010c2c93c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffff800010c39a38)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffff800010c460fc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffff800010c46ce8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffff800010c5dc08)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6b948)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6cfd0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffff800010c77460)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffff800010c93980)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffff800010ca8f68)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffff800010cb0de0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffff800010cb8938)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf3fc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffff800010cc3288)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv4/nexthop.c (ffff800010cc5ad0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffff800010ccd948)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffff800010cd1e0c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffff800010cd568c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd9fec)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffff800010ce278c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffff800010cf2a98)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/anycast.c (ffff800010cf7284)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffff800010d02c18)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6_fib.c (ffff800010d1acc4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1e714)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv6/mcast.c (ffff800010d3159c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffff800010d3c404)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffff800010d45394)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffff800010d4e124)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffff800010d5d080)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffff800010d81358)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/klist.c (ffff800010d89a34)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffff800010d8b174)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/arm/mm/dma-mapping.c (c031e54c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_create_mapping
```
```
In kernel/fork.c (c0351e14)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (c0363554)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (c0377918)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (c03ab980)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (c03b312c)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/irq/manage.c (c03ca84c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/futex.c (c0400c9c)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/cgroup/cgroup.c (c04154b4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (c041cc10)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (c0425b7c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (c0427c5c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_watch.c (c04335b8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (c0435bcc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/seccomp.c (c0448988)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (c0449684)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (c045ec28)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/btf.c (c04b6060)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (c04c4364)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (c04d2c5c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (c04d5d44)
Location: include/linux/refcount.h:30
Inline: True
```
```
In mm/backing-dev.c (c050419c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (c0541540)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/memcontrol.c (c0556970)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (c0574e80)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/fsopen.c (c05b080c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fsopen.c:fscontext_alloc_log
```
```
In fs/notify/group.c (c05c0568)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (c05c0b58)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (c05cac88)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (c05cdca0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (c05d1348)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_submit
```
```
In fs/io_uring.c (c05d32c0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keyring.c (c05da2f0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (c05dc474)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/posix_acl.c (c05eef10)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/proc/generic.c (c0608858)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (c061ea6c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (c06be3dc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (c06c9948)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (c06cbff8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (c06d2dac)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (c06d961c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (c06dfc80)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (c06e560c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (c06e6ef0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (c071c8d4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (c073dcc4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (c0740610)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (c07411dc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (c074abec)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (c0752678)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (c076639c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (c0767784)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (c078e258)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (c079aa94)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (c07b53e4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (c07b608c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (c07b6b00)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/cpu_rmap.c (c080b27c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/pinctrl/core.c (c082f62c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/clk/clk.c (c08ed3e4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (c091e1b0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/soc/qcom/smem_state.c (c0938488)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/soc/qcom/smem_state.c:qcom_smem_state_register
```
```
In drivers/reset/core.c (c095874c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (c095dfe4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (c096598c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (c09af41c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (c09b0e84)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/connector/cn_queue.c (c09cc708)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (c09cdd64)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (c09d4b20)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (c09f65c4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/dax/bus.c (c0a3b2cc)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (c0a3d318)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (c0a40e44)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (c0a4e988)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (c0a5ee38)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (c0a61b58)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (c0a679c4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/mtd/mtd_blkdevs.c (c0a97fe8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
```
```
In drivers/net/phy/sfp-bus.c (c0ac076c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (c0add760)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hub.c (c0af2428)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (c0af4c74)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (c0af7100)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (c0afdf1c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (c0aff0f8)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (c0ba52b4)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/md/dm.c (c0bde4a4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (c0be1484)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (c0bf521c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:_opp_get_opp_table
```
```
In drivers/opp/of.c (c0bf6770)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (c0c63fbc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (c0c814c0)
Location: include/linux/refcount.h:30
Inline: True
```
```
In sound/core/pcm_native.c (c0c95fd8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
```
```
In net/core/sock.c (c0cc8070)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (c0cd091c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (c0cdd4c4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (c0ce4644)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (c0cfb1b4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (c0d00f4c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (c0d1b894)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (c0d24ec0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (c0d264e4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (c0d284b8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (c0d2a0a8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (c0d4359c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (c0d4bd90)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (c0d55f9c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (c0d57ea4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (c0d6cfe8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a9e8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (c0d7b5c8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (c0d859d8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (c0da22fc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (c0db570c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (c0dbadf8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (c0dc3df8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (c0dcad2c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (c0dceab8)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv4/nexthop.c (c0dd14a0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (c0dd8a10)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (c0ddbb0c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (c0ddf5c4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (c0de3d18)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (c0deb898)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (c0df88c0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/anycast.c (c0dfd950)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (c0e09910)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6_fib.c (c0e20068)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (c0e24320)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv6/mcast.c (c0e34970)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (c0e3f60c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (c0e47f40)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (c0e4e38c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (c0e5e46c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (c0e7b904)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/klist.c (c0e84ad8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (c0e85ee8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/powerpc/platforms/powernv/pci.c (c0000000000d0f94)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci.c:pnv_pci_table_alloc
```
```
In arch/powerpc/platforms/pseries/iommu.c (c0000000000f0660)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/iommu.c:iommu_pseries_alloc_group
```
```
In arch/powerpc/platforms/pseries/vio.c (c000000000101868)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
```
```
In kernel/fork.c (c0000000001393c0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (c000000000151568)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (c00000000016e5a4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/fair.c (c00000000019ac48)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/autogroup.c (c0000000001b447c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (c0000000001bfd60)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/irq/manage.c (c0000000001d31c8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/futex.c (c00000000021dde4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/futex.c:put_pi_state
```
```
In kernel/cgroup/cgroup.c (c00000000023d38c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (c000000000247634)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (c0000000002556e0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (c000000000258154)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_watch.c (c000000000267b58)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (c00000000026b28c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/seccomp.c (c000000000286a68)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (c000000000287e3c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (c0000000002a6568)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/btf.c (c000000000330970)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (c0000000003465d8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (c00000000035553c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (c000000000359e40)
Location: include/linux/refcount.h:30
Inline: True
```
```
In mm/backing-dev.c (c00000000039ed64)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (c0000000004032fc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (c000000000409cac)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (c000000000450b04)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (c0000000004857b0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/fsopen.c (c0000000004db560)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fsopen.c:fscontext_alloc_log
```
```
In fs/notify/group.c (c0000000004ef93c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (c0000000004f05c8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (c0000000004fdea8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (c0000000004fe9b8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (c000000000506b90)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/io_uring.c (c00000000050ad50)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keyring.c (c00000000051a88c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (c00000000051d4dc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/posix_acl.c (c0000000005355e8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/proc/generic.c (c000000000558b90)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (c000000000579c18)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (c000000000645ccc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (c0000000006551d4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (c000000000658378)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (c00000000065ffbc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (c00000000066624c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (c00000000066fbf8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:do_semtimedop
```
```
In ipc/namespace.c (c000000000678d10)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (c00000000067b3d4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (c0000000006cbc94)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (c0000000006ff2d4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (c000000000702b60)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (c000000000703b30)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (c000000000710d3c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (c00000000071cf68)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (c00000000073c344)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (c00000000073e394)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (c000000000774050)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (c000000000784814)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (c0000000007a6b04)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (c0000000007a7780)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (c0000000007a8b50)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/cpu_rmap.c (c000000000816728)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (c0000000008272e4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/dma/dmaengine.c (c0000000008c8280)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/reset/core.c (c0000000008eb98c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (c0000000008f2a00)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (c0000000008fd3b4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (c00000000094e9dc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (c000000000951534)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
```
In drivers/connector/cn_queue.c (c000000000970b98)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (c0000000009730c4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (c00000000097c22c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (c0000000009adb18)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (c0000000009fcb64)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (c000000000a02ba0)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dax/bus.c (c000000000a1adbc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (c000000000a1e00c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_init
```
```
In drivers/dma-buf/sw_sync.c (c000000000a23c3c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (c000000000a3557c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (c000000000a4de9c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (c000000000a52dc0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (c000000000a5a28c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (c000000000a9ba28)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa8118)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (c000000000ab0dc4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab6c8c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (c000000000ad393c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (c000000000ad559c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (c000000000ada0b8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (c000000000ae3cb0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (c000000000ae545c)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (c000000000ba66d4)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/md/dm.c (c000000000bed710)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (c000000000bf1bd8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (c000000000c0c3e8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:_opp_get_opp_table
```
```
In drivers/opp/of.c (c000000000c0e4bc)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5d254)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (c000000000c731fc)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/core/sock.c (c000000000c7efb0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (c000000000c8a244)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (c000000000c9bdbc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (c000000000ca4d8c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (c000000000cc1580)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (c000000000cca060)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (c000000000ceb604)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (c000000000cf7ed4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (c000000000cfa620)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (c000000000cfccbc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (c000000000d01684)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (c000000000d23b5c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (c000000000d32890)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (c000000000d40b18)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (c000000000d441fc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (c000000000d60134)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d71020)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72088)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (c000000000d7f87c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (c000000000da3e18)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (c000000000dbe194)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (c000000000dc72e4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (c000000000dd1388)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (c000000000dda024)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (c000000000ddee24)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv4/nexthop.c (c000000000de256c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (c000000000dea350)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (c000000000df0104)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (c000000000df4d28)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dfca40)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (c000000000e05238)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (c000000000e17f54)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/anycast.c (c000000000e1dac8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (c000000000e2a658)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6_fib.c (c000000000e4903c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4cf88)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv6/mcast.c (c000000000e63bb8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (c000000000e700a8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (c000000000e7aea4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (c000000000e83c48)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (c000000000e98f00)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (c000000000ec12a4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/klist.c (c000000000ecb058)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (c000000000ecd19c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In kernel/fork.c (ffffffe0000bfdc4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffe0000ccfa4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffe0000dc86a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/autogroup.c (ffffffe0001033d8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffe0001096d2)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/irq/manage.c (ffffffe0001138b0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/futex.c (ffffffe00013c502)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffe00014beec)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffe000152aa2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffe00015afb4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffe00015cd0e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_watch.c (ffffffe0001665ee)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffe000168c96)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/seccomp.c (ffffffe00016bace)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffe00016c4d8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffe00017dabc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/btf.c (ffffffe0001bad7c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffffffe0001c74a0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffe0001d19ba)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/backing-dev.c (ffffffe0001f70be)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffe000229e80)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffe00022e1f2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (ffffffe0002430cc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (ffffffe00025e374)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/fsopen.c (ffffffe0002907b2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fsopen.c:fscontext_alloc_log
```
```
In fs/notify/group.c (ffffffe00029d922)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffe00029dda8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffe0002a672c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffe0002a8f50)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffe0002ab2bc)
Location: include/linux/refcount.h:30
Inline: True
```
```
In fs/io_uring.c (ffffffe0002ad670)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keyring.c (ffffffe0002b6a2c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b861a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/posix_acl.c (ffffffe0002c4d8a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/proc/generic.c (ffffffe0002d9be6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffe0002edd5c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffe00036ec78)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffe000378f30)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffe00037b082)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffe000380630)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffe000384b3e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffe00038a108)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffe00038ec02)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffe0003903c4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffe0003bde38)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (ffffffe0003db2a4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffe0003dd4b4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffe0003ddf84)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e6174)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffe0003eca2a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffe0003fde9c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffe0003ff2ac)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (ffffffe000423502)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffe00042daa2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffe0004437ac)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffe0004442ee)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffe000444cd4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/cpu_rmap.c (ffffffe00048ef26)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffe0004997a0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/clk/clk.c (ffffffe000510280)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffe0005175da)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/reset/core.c (ffffffe00052bca2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffe00052ff22)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffe000536b2e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffe000566932)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffe000567f2e)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/connector/cn_queue.c (ffffffe000573c6e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffffffe000575444)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffe00057af52)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffe000592042)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffe0005c02f4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffe0005c44f4)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dax/bus.c (ffffffe0005d182e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d35da)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d6402)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e29b2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffe0005f13be)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffe0005f38b2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffe0005f8754)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffe000624a5e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062cb2c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hub.c (ffffffe00063ec36)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffe000640438)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffe000643a22)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_alloc_urb
```
```
In drivers/usb/core/config.c (ffffffe000649b0e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffe00064ab0e)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffe0006c441a)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/md/dm.c (ffffffe0006eec74)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffe0006f21c0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffe000702d80)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/opp/core.c:_opp_get_opp_table
```
```
In drivers/opp/of.c (ffffffe0007040a8)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/nvmem/core.c (ffffffe000737c48)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/core/sock.c (ffffffe00073cfd2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffe000744600)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:build_skb_around
  - net/core/skbuff.c:__build_skb
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffe00074f00a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffe000754f72)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffe000766e84)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffe000769bda)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffe00078172c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (ffffffe000789b50)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffe00078b394)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffe00078cb1e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffe00078f6fc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffe0007a3e3c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffe0007aadd8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffe0007b3572)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffe0007b5256)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffe0007c63ec)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d13ae)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d1fe0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffffffe0007da5d2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2fee)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffe000803c7a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffe000808434)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffe00080f7de)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffe0008151cc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffe0008186d4)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffe00081a6cc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffffffe00081fe1c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffe000823118)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008262fe)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082a640)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffe000830e4e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffe00083e18c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/anycast.c (ffffffe000842684)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffe00084bfae)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6_fib.c (ffffffe00085ef3e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe00086141c)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv6/mcast.c (ffffffe00086fe42)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffe000878e42)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffe00088069a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffe00088730e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffe000893698)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad804)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/klist.c (ffffffe0008b3666)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffe0008b4b5a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff810524a9)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/fork.c (ffffffff81098320)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810a978e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffff810c0499)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/fair.c (ffffffff810e323a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/autogroup.c (ffffffff810f3a9f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff810fc2af)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81110219)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/futex.c (ffffffff81142883)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811598b7)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff811600d1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81169cd8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8116bb48)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_watch.c (ffffffff81176838)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff81178ce7)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/seccomp.c (ffffffff8118a522)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff8118b3dd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff8119e411)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/btf.c (ffffffff811f6fec)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffffffff8120523c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff81210cfd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81213b2e)
Location: include/linux/refcount.h:30
Inline: True
```
```
In mm/backing-dev.c (ffffffff81242165)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff81286c16)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8128b868)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (ffffffff812ba411)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (ffffffff812deb81)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/fsopen.c (ffffffff81317558)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff81325641)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff81325a02)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff81330155)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81330880)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff813369ed)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/io_uring.c (ffffffff813398e4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keyring.c (ffffffff81344de5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff81346c7f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/posix_acl.c (ffffffff813586a7)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/proc/generic.c (ffffffff8136fe55)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff81384aa8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffff81417946)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff81422868)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81424efb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff8142a74a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8142f1a5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff81435f02)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff8143c8c2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff8143dfea)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff81470b39)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (ffffffff8148f8c1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81491ffa)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff814929e7)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8149c2dd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff814a3602)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff814b6ca8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff814b7c1d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (ffffffff814dc4f5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff814e7b28)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff8150011e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff81500c2d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff815016fd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/cpu_rmap.c (ffffffff8154e343)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff815591c3)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159d641)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff815d5cd4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff81617caf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff8161ccf8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81635744)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8164746d)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8164b67b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff81652eb2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81687f8a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff8168ac1c)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/connector/cn_queue.c (ffffffff816b9b47)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffffffff816bb296)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff816c139a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff816e0152)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff81704bbf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff81708a87)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81718dc0)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8171aecb)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8171de3a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8172ab8d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8173a8bd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8173ca7e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/nvme/host/core.c (ffffffff81746e60)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_init_subsystem
```
```
In drivers/ata/libata-core.c (ffffffff81753474)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81784198)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff8178c7fd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/usb/core/hub.c (ffffffff817a442a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817a4dcf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817a872f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817aef38)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817b081f)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff81824332)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/md/dm.c (ffffffff8184e718)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81851eb4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffff81863a7b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81895b5a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff818a2af6)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff818b1fb1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff818b9f96)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff818c5f76)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff818d0395)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff818e0d16)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff818e69e4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffff818feeef)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (ffffffff81907175)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81908d55)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff8190a35f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff8190d8ce)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff819241f1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff8192e0be)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff81939270)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff8193a0c0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffff8194d61d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959e2c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195a985)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffffffff819648a3)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8197fc4f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff81992a08)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff8199981b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff819a0085)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff819a6333)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff819a9d2c)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff819ac22b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffffffff819b2bb2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff819b57cf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff819b8fb6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bd0c2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff819c45df)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff819d0f3d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/anycast.c (ffffffff819d5d2b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff819e0862)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff819f5794)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f94d0)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a09bca)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81a13058)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff81a1aeb9)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81a21f5e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81a2f62c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81a4be65)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/klist.c (ffffffff81a4f012)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81a50566)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81041e99)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/fork.c (ffffffff81086d66)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff81098148)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffff810aec9d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/fair.c (ffffffff810d234a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/autogroup.c (ffffffff810e3bcf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff810ec4bf)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81100f49)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/futex.c (ffffffff81135be3)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff8114cbc1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8115333b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8115ced8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff8115ed48)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_watch.c (ffffffff811699d8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff8116be87)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/seccomp.c (ffffffff8117d652)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff8117e4dd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff81191471)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/btf.c (ffffffff811e9d3c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffffffff811f7fcc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff81203a8d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff8120689e)
Location: include/linux/refcount.h:30
Inline: True
```
```
In mm/backing-dev.c (ffffffff81235135)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff81278a76)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff8127d698)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (ffffffff812ab5d1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (ffffffff812cecb5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/fsopen.c (ffffffff81308148)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff813161e1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff813165a2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff81320d75)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81321470)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff8132736d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/io_uring.c (ffffffff8132a614)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keyring.c (ffffffff81335ac5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff8133795f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/posix_acl.c (ffffffff81349357)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/proc/generic.c (ffffffff813608e5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff81375538)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffff814083c6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff814132e8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8141597b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff8141b1ca)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8141fc25)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff81426982)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff8142d332)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff8142ea5a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff81461559)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (ffffffff814802e1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff81482a1a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff81483407)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8148ccfd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff81494022)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff814a76c8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff814a863d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (ffffffff814ccea5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff814d8098)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff814f062e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff814f113d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff814f1c0d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/cpu_rmap.c (ffffffff8153e623)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff81549683)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158c7d1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff815bf894)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff8160c1df)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff816113e8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/reset/core.c (ffffffff816278cd)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8162bacb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff816332f2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff81665aaa)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff8166861c)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/connector/cn_queue.c (ffffffff81697787)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/base/core.c (ffffffff8169c64a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff816ba792)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff816d863f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff816dc507)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dax/bus.c (ffffffff816f12f0)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff816f432b)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff816f729a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff81703fad)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8171c55d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8171e71e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/nvme/host/core.c (ffffffff81728ae4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
  - drivers/nvme/host/core.c:nvme_init_subsystem
```
```
In drivers/ata/libata-core.c (ffffffff81733314)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81763ae8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/vxlan.c (ffffffff81770e56)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/vxlan.c:__vxlan_sock_add
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817755cd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff8177a720)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff8178180c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (ffffffff81795f9b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817968df)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff8179a13f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817a0938)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817a21e0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_register_dev
```
```
In drivers/media/cec/cec-notifier.c (ffffffff817eb9d2)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/md/dm.c (ffffffff81815d38)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff818194c4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/opp/core.c (ffffffff8182c72b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/nvmem/core.c (ffffffff8185e266)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff8186bf01)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff81873ee6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff8187feb6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81886235)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff8189ab56)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff818a0824)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffff818b8d1f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (ffffffff818c0f85)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff818c2b65)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff818c420f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff818c768e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff818ddfa1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff818e7bbe)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff818f2d70)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff818f3bc0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffff8190710d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8191391c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914475)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffffffff8191e393)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffff8193970f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff8194c4c8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff819532db)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81959b45)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff8195fdf3)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff819637ec)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81965ceb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffffffff8196f1e2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff819725bf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81975da6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81979eb2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff819813cf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff8198dcfd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/anycast.c (ffffffff81992aeb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff8199d622)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff819b2554)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b6290)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff819c698a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff819cfe18)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff819d7c79)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff819ded1e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff819ec81c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81a08a55)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/klist.c (ffffffff81a0c112)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81a0d666)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81052359)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/fork.c (ffffffff810982d0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810a8cee)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffff810bf9e9)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/fair.c (ffffffff810df5ba)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/autogroup.c (ffffffff810f0bef)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff810f946f)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/irq/manage.c (ffffffff8110e109)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/futex.c (ffffffff81140733)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff81157687)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8115dea1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81167aa8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81169918)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_watch.c (ffffffff81174608)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff81176ab7)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/seccomp.c (ffffffff811882f2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff811891ad)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff8119c1e1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/btf.c (ffffffff811f4dbc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffffffff8120300c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8120ea9d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff812118ce)
Location: include/linux/refcount.h:30
Inline: True
```
```
In mm/backing-dev.c (ffffffff8123ff05)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff81284a26)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81289678)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (ffffffff812b8221)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (ffffffff812dc991)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/fsopen.c (ffffffff81315028)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff81323111)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff813234d2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff8132dc25)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff8132e350)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff813344bd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/io_uring.c (ffffffff813373b4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keyring.c (ffffffff813428b5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134474f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/posix_acl.c (ffffffff81356177)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/proc/generic.c (ffffffff8136d925)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff81382578)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffff81413ae6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff8141ea08)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff8142109b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff814268ea)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff8142b345)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff814320a2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff81438a62)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff8143a18a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff8146cbd9)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (ffffffff8148b961)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff8148e09a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff8148ea87)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff8149837d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff8149f6a2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff814b2d38)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff814b3cad)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (ffffffff814d8585)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff814e3bb8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff814fc1ae)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff814fccbd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff814fd78d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/cpu_rmap.c (ffffffff8154a083)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff81554f03)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159dbc1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff815d80c4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff81645a8f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff8164ac98)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff816634c4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8167582d)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81679a3b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff81681272)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff816b626a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff816b8e8c)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/connector/cn_queue.c (ffffffff816e8017)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffffffff816e9766)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff816ef86a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff8170d6cc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff8174398f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff81747857)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81757b90)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81759c9b)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff8175cc0a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff8176995d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff8177b04d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8177d20e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff81783164)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817b4548)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817bcb9d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff817c54f0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cc5dc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (ffffffff817e0eca)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817e186f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817e51cf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff817eb9d8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff817ed2bf)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff81871272)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/md/dm.c (ffffffff8189dd48)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff818a14e4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff818b24a2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff818b480b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/nvmem/core.c (ffffffff818f40e6)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff81902fb1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8190af96)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff81916f76)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81921395)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81931d46)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81937a14)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffff8194ff1f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (ffffffff819581a5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff81959d85)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff8195b38f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff8195e8fe)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81975381)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff8197f24e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff8198a400)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff8198b250)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199bbe4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a1c87)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_alloc
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a38b7)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:nf_conntrack_helper_register
```
```
In net/ipv4/inetpeer.c (ffffffff819b7ded)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c45fc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5155)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffffffff819cf073)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819ea41f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff819fd2a8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81a040bb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0a925)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10bd3)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81a145cc)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a16acb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffffffff81a1d452)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81a2006f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a23a36)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a27b42)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f05f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81a3b9bd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/anycast.c (ffffffff81a407ab)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a4b2e2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff81a60214)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a63f50)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a7464a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81a7dad8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff81a85939)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81a8c9de)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81a9b1dc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7d15)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/klist.c (ffffffff81abb402)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81abc956)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
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
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81053799)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/fork.c (ffffffff8109fec7)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/user.c (ffffffff810b0dda)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/pid.c (ffffffff810c7e17)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/fair.c (ffffffff810eb162)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/autogroup.c (ffffffff810fbc7f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_init
```
```
In kernel/sched/psi.c (ffffffff811045af)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/irq/manage.c (ffffffff81119642)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_notifier
```
```
In kernel/futex.c (ffffffff8114d4e3)
Location: include/linux/refcount.h:30
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffff811645fb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffff8116b10f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81175188)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/pid_namespace.c (ffffffff81177038)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In kernel/audit_watch.c (ffffffff81181ee8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_tree.c (ffffffff81184397)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_make_tree
```
```
In kernel/seccomp.c (ffffffff81195c52)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff81196afd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/relay.c:__relay_reset
```
```
In kernel/trace/trace.c (ffffffff811a9e81)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
```
In kernel/bpf/btf.c (ffffffff812032dc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
```
In kernel/events/core.c (ffffffff81212bdc)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (ffffffff8121d9ad)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81220811)
Location: include/linux/refcount.h:30
Inline: True
```
```
In mm/backing-dev.c (ffffffff8124f665)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:wb_congested_get_create
  - mm/backing-dev.c:default_bdi_init
```
```
In mm/zswap.c (ffffffff812946c6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
```
```
In mm/hugetlb.c (ffffffff81299458)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/hugetlb.c:resv_map_alloc
```
```
In mm/memcontrol.c (ffffffff812c8b51)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
```
```
In fs/exec.c (ffffffff812ed73c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/fsopen.c (ffffffff81326b98)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
```
```
In fs/notify/group.c (ffffffff81334e51)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/mark.c (ffffffff81335362)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_init_mark
```
```
In fs/eventfd.c (ffffffff81340a05)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff81340c50)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/userfaultfd.c:__ia32_sys_userfaultfd
  - fs/userfaultfd.c:__x64_sys_userfaultfd
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (ffffffff81346931)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
```
```
In fs/io_uring.c (ffffffff8134a655)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/io_uring.c:io_get_req
```
```
In fs/crypto/keyring.c (ffffffff81355bb5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff81357a2f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
```
In fs/posix_acl.c (ffffffff81369847)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_clone
  - fs/posix_acl.c:posix_acl_alloc
```
```
In fs/proc/generic.c (ffffffff81381258)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/configfs/item.c (ffffffff81396098)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/configfs/item.c:config_group_init_type_name
  - fs/configfs/item.c:config_item_init_type_name
```
```
In fs/fuse/dev.c (ffffffff8142a966)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_alloc
```
```
In fs/fuse/file.c (ffffffff81435768)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_file_alloc
```
```
In fs/fuse/inode.c (ffffffff81437f1b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_conn_init
```
```
In fs/debugfs/file.c (ffffffff8143d7aa)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_get
```
```
In ipc/util.c (ffffffff81442295)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In ipc/sem.c (ffffffff81449172)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/sem.c:copy_semundo
  - ipc/sem.c:find_alloc_undo
```
```
In ipc/namespace.c (ffffffff8144fbd2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffff814512bb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/keys/key.c:key_alloc
  - security/keys/key.c:key_user_lookup
```
```
In security/selinux/ss/services.c (ffffffff814843f8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
```
```
In security/apparmor/apparmorfs.c (ffffffff814a3741)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
```
In security/apparmor/lib.c (ffffffff814a5faa)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_str_alloc
```
```
In security/apparmor/match.c (ffffffff814a6997)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/policy_unpack.c (ffffffff814b04cd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/label.c (ffffffff814b7cd2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_label_alloc
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In crypto/api.c (ffffffff814cb7b8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/api.c:crypto_alg_mod_lookup
```
```
In crypto/algapi.c (ffffffff814cc72d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - crypto/algapi.c:__crypto_register_alg
  - crypto/algapi.c:crypto_check_alg
```
```
In block/blk-core.c (ffffffff814f1195)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff814fd11c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bsg.c (ffffffff8151525e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
```
```
In block/bsg-lib.c (ffffffff81515d6d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_queue_rq
```
```
In block/blk-cgroup.c (ffffffff81516d4d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
```
```
In lib/cpu_rmap.c (ffffffff81563ed3)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/cpu_rmap.c:alloc_cpu_rmap
```
```
In drivers/pinctrl/core.c (ffffffff8156ed93)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:create_pinctrl
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b7ff1)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
```
```
In drivers/acpi/ec.c (ffffffff815f1f84)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/clk/clk.c (ffffffff8166001f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
```
In drivers/dma/dmaengine.c (ffffffff81665238)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_get_unmap_data
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167da84)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
```
```
In drivers/reset/core.c (ffffffff8168fe8d)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8169409b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
```
```
In drivers/tty/tty_port.c (ffffffff8169b8c2)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_init
```
```
In drivers/char/virtio_console.c (ffffffff816d085a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/char/hw_random/core.c (ffffffff816d345c)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/connector/cn_queue.c (ffffffff81702717)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffffffff81703fa6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_alloc_dev
```
```
In drivers/base/core.c (ffffffff8170a0aa)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/firmware_loader/main.c (ffffffff81728486)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/nvdimm/core.c (ffffffff8175eddf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
```
In drivers/nvdimm/dimm.c (ffffffff81762c97)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dax/bus.c (ffffffff81773030)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffff8177520b)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (ffffffff817782aa)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open
```
```
In drivers/scsi/scsi_scan.c (ffffffff817850ad)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
```
In drivers/scsi/sr.c (ffffffff81794bbd)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81797035)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffff8179d024)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_init
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/net/phy/sfp-bus.c (ffffffff817ce518)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff817d77a8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
```
In drivers/vfio/vfio.c (ffffffff817df790)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_fops_open
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e687c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (ffffffff817fb1ba)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff817fbc5f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (ffffffff817ff42f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_init_urb
```
```
In drivers/usb/core/config.c (ffffffff81805c18)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
```
In drivers/usb/core/file.c (ffffffff818074ff)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (ffffffff8188b232)
Location: include/linux/refcount.h:30
Inline: True
```
```
In drivers/md/dm.c (ffffffff818ba0f8)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff818bd724)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/edac/ghes_edac.c (ffffffff818ce752)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_register
```
```
In drivers/opp/core.c (ffffffff818d0abb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_add
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819062ba)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/nvmem/core.c (ffffffff81915186)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/core/sock.c (ffffffff81923f21)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sock_init_data
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_clone_lock
  - net/core/sock.c:sk_alloc
```
```
In net/core/skbuff.c (ffffffff8192c096)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:sock_zerocopy_alloc
  - net/core/skbuff.c:__skb_clone
  - net/core/skbuff.c:__build_skb_around
  - net/core/skbuff.c:__alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/net_namespace.c (ffffffff81938186)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:setup_net
  - net/core/net_namespace.c:setup_net
```
```
In net/core/dev.c (ffffffff81943205)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffff81953416)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff819591e4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_parms_alloc
  - net/core/neighbour.c:___neigh_create
```
```
In net/core/filter.c (ffffffff819718ef)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
```
```
In net/core/page_pool.c (ffffffff8197a2b5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/skmsg.c (ffffffff8197bfa5)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/netpoll.c (ffffffff8197d5af)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/core/fib_rules.c (ffffffff81980b6e)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_default_rule_add
```
```
In net/core/devlink.c (ffffffff81997871)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_health_reporter_create
```
```
In net/sched/sch_generic.c (ffffffff819a17ae)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_alloc
```
```
In net/sched/cls_api.c (ffffffff819ab76f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
```
```
In net/sched/act_api.c (ffffffff819adac0)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_idr_create
```
```
In net/ipv4/inetpeer.c (ffffffff819c166c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce19c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_alloc
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cec25)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add
```
```
In net/ipv4/tcp_input.c (ffffffff819d8c03)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/tcp_fastopen.c (ffffffff819f425d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/devinet.c (ffffffff81a07638)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/igmp.c (ffffffff81a0e62b)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/igmp.c:____ip_mc_inc_group
```
```
In net/ipv4/fib_semantics.c (ffffffff81a15105)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b48f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frags_init
```
```
In net/ipv4/metrics.c (ffffffff81a1efdc)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81a214fb)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
```
In net/ipv4/ipmr.c (ffffffff81a285bf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv4/syncookies.c (ffffffff81a2b56f)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/cipso_ipv4.c (ffffffff81a2ee1a)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a33172)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3a2bf)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_alloc
```
```
In net/unix/af_unix.c (ffffffff81a46d0d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
```
```
In net/ipv6/anycast.c (ffffffff81a4c3ab)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/addrconf.c (ffffffff81a5723d)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_addr
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6c6d4)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:fib6_info_alloc
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a70450)
Location: include/linux/refcount.h:30
Inline: True
```
```
In net/ipv6/mcast.c (ffffffff81a80cef)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
```
```
In net/ipv6/exthdrs.c (ffffffff81a8a328)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_renew_options
  - net/ipv6/exthdrs.c:ipv6_dup_options
```
```
In net/ipv6/ip6mr.c (ffffffff81a923a6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/calipso.c (ffffffff81a9863c)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_doi_add
```
```
In net/packet/af_packet.c (ffffffff81aa7f44)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
```
In net/xdp/xdp_umem.c (ffffffff81ac4135)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In lib/klist.c (ffffffff81ac7872)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/klist.c:klist_node_init
```
```
In lib/kobject.c (ffffffff81ac8dd6)
Location: include/linux/refcount.h:30
Inline: True
Inline callers:
  - lib/kobject.c:kset_register
  - lib/kobject.c:kobject_init
```
</details>
</li>
</ul>

## Differences
