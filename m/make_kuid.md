# Function: <code>make_kuid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8111de30)
Location: kernel/user_namespace.c:245
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:__send_signal
  - kernel/sys.c:SyS_setpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setfsuid
  - kernel/auditfilter.c:audit_rule_change
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
  - fs/open.c:SyS_access
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:SyS_quotactl
  - fs/proc/base.c:proc_loginuid_write
  - fs/devpts/inode.c:parse_mount_options
  - fs/devpts/inode.c:devpts_mount
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/acl.c:ext4_get_acl
  - fs/fat/inode.c:parse_options
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_secureexec
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/apparmor/policy.c:aa_may_open_profiles
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_get
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff8111de30-ffffffff8111dea4: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81126bc7)
Location: kernel/user_namespace.c:245
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:__send_signal
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/auditfilter.c:audit_rule_change
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
  - fs/open.c:SyS_access
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:SyS_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:proc_loginuid_write
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_secureexec
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/apparmor/policy.c:policy_view_capable
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
```
**Symbols:**

```
ffffffff81125d00-ffffffff81125d74: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811306b4)
Location: kernel/user_namespace.c:291
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:__send_signal
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/auditfilter.c:audit_rule_change
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
  - fs/open.c:SyS_access
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:SyS_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_secureexec
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/apparmor/policy.c:policy_view_capable
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/fib_rules.c:nla_get_kuid_range
  - net/core/fib_rules.c:nla_get_kuid_range
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff8112f750-ffffffff8112f7c4: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81131d0d)
Location: kernel/user_namespace.c:292
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:__send_signal
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/auditfilter.c:audit_rule_change
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
  - fs/open.c:SyS_access
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:SyS_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_secureexec
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/fib_rules.c:nla_get_kuid_range
  - net/core/fib_rules.c:nla_get_kuid_range
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff81130d60-ffffffff81130dd4: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8113eb63)
Location: kernel/user_namespace.c:398
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:__send_signal
  - kernel/sys.c:SyS_setfsuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setresuid
  - kernel/sys.c:SyS_setuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_setreuid
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/auditfilter.c:audit_rule_change
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
  - fs/open.c:SyS_access
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:SyS_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/fib_rules.c:nla_get_kuid_range
  - net/core/fib_rules.c:nla_get_kuid_range
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:fib_validate_source
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff8113e120-ffffffff8113e135: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8114d5dd)
Location: kernel/user_namespace.c:398
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/auditfilter.c:audit_rule_change
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8114cac0-ffffffff8114cad5: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8115a293)
Location: kernel/user_namespace.c:398
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:__send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/auditfilter.c:audit_rule_change
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff811596e0-ffffffff811596f5: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116699b)
Location: kernel/user_namespace.c:392
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81165e50-ffffffff81165e65: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8117285b)
Location: kernel/user_namespace.c:392
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81171d10-ffffffff81171d25: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81184321)
Location: kernel/user_namespace.c:392
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:access_override_creds
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_fillattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:parse_policy_line
  - security/safesetid/securityfs.c:parse_policy_line
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - lib/kobject_uevent.c:uevent_net_broadcast_tagged
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff81183de0-ffffffff81183df5: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81181081)
Location: kernel/user_namespace.c:392
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:access_override_creds
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_fillattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:parse_policy_line
  - security/safesetid/securityfs.c:parse_policy_line
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - lib/kobject_uevent.c:uevent_net_broadcast_tagged
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff81180b40-ffffffff81180b55: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81181d76)
Location: kernel/user_namespace.c:393
Inline: True
Inline callers:
  - kernel/user_namespace.c:new_idmap_permitted
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/signal.c:send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/stat.c:generic_fillattr
  - fs/exec.c:begin_new_exec
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:atime_needs_update
  - fs/inode.c:inode_init_always
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/coredump.c:do_coredump
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/file.c:__file_path_perm
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff81181ba0-ffffffff81181bb5: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811a9d30)
Location: kernel/user_namespace.c:409
Inline: True
Inline callers:
  - kernel/user_namespace.c:new_idmap_permitted
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/signal.c:send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/stat.c:generic_fillattr
  - fs/exec.c:begin_new_exec
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:atime_needs_update
  - fs/inode.c:inode_init_always
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/coredump.c:do_coredump
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/file.c:__file_path_perm
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff811a9b40-ffffffff811a9b55: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811db222)
Location: kernel/user_namespace.c:414
Inline: True
Inline callers:
  - kernel/user_namespace.c:new_idmap_permitted
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/signal.c:send_signal_locked
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/stat.c:generic_fillattr
  - fs/exec.c:bprm_fill_uid
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/inode.c:inode_init_always
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/coredump.c:do_coredump
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_fix_setuid
  - security/commoncap.c:cap_task_fix_setuid
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/policy.c:aa_policy_view_capable
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/file.c:__file_path_perm
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_do_redirect
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff811dafd0-ffffffff811dafef: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81220ab2)
Location: kernel/user_namespace.c:414
Inline: True
Inline callers:
  - kernel/user_namespace.c:new_idmap_permitted
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/signal.c:send_signal_locked
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/stat.c:generic_fillattr
  - fs/exec.c:bprm_fill_uid
  - fs/namei.c:vfs_link
  - fs/namei.c:do_open
  - fs/namei.c:do_open
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:__check_sticky
  - fs/namei.c:__check_sticky
  - fs/namei.c:pick_link
  - fs/namei.c:may_linkat
  - fs/inode.c:inode_owner_or_capable
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/inode.c:inode_init_always
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:may_write_xattr
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_permission
  - fs/posix_acl.c:posix_acl_permission
  - fs/coredump.c:do_coredump
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/file.c:fat_setattr
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_fix_setuid
  - security/commoncap.c:cap_task_fix_setuid
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/policy.c:aa_policy_view_capable
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
  - security/apparmor/file.c:__file_path_perm
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81220830-ffffffff8122084f: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81236ecc)
Location: kernel/user_namespace.c:414
Inline: True
Inline callers:
  - kernel/user_namespace.c:new_idmap_permitted
