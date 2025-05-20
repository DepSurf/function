# Function: <code>ns_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108a2f0)
Location: kernel/capability.c:375
Inline: True
Direct callers:
  - kernel/capability.c:capable
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:set_one_prio
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_sethostname
  - kernel/sys.c:SyS_setdomainname
  - kernel/sys.c:SyS_prlimit64
  - kernel/nsproxy.c:copy_namespaces
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/reboot.c:SYSC_reboot
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup.c:cgroupns_install
  - kernel/cgroup.c:cgroupns_install
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:copy_cgroup_ns
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:map_write
  - kernel/user_namespace.c:userns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - fs/open.c:SyS_chroot
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/inode.c:should_remove_suid
  - fs/attr.c:inode_change_ok
  - fs/attr.c:inode_change_ok
  - fs/namespace.c:do_umount
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/proc/root.c:proc_mount
  - fs/proc/base.c:proc_setgroups_open
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/resize.c:ext4_resize_begin
  - ipc/util.c:ipcperms
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/shm.c:SyS_shmctl
  - ipc/mqueue.c:mqueue_mount
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_ptrace_access_check
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_inode_removexattr
  - security/apparmor/policy.c:policy_admin_capable
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
  - security/integrity/ima/ima_appraise.c:ima_inode_removexattr
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sk_ns_capable
  - net/core/sock.c:sock_cmsg_send
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:inet6_create
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff8108a2f0-ffffffff8108a33e: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108d306)
Location: kernel/capability.c:393
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_setdomainname
  - kernel/sys.c:SyS_sethostname
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:SYSC_reboot
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup.c:cgroupns_install
  - kernel/cgroup.c:cgroupns_install
  - kernel/cgroup.c:copy_cgroup_ns
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:SyS_chroot
  - fs/super.c:mount_ns
  - fs/super.c:sget
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:inode_change_ok
  - fs/attr.c:inode_change_ok
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:do_umount
  - fs/proc/base.c:proc_setgroups_open
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/resize.c:ext4_resize_begin
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
  - ipc/shm.c:SyS_shmctl
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:inet6_create
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff8108d2a0-ffffffff8108d2b5: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81092736)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_setdomainname
  - kernel/sys.c:SyS_sethostname
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:SYSC_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup.c:cgroupns_install
  - kernel/cgroup.c:cgroupns_install
  - kernel/cgroup.c:copy_cgroup_ns
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:SyS_chroot
  - fs/super.c:mount_ns
  - fs/super.c:sget
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:do_umount
  - fs/proc/base.c:proc_setgroups_open
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/resize.c:ext4_resize_begin
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
  - ipc/shm.c:SyS_shmctl
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/af_inet6.c:inet6_create
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff81092250-ffffffff81092265: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8108f876)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_setdomainname
  - kernel/sys.c:SyS_sethostname
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:SYSC_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:SyS_chroot
  - fs/super.c:mount_ns
  - fs/super.c:sget
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:do_umount
  - fs/proc/base.c:proc_setgroups_open
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/resize.c:ext4_resize_begin
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
  - ipc/shm.c:SyS_shmctl
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff8108f400-ffffffff8108f415: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81096736)
Location: kernel/capability.c:395
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:SyS_prlimit64
  - kernel/sys.c:SyS_setdomainname
  - kernel/sys.c:SyS_sethostname
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:SYSC_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:SyS_chroot
  - fs/super.c:mount_ns
  - fs/super.c:sget
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:do_umount
  - fs/proc/base.c:proc_setgroups_open
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/resize.c:ext4_resize_begin
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
```
**Symbols:**

```
ffffffff810962c0-ffffffff810962d5: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81099c6b)
Location: kernel/capability.c:395
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:check_prlimit_permission
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:ksys_chroot
  - fs/super.c:mount_ns
  - fs/super.c:sget
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/proc/base.c:proc_setgroups_open
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/resize.c:ext4_resize_begin
  - ipc/util.c:ipcctl_pre_down_nolock
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/ip_options.c:ip_options_compile
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff810997b0-ffffffff810997c5: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a1ff8)
Location: kernel/capability.c:396
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:check_prlimit_permission
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/cgroup.c:cgroup_mount
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:ksys_chroot
  - fs/super.c:mount_ns
  - fs/super.c:sget
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/resize.c:ext4_resize_begin
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff810a1b20-ffffffff810a1b32: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a6a29)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:ksys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/resize.c:ext4_resize_begin
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff810a6550-ffffffff810a6562: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810ad009)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:ksys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff810acb30-ffffffff810acb42: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (ffffffff810b4878)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:check_prlimit_permission
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:set_one_prio
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:__do_sys_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:ksys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_task_setioprio
  - security/commoncap.c:cap_task_setscheduler
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_open_file
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff810b4b3b-ffffffff810b4b49: ns_capable.cold (STB_LOCAL)
ffffffff810b4980-ffffffff810b49ce: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (ffffffff810afa78)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:check_prlimit_permission
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:set_one_prio
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/sched/core.c:sched_setaffinity
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:path_umount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/init.c:init_chroot
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_open_file
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_renew
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff81bdba10-ffffffff81bdba1e: ns_capable.cold (STB_LOCAL)
ffffffff810afb20-ffffffff810afb6e: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (ffffffff810b124a)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:set_one_prio
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/sched/core.c:sched_setaffinity
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/inode.c:inode_owner_or_capable
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:path_umount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/init.c:init_chroot
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:ifalias_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
  - net/netlink/genetlink.c:genl_bind
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff81bcdace-ffffffff81bcdadc: ns_capable.cold (STB_LOCAL)
ffffffff810b10d0-ffffffff810b111e: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (ffffffff810c330a)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:set_one_prio
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/sched/core.c:sched_setaffinity
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/inode.c:inode_owner_or_capable
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:path_umount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/fsopen.c:__do_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/init.c:init_chroot
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:ifalias_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
  - net/netlink/genetlink.c:genl_bind
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff81ca45b5-ffffffff81ca45c3: ns_capable.cold (STB_LOCAL)
ffffffff810c3190-ffffffff810c31de: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/capability.c (ffffffff810da84a)
Location: kernel/capability.c:395
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:set_one_prio
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/sched/core.c:sched_setaffinity
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/inode.c:inode_owner_or_capable
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:path_umount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/init.c:init_chroot
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_map_files_get_link
  - fs/proc/base.c:proc_map_files_get_link
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/ipc_sysctl.c:ipc_permissions
  - ipc/ipc_sysctl.c:ipc_permissions
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/rtnetlink.c:rtnetlink_bind
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
  - net/netlink/genetlink.c:genl_bind
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff81e53e1c-ffffffff81e53e2a: ns_capable.cold (STB_LOCAL)
ffffffff810da570-ffffffff810da5c5: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810fa91a)
Location: kernel/capability.c:395
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:set_one_prio
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/sched/core.c:sched_setaffinity
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/inode.c:inode_owner_or_capable
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__do_sys_mount_setattr
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:path_umount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/init.c:init_chroot
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_map_files_get_link
  - fs/proc/base.c:proc_map_files_get_link
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/ipc_sysctl.c:ipc_permissions
  - ipc/ipc_sysctl.c:ipc_permissions
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/rtnetlink.c:rtnetlink_bind
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
  - net/netlink/genetlink.c:genl_bind
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff810fa5c0-ffffffff810fa61f: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8110695a)
Location: kernel/capability.c:381
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:set_one_prio
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/sched/core.c:sched_setaffinity
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_mfd_noexec_dointvec_minmax
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/inode.c:inode_owner_or_capable
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:path_umount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/init.c:init_chroot
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_map_files_get_link
  - fs/proc/base.c:proc_map_files_get_link
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/ipc_sysctl.c:ipc_permissions
  - ipc/ipc_sysctl.c:ipc_permissions
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/rtnetlink.c:rtnetlink_bind
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
  - net/netlink/genetlink.c:genl_bind
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff81106760-ffffffff811067bf: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff811102aa)
Location: kernel/capability.c:381
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/ptrace.c:__ptrace_may_access
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__do_sys_prlimit64
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:set_one_prio
  - kernel/pid.c:alloc_pid
  - kernel/pid.c:alloc_pid
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/sched/core.c:sched_setaffinity
  - kernel/time/namespace.c:timens_install
  - kernel/time/namespace.c:timens_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:new_idmap_permitted
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - kernel/pid_namespace.c:pid_mfd_noexec_dointvec_minmax
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/inode.c:inode_owner_or_capable
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:path_umount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
  - fs/init.c:init_chroot
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:proc_map_files_get_link
  - fs/proc/base.c:proc_map_files_get_link
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/ipc_sysctl.c:ipc_permissions
  - ipc/ipc_sysctl.c:ipc_permissions
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/yama/yama_lsm.c:yama_ptrace_access_check
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/connector/connector.c:cn_bind
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:__sock_cmsg_send
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_bindtoindex_locked
  - net/core/sock.c:sk_net_capable
  - net/core/sock.c:sk_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/rtnetlink.c:rtnetlink_bind
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:threaded_store
  - net/core/net-sysfs.c:proto_down_store
  - net/core/net-sysfs.c:group_store
  - net/core/net-sysfs.c:ifalias_store
  - net/core/net-sysfs.c:napi_defer_hard_irqs_store
  - net/core/net-sysfs.c:gro_flush_timeout_store
  - net/core/net-sysfs.c:tx_queue_len_store
  - net/core/net-sysfs.c:flags_store
  - net/core/net-sysfs.c:mtu_store
  - net/core/net-sysfs.c:carrier_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_net_capable
  - net/netlink/af_netlink.c:netlink_capable
  - net/netlink/genetlink.c:genl_bind
  - net/netlink/genetlink.c:genl_bind
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
**Symbols:**

