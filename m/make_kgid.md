# Function: <code>make_kgid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8111dfb0)
Location: kernel/user_namespace.c:313
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setfsgid
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
  - kernel/auditfilter.c:audit_rule_change
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
  - fs/inode.c:inode_init_always
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_getquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:SyS_quotactl
  - fs/proc/root.c:proc_parse_options
  - fs/devpts/inode.c:parse_mount_options
  - fs/devpts/inode.c:devpts_mount
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/acl.c:ext4_get_acl
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/inode.c:parse_options
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/inode.c:fuse_fill_super
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:aa_may_open_profiles
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
**Symbols:**

```
ffffffff8111dfb0-ffffffff8111e025: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811269a7)
Location: kernel/user_namespace.c:313
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:SyS_setregid
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
  - kernel/auditfilter.c:audit_rule_change
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
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
  - fs/proc/root.c:proc_parse_options
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
**Symbols:**

```
ffffffff81125e80-ffffffff81125ef5: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81130494)
Location: kernel/user_namespace.c:359
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:SyS_setregid
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
  - kernel/auditfilter.c:audit_rule_change
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
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
  - fs/proc/root.c:proc_parse_options
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff8112f8d0-ffffffff8112f945: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81131a66)
Location: kernel/user_namespace.c:360
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:SyS_setregid
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
  - kernel/auditfilter.c:audit_rule_change
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
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
  - fs/proc/root.c:proc_parse_options
  - fs/proc/base.c:task_dump_owner
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff81130ee0-ffffffff81130f55: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8113ea59)
Location: kernel/user_namespace.c:466
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:SyS_setfsgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setresgid
  - kernel/sys.c:SyS_setgid
  - kernel/sys.c:SyS_setregid
  - kernel/sys.c:SyS_setregid
  - kernel/groups.c:SyS_setgroups
  - kernel/uid16.c:SyS_setgroups16
  - kernel/auditfilter.c:audit_rule_change
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
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
  - fs/proc/root.c:proc_parse_options
  - fs/proc/base.c:task_dump_owner
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff8113e140-ffffffff8113e159: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8114d4f5)
Location: kernel/user_namespace.c:466
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:groups_from_user
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_rule_change
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
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
  - fs/proc/root.c:proc_parse_options
  - fs/proc/base.c:task_dump_owner
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8114cae0-ffffffff8114caf9: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8115a0b5)
Location: kernel/user_namespace.c:466
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_rule_change
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
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
  - fs/proc/root.c:proc_parse_options
  - fs/proc/base.c:task_dump_owner
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81159700-ffffffff81159719: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811667b4)
Location: kernel/user_namespace.c:460
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_options
  - fs/open.c:chown_common
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
  - fs/proc/root.c:proc_reconfigure
  - fs/proc/root.c:proc_fill_super
  - fs/proc/base.c:task_dump_owner
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
  - fs/ext4/balloc.c:ext4_has_free_clusters
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:handle_mount_opt
  - fs/ext4/acl.c:ext4_get_acl
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81165e70-ffffffff81165e89: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81172674)
Location: kernel/user_namespace.c:460
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
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
  - fs/proc/root.c:proc_reconfigure
  - fs/proc/root.c:proc_fill_super
  - fs/proc/base.c:task_dump_owner
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81171d30-ffffffff81171d49: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81184435)
Location: kernel/user_namespace.c:460
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_fillattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - lib/kobject_uevent.c:uevent_net_broadcast_tagged
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff81183e00-ffffffff81183e19: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81181195)
Location: kernel/user_namespace.c:460
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_fillattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:parse_policy_line
  - security/safesetid/securityfs.c:parse_policy_line
  - lib/kobject_uevent.c:uevent_net_broadcast_tagged
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff81180b60-ffffffff81180b79: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81181cc9)
Location: kernel/user_namespace.c:461
Inline: True
Inline callers:
  - kernel/user_namespace.c:new_idmap_permitted
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/stat.c:generic_fillattr
  - fs/exec.c:begin_new_exec
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/inode.c:inode_init_always
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/acl.c:fuse_set_acl
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff81181bc0-ffffffff81181bd9: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811a9c75)
Location: kernel/user_namespace.c:477
Inline: True
Inline callers:
  - kernel/user_namespace.c:new_idmap_permitted
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/stat.c:generic_fillattr
  - fs/exec.c:begin_new_exec
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/inode.c:inode_init_always
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/file.c:fat_setattr
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/fuse/acl.c:fuse_set_acl
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff811a9b60-ffffffff811a9b79: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811db13c)
Location: kernel/user_namespace.c:482
Inline: True
Inline callers:
  - kernel/user_namespace.c:new_idmap_permitted
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/stat.c:generic_fillattr
  - fs/exec.c:bprm_fill_uid
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
  - fs/inode.c:inode_init_owner
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/inode.c:inode_init_always
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/xattr.c:xattr_permission
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_fix_xattr_userns
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
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
  - security/apparmor/policy.c:aa_policy_view_capable
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
```
**Symbols:**

```
ffffffff811daff0-ffffffff811db013: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff812209cc)
Location: kernel/user_namespace.c:482
Inline: True
Inline callers:
  - kernel/user_namespace.c:new_idmap_permitted