Direct callers:
  - kernel/signal.c:send_signal_locked
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/inode.c:inode_init_always
  - fs/mnt_idmapping.c:from_vfsuid
  - fs/mnt_idmapping.c:make_vfsuid
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_fix_setuid
  - security/commoncap.c:cap_task_fix_setuid
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:aa_policy_view_capable
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81236c00-ffffffff81236c1f: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff812506bc)
Location: kernel/user_namespace.c:417
Inline: True
Inline callers:
  - kernel/user_namespace.c:new_idmap_permitted
Direct callers:
  - kernel/signal.c:send_signal_locked
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - mm/shmem_quota.c:shmem_get_next_id
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/inode.c:inode_init_always
  - fs/mnt_idmapping.c:from_vfsuid
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:ext4_parse_param
  - fs/ext4/acl.c:ext4_acl_from_disk
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_fillattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - fs/efivarfs/super.c:efivarfs_parse_param
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_task_fix_setuid
  - security/commoncap.c:cap_task_fix_setuid
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:cap_bprm_creds_from_file
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:aa_policy_view_capable
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/icmp.c:icmp_reply
  - net/ipv4/af_inet.c:inet_sk_rebuild_header
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81250430-ffffffff8125044f: make_kuid (STB_GLOBAL)
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
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffff8000101e6418)
Location: kernel/user_namespace.c:392
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__arm64_sys_ioprio_get
  - block/ioprio.c:__arm64_sys_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffff8000101e59a8-ffff8000101e59e0: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c0426eb8)
Location: kernel/user_namespace.c:392
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/fib_rules.c:fib_nl2rule
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c0426388-c04263a8: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c000000000256eb4)
Location: kernel/user_namespace.c:392
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c000000000256040-c000000000256074: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffe00015c06e)
Location: kernel/user_namespace.c:392
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_set
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffe00015b5ca-ffffffe00015b5fe: make_kuid (STB_GLOBAL)
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
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116ae7b)
Location: kernel/user_namespace.c:392
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8116a330-ffffffff8116a345: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8115e07b)
Location: kernel/user_namespace.c:392
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8115d530-ffffffff8115d545: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81168c4b)
Location: kernel/user_namespace.c:392
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/netfilter/nfnetlink_log.c:nfnl_log_net_init
  - net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_pernet_init
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81168100-ffffffff81168115: make_kuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
kuid_t make_kuid(struct user_namespace *ns, uid_t uid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8117633b)
Location: kernel/user_namespace.c:392
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/signal.c:send_signal
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:do_faccessat
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
  - fs/proc/base.c:proc_loginuid_write
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:cap_bprm_set_creds
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/safesetid/securityfs.c:safesetid_file_write
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_set
  - block/ioprio.c:__x64_sys_ioprio_set
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/sock.c:sock_init_data
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv4_fib_lookup
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/ip_output.c:__ip_queue_xmit
  - net/ipv4/inet_connection_sock.c:inet_csk_rebuild_route
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/datagram.c:ip4_datagram_release_cb
  - net/ipv4/igmp.c:igmp_send_report
  - net/ipv4/igmp.c:igmpv3_newpack
  - net/ipv4/fib_frontend.c:__fib_validate_source
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/icmp.c:icmpv6_err
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/netfilter.c:ip6_route_me_harder
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff811757a0-ffffffff811757b5: make_kuid (STB_GLOBAL)
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