```
ffffffff811100b0-ffffffff8111010f: ns_capable (STB_GLOBAL)
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
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffff800010106850)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__arm64_sys_prlimit64
  - kernel/sys.c:__arm64_sys_setdomainname
  - kernel/sys.c:__arm64_sys_sethostname
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:ksys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_move_mount
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__arm64_sys_fsconfig
  - fs/fsopen.c:__arm64_sys_fspick
  - fs/fsopen.c:__arm64_sys_fsopen
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffff800010105ab8-ffff800010105af0: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c0361550)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_setdomainname
  - kernel/sys.c:__se_sys_sethostname
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:ksys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/inode.c:inode_owner_or_capable
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fsopen
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:ksys_shmctl
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
c0360ef0-c0360f10: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c00000000014dc38)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_setdomainname
  - kernel/sys.c:__se_sys_sethostname
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:ksys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fsopen
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
c00000000014d230-c00000000014d248: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffe0000cb5b0)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__se_sys_prlimit64
  - kernel/sys.c:__se_sys_setdomainname
  - kernel/sys.c:__se_sys_sethostname
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:ksys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__se_sys_fsconfig
  - fs/fsopen.c:__se_sys_fspick
  - fs/fsopen.c:__se_sys_fsopen
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/core/net-sysfs.c:ifalias_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffe0000cb098-ffffffe0000cb0cc: ns_capable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a7379)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:ksys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff810a6ea0-ffffffff810a6eb2: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81095d59)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:ksys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ip_tunnel.c:ip_tunnel_ioctl
  - net/ipv4/ip_tunnel.c:ip_tunnel_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff81095880-ffffffff81095892: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810a68d9)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:ksys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff810a6400-ffffffff810a6412: ns_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool ns_capable(struct user_namespace *ns, int cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810aea09)
Location: kernel/capability.c:394
Inline: True
Inline callers:
  - kernel/capability.c:capable_wrt_inode_uidgid
  - kernel/capability.c:capable
Direct callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:__ia32_sys_prlimit64
  - kernel/sys.c:__x64_sys_prlimit64
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:set_one_prio
  - kernel/nsproxy.c:unshare_nsproxy_namespaces
  - kernel/nsproxy.c:copy_namespaces
  - kernel/reboot.c:__do_sys_reboot
  - kernel/ucount.c:set_permissions
  - kernel/groups.c:may_setgroups
  - kernel/sched/core.c:sched_setaffinity
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_install
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:map_write
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pid_ns_ctl_handler
  - fs/open.c:ksys_chroot
  - fs/super.c:mount_capable
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
  - fs/fsopen.c:__ia32_sys_fsopen
  - fs/fsopen.c:__x64_sys_fsopen
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - ipc/util.c:ipcctl_obtain_check
  - ipc/util.c:ipcperms
  - ipc/shm.c:shmctl_do_lock
  - ipc/namespace.c:ipcns_install
  - ipc/namespace.c:ipcns_install
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_prctl
  - security/commoncap.c:cap_safe_nice
  - security/commoncap.c:cap_inode_removexattr
  - security/commoncap.c:cap_inode_setxattr
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_ptrace_access_check
  - security/apparmor/policy.c:policy_admin_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_open
  - net/socket.c:sock_ioctl
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setbindtodevice_locked
  - net/core/sock.c:sk_ns_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_install
  - net/core/ethtool.c:dev_ethtool
  - net/core/sock_diag.c:sock_diag_destroy
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
  - net/core/net-sysfs.c:net_current_may_mount
  - net/core/net-sysfs.c:xps_rxqs_store
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_connect
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:__netlink_ns_capable
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/ip_options.c:__ip_options_compile
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/unix/af_unix.c:unix_ioctl
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/addrconf.c:addrconf_del_ifaddr
  - net/ipv6/addrconf.c:addrconf_add_ifaddr
  - net/ipv6/route.c:ipv6_route_ioctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/datagram.c:ip6_datagram_send_ctl
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/packet/af_packet.c:packet_create
  - net/xdp/xsk.c:xsk_create
```
**Symbols:**

```
ffffffff810ae4b0-ffffffff810ae4c2: ns_capable (STB_GLOBAL)
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