Direct callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/open.c:chown_common
  - fs/stat.c:generic_fillattr
  - fs/exec.c:bprm_fill_uid
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:may_linkat
  - fs/inode.c:mode_strip_sgid
  - fs/inode.c:inode_init_owner
  - fs/inode.c:atime_needs_update
  - fs/inode.c:inode_init_always
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_prepare
  - fs/attr.c:setattr_should_drop_suidgid
  - fs/xattr.c:may_write_xattr
  - fs/posix_acl.c:do_get_acl
  - fs/posix_acl.c:vfs_set_acl
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:posix_acl_update_mode
  - fs/posix_acl.c:posix_acl_permission
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
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/devpts/inode.c:parse_mount_options
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
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
  - security/apparmor/policy.c:aa_policy_view_capable
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_match_rules
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81220860-ffffffff81220883: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81236dc2)
Location: kernel/user_namespace.c:482
Inline: True
Inline callers:
  - kernel/user_namespace.c:new_idmap_permitted
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
  - fs/inode.c:inode_init_always
  - fs/mnt_idmapping.c:from_vfsgid
  - fs/mnt_idmapping.c:make_vfsgid
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:aa_policy_view_capable
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81236c30-ffffffff81236c53: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff812505b2)
Location: kernel/user_namespace.c:485
Inline: True
Inline callers:
  - kernel/user_namespace.c:new_idmap_permitted
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__do_sys_setgroups
  - kernel/uid16.c:__do_sys_setgroups16
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/bpf/inode.c:bpf_parse_param
  - mm/shmem.c:shmem_parse_one
  - mm/shmem_quota.c:shmem_get_next_id
  - fs/open.c:chown_common
  - fs/inode.c:inode_init_always
  - fs/mnt_idmapping.c:from_vfsgid
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/quota/quota.c:do_quotactl
  - fs/quota/quota.c:quota_getnextxquota
  - fs/quota/quota.c:quota_getxquota
  - fs/quota/quota.c:quota_setxquota
  - fs/quota/quota.c:quota_setquota
  - fs/quota/quota.c:quota_getnextquota
  - fs/quota/quota.c:quota_getquota
  - fs/proc/base.c:task_dump_owner
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
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
  - security/apparmor/policy.c:aa_policy_view_capable
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - io_uring/io_uring.c:__ia32_sys_io_uring_setup
  - io_uring/io_uring.c:__x64_sys_io_uring_setup
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81250460-ffffffff81250483: make_kgid (STB_GLOBAL)
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
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffff8000101e62dc)
Location: kernel/user_namespace.c:460
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:groups_from_user
  - kernel/uid16.c:__arm64_sys_setgroups16
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
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
  - fs/proc/root.c:proc_reconfigure
  - fs/proc/root.c:proc_fill_super
  - fs/proc/base.c:task_dump_owner
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffff8000101e59e0-ffff8000101e5a18: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c0426d74)
Location: kernel/user_namespace.c:460
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__se_sys_setgroups
  - kernel/uid16.c:__se_sys_setgroups16
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
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
  - security/apparmor/policy.c:policy_view_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c04263a8-c04263cc: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c000000000256db4)
Location: kernel/user_namespace.c:460
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__se_sys_setgroups
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c000000000256080-c0000000002560b8: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffe00015bf56)
Location: kernel/user_namespace.c:460
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__se_sys_setgroups
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffe00015b5fe-ffffffe00015b634: make_kgid (STB_GLOBAL)
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
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8116ac94)
Location: kernel/user_namespace.c:460
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
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
  - fs/proc/root.c:proc_reconfigure
  - fs/proc/root.c:proc_fill_super
  - fs/proc/base.c:task_dump_owner
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8116a350-ffffffff8116a369: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8115de94)
Location: kernel/user_namespace.c:460
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
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
  - fs/proc/root.c:proc_reconfigure
  - fs/proc/root.c:proc_fill_super
  - fs/proc/base.c:task_dump_owner
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff8115d550-ffffffff8115d569: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81168a64)
Location: kernel/user_namespace.c:460
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
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
  - fs/proc/root.c:proc_reconfigure
  - fs/proc/root.c:proc_fill_super
  - fs/proc/base.c:task_dump_owner
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/netfilter/nfnetlink_log.c:nfnl_log_net_init
  - net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_pernet_init
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81168120-ffffffff81168139: make_kgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
kgid_t make_kgid(struct user_namespace *ns, gid_t gid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81176154)
Location: kernel/user_namespace.c:460
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
Direct callers:
  - kernel/sys.c:__sys_setfsgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setresgid
  - kernel/sys.c:__sys_setgid
  - kernel/sys.c:__sys_setregid
  - kernel/sys.c:__sys_setregid
  - kernel/groups.c:__ia32_sys_setgroups
  - kernel/groups.c:__x64_sys_setgroups
  - kernel/uid16.c:groups16_from_user
  - kernel/auditfilter.c:audit_data_to_entry
  - mm/shmem.c:shmem_parse_one
  - fs/open.c:chown_common
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
  - fs/proc/root.c:proc_reconfigure
  - fs/proc/root.c:proc_fill_super
  - fs/proc/base.c:task_dump_owner
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
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/fat/inode.c:parse_options
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/inode.c:fuse_parse_param
  - fs/fuse/inode.c:fuse_change_attributes_common
  - fs/debugfs/inode.c:debugfs_parse_options
  - fs/tracefs/inode.c:tracefs_parse_options
  - ipc/util.c:ipc_update_perm
  - security/keys/keyctl.c:keyctl_chown_key
  - security/apparmor/policy.c:policy_view_capable
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/af_inet.c:inet_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
  - net/sysctl_net.c:net_ctl_set_ownership
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff811757c0-ffffffff811757d9: make_kgid (STB_GLOBAL)
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
