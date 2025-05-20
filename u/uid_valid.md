# Function: <code>uid_valid</code>

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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/kernfs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:110
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8112d778)
Location: include/linux/uidgid.h:110
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8112f2e4)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:110
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In kernel/auditfilter.c (ffffffff811374a8)
Location: include/linux/uidgid.h:110
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff81138fa5)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:110
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81138a08)
Location: include/linux/uidgid.h:110
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8113a5d0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:110
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:110
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/auditfilter.c (ffffffff811456f2)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff811472a0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81154093)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff81155c4f)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81160f68)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff811630fa)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8116d622)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff81170242)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/safesetid/securityfs.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/auditfilter.c (ffffffff811794c2)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8117c0c2)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/safesetid/securityfs.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
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
In kernel/sys.c (ffffffff810c3849)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
```
In kernel/cred.c (ffffffff810d7535)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/cred.c:set_create_files_as
```
```
In kernel/audit.c (ffffffff8118a125)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff8118c53c)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_data_to_entry
```
```
In kernel/auditsc.c (ffffffff8118e789)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (ffffffff8126b6e1)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/open.c (ffffffff8130de2f)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/namei.c (ffffffff813255c3)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:pick_link
```
```
In fs/inode.c (ffffffff8133798d)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff8133800f)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff81342ba8)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (ffffffff813c9946)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/devpts/inode.c (ffffffff813d7d42)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/devpts/inode.c:parse_mount_options
```
```
In fs/ext4/super.c (ffffffff8142ee36)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/hugetlbfs/inode.c (ffffffff814505e1)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fat/inode.c (ffffffff814598fc)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/fat/inode.c:parse_options
```
```
In fs/fuse/inode.c (ffffffff8147cae4)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In fs/debugfs/inode.c (ffffffff81480e33)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_parse_options
```
```
In fs/tracefs/inode.c (ffffffff814835d3)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_parse_options
```
```
In ipc/util.c (ffffffff81487620)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - ipc/util.c:ipc_update_perm
```
```
In security/keys/keyctl.c (ffffffff8149aa2e)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/persistent.c (ffffffff8149fb6e)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/commoncap.c (ffffffff814a67a9)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/tomoyo/tomoyo.c (ffffffff814e9885)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
```
```
In security/safesetid/securityfs.c (ffffffff81512918)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:parse_policy_line
  - security/safesetid/securityfs.c:parse_policy_line
```
```
In security/integrity/ima/ima_policy.c (ffffffff815192bc)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/ioprio.c (ffffffff8155be7d)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In lib/kobject_uevent.c (ffffffff815ec3de)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_broadcast_tagged
```
```
In drivers/net/tun.c (ffffffff8188a1b6)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/scm.c (ffffffff819f6e56)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff819f7f77)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81a404a2)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/sysctl_net.c (ffffffff81b9ca03)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/sysctl_net.c:net_ctl_set_ownership
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
In kernel/sys.c (ffffffff810bec59)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
```
In kernel/cred.c (ffffffff810d21f5)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/cred.c:set_create_files_as
```
```
In kernel/audit.c (ffffffff81187435)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff8118975a)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_data_to_entry
```
```
In kernel/auditsc.c (ffffffff8118b95c)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (ffffffff81276055)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/open.c (ffffffff8131b58f)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/namei.c (ffffffff81330d33)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/namei.c:vfs_link
  - fs/namei.c:may_delete
  - fs/namei.c:may_delete
  - fs/namei.c:pick_link
```
```
In fs/inode.c (ffffffff813432cd)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
```
```
In fs/attr.c (ffffffff81343979)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/xattr.c (ffffffff8134eeb8)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/xattr.c:xattr_permission
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (ffffffff813db5b6)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/devpts/inode.c (ffffffff813e99e2)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/devpts/inode.c:parse_mount_options
```
```
In fs/ext4/super.c (ffffffff81447b07)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/hugetlbfs/inode.c (ffffffff8146caf1)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fat/inode.c (ffffffff81475c4c)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/fat/inode.c:parse_options
```
```
In fs/fuse/inode.c (ffffffff81497c44)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In fs/debugfs/inode.c (ffffffff8149e463)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_parse_options
```
```
In fs/tracefs/inode.c (ffffffff814a0c43)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_parse_options
```
```
In ipc/util.c (ffffffff814a4c40)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - ipc/util.c:ipc_update_perm
```
```
In security/keys/keyctl.c (ffffffff814b865e)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/persistent.c (ffffffff814bd59e)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/commoncap.c (ffffffff814c3d59)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/tomoyo/tomoyo.c (ffffffff81506ba5)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
```
```
In security/safesetid/securityfs.c (ffffffff8152f96e)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:parse_policy_line
  - security/safesetid/securityfs.c:parse_policy_line
```
```
In security/integrity/ima/ima_policy.c (ffffffff8153635f)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/ioprio.c (ffffffff81577fd8)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In lib/kobject_uevent.c (ffffffff81610bbe)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_broadcast_tagged
```
```
In drivers/net/tun.c (ffffffff818982b6)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/scm.c (ffffffff819f68c6)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff819f79d7)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81a431a2)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/sysctl_net.c (ffffffff81bac713)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/sysctl_net.c:net_ctl_set_ownership
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
In kernel/sys.c (ffffffff810c05c9)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
```
In kernel/cred.c (ffffffff810d3dd5)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/cred.c:set_create_files_as
```
```
In kernel/audit.c (ffffffff81188371)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff8118a5b1)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_data_to_entry
```
```
In kernel/auditsc.c (ffffffff8118c80d)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (ffffffff8127b465)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (ffffffff81333865)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/namei.c:pick_link
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (ffffffff813e24e6)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/devpts/inode.c (ffffffff813f0550)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/devpts/inode.c:parse_mount_options
```
```
In fs/ext4/super.c (ffffffff8144d325)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/hugetlbfs/inode.c (ffffffff81471ec1)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fat/inode.c (ffffffff8147b6c1)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/fat/inode.c:parse_options
```
```
In fs/fuse/inode.c (ffffffff8149ce74)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In fs/debugfs/inode.c (ffffffff814a442b)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_parse_options
```
```
In fs/tracefs/inode.c (ffffffff814a6d6b)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_parse_options
```
```
In ipc/util.c (ffffffff814aac00)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - ipc/util.c:ipc_update_perm
```
```
In security/keys/keyctl.c (ffffffff814be4be)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/persistent.c (ffffffff814c340e)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/commoncap.c (ffffffff814ca202)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/tomoyo/tomoyo.c (ffffffff8150d6e5)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
```
```
In security/safesetid/securityfs.c (ffffffff81535e31)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/integrity/ima/ima_policy.c (ffffffff8153eb55)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/ioprio.c (ffffffff8157fd18)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In lib/kobject_uevent.c (ffffffff815f42d3)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
```
In drivers/net/tun.c (ffffffff8188136b)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/scm.c (ffffffff819dca34)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff819ddb57)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81a27f02)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/sysctl_net.c (ffffffff81b9b8a3)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/sysctl_net.c:net_ctl_set_ownership
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
In kernel/sys.c (ffffffff810d30b9)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
```
In kernel/cred.c (ffffffff810e6fb5)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/cred.c:set_create_files_as
```
```
In kernel/audit.c (ffffffff811b0891)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff811b30ac)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_data_to_entry
```
```
In kernel/auditsc.c (ffffffff811b5455)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (ffffffff812b9315)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (ffffffff81381195)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/namei.c:pick_link
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (ffffffff81433ff6)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/devpts/inode.c (ffffffff81442440)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/devpts/inode.c:parse_mount_options
```
```
In fs/ext4/super.c (ffffffff814a13b5)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/ext4/super.c:handle_mount_opt
```
```
In fs/hugetlbfs/inode.c (ffffffff814c8851)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fat/inode.c (ffffffff814d2d51)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/fat/inode.c:parse_options
```
```
In fs/fuse/inode.c (ffffffff814f48d4)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In fs/debugfs/inode.c (ffffffff814fc4ab)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_parse_options
```
```
In fs/tracefs/inode.c (ffffffff814feecb)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_parse_options
```
```
In ipc/util.c (ffffffff815030f0)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - ipc/util.c:ipc_update_perm
```
```
In security/keys/keyctl.c (ffffffff81516ede)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/persistent.c (ffffffff8151bdfe)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/commoncap.c (ffffffff81522ea2)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/tomoyo/tomoyo.c (ffffffff8156b225)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
```
```
In security/safesetid/securityfs.c (ffffffff81594439)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/integrity/ima/ima_policy.c (ffffffff8159e068)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/ioprio.c (ffffffff815e4ff8)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In lib/kobject_uevent.c (ffffffff81661643)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
```
In drivers/net/tun.c (ffffffff81912cc5)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/scm.c (ffffffff81a8cc74)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff81a8ddd7)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81adcca2)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/sysctl_net.c (ffffffff81c687f3)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/sysctl_net.c:net_ctl_set_ownership
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
In kernel/sys.c (ffffffff810ec6f4)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
```
In kernel/cred.c (ffffffff81101285)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/cred.c:set_create_files_as
```
```
In kernel/audit.c (ffffffff811e2a72)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff811e54de)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_data_to_entry
```
```
In kernel/auditsc.c (ffffffff811e7afe)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (ffffffff813152b2)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/open.c (ffffffff813ed43e)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/namei.c (ffffffff81404b44)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/namei.c:pick_link
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (ffffffff814ae054)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/devpts/inode.c (ffffffff814be1a7)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/devpts/inode.c:parse_mount_options
```
```
In fs/ext4/super.c (ffffffff815288f8)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/hugetlbfs/inode.c (ffffffff81553edb)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fat/inode.c (ffffffff815600f4)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/fat/inode.c:parse_options
```
```
In fs/fuse/inode.c (ffffffff815844d3)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In fs/debugfs/inode.c (ffffffff8158cb5c)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_parse_options
```
```
In fs/tracefs/inode.c (ffffffff8158febc)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_parse_options
```
```
In ipc/util.c (ffffffff81594730)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - ipc/util.c:ipc_update_perm
```
```
In security/keys/keyctl.c (ffffffff815a981e)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/persistent.c (ffffffff815af064)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/commoncap.c (ffffffff815b6c32)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/tomoyo/tomoyo.c (ffffffff816073f5)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
```
```
In security/safesetid/securityfs.c (ffffffff816364b3)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/integrity/ima/ima_policy.c (ffffffff816433ae)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/ioprio.c (ffffffff81694148)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In lib/kobject_uevent.c (ffffffff8177b3fe)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
```
In drivers/net/tun.c (ffffffff81a65ee5)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/scm.c (ffffffff81c02554)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff81c03a07)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81c5e221)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/sysctl_net.c (ffffffff81e0b953)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/sysctl_net.c:net_ctl_set_ownership
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
In kernel/sys.c (ffffffff8110da14)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
```
In kernel/cred.c (ffffffff811263c5)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/cred.c:set_create_files_as
```
```
In kernel/audit.c (ffffffff81228952)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff8122b55e)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_data_to_entry
```
```
In kernel/auditsc.c (ffffffff8122dc5e)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (ffffffff81389192)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/open.c (ffffffff81475a51)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/namei.c (ffffffff8148c0bb)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (ffffffff81544614)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/devpts/inode.c (ffffffff81555f5e)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/devpts/inode.c:parse_mount_options
```
```
In fs/ext4/super.c (ffffffff815c694c)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/hugetlbfs/inode.c (ffffffff815f572b)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fat/inode.c (ffffffff816024ec)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/fat/inode.c:parse_options
```
```
In fs/fuse/inode.c (ffffffff8162a5b3)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In fs/debugfs/inode.c (ffffffff81633539)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_parse_options
```
```
In fs/tracefs/inode.c (ffffffff81637289)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_parse_options
```
```
In ipc/util.c (ffffffff8163d3a0)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - ipc/util.c:ipc_update_perm
```
```
In security/keys/keyctl.c (ffffffff81653a7e)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/persistent.c (ffffffff81659834)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/commoncap.c (ffffffff81661c43)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/commoncap.c:cap_convert_nscap
```
```
In security/tomoyo/tomoyo.c (ffffffff816b8af5)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
```
```
In security/safesetid/securityfs.c (ffffffff816ed4d7)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fb670)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/ioprio.c (ffffffff81753128)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/net/tun.c (ffffffff81bf1085)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/scm.c (ffffffff81db19e4)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff81db3097)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e14a41)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/sysctl_net.c (ffffffff81fe15e3)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/sysctl_net.c:net_ctl_set_ownership
```
```
In lib/kobject_uevent.c (ffffffff8202460e)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In kernel/sys.c (ffffffff81119ca4)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
```
In kernel/cred.c (ffffffff81133875)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/cred.c:set_create_files_as
```
```
In kernel/audit.c (ffffffff8123ef52)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff81241b96)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_data_to_entry
```
```
In kernel/auditsc.c (ffffffff81243f73)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (ffffffff813bb36c)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/open.c (ffffffff814aa3f2)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/namei.c (ffffffff814c3e81)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff814dabc0)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (ffffffff8157c214)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/devpts/inode.c (ffffffff8158dca5)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/devpts/inode.c:parse_mount_options
```
```
In fs/ext4/super.c (ffffffff815fe49d)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/hugetlbfs/inode.c (ffffffff8162d80a)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fat/inode.c (ffffffff8163a2ad)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/fat/inode.c:parse_options
```
```
In fs/fuse/inode.c (ffffffff8166280f)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In fs/debugfs/inode.c (ffffffff8166b7e8)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_parse_options
```
```
In fs/tracefs/inode.c (ffffffff8166f628)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_parse_options
```
```
In ipc/util.c (ffffffff816758c0)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - ipc/util.c:ipc_update_perm
```
```
In security/keys/keyctl.c (ffffffff8168c28f)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/persistent.c (ffffffff816920d4)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/commoncap.c (ffffffff8169a1df)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/commoncap.c:cap_convert_nscap
```
```
In security/tomoyo/tomoyo.c (ffffffff816f14c5)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
```
```
In security/safesetid/securityfs.c (ffffffff817278eb)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/integrity/ima/ima_policy.c (ffffffff817355a8)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/ioprio.c (ffffffff8178f237)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/net/tun.c (ffffffff81c493d3)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/scm.c (ffffffff81e21f82)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff81e23667)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81e88351)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/sysctl_net.c (ffffffff8205d863)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - net/sysctl_net.c:net_ctl_set_ownership
```
```
In lib/kobject_uevent.c (ffffffff820a471e)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In kernel/sys.c (ffffffff81123694)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - kernel/sys.c:__sys_setfsuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setresuid
  - kernel/sys.c:__sys_setuid
  - kernel/sys.c:__sys_setreuid
  - kernel/sys.c:__sys_setreuid
```
```
In kernel/cred.c (ffffffff8113e7d5)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - kernel/cred.c:set_create_files_as
```
```
In kernel/audit.c (ffffffff81258dc3)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff8125b9ae)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
  - kernel/auditfilter.c:audit_data_to_entry
```
```
In kernel/auditsc.c (ffffffff8125dec4)
Location: include/linux/uidgid.h:103
Inline: True
```
```
In kernel/bpf/inode.c (ffffffff8133f4d0)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_parse_param
```
```
In mm/shmem.c (ffffffff813e5f3b)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_one
```
```
In fs/open.c (ffffffff814db892)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - fs/open.c:chown_common
```
```
In fs/namei.c (ffffffff814f655b)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In fs/attr.c (ffffffff8150d172)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - fs/attr.c:notify_change
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:103
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:103
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:103
Inline: True
```
```
In fs/proc/proc_net.c (ffffffff815b4b24)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
```
```
In fs/devpts/inode.c (ffffffff815c69e5)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - fs/devpts/inode.c:parse_mount_options
```
```
In fs/ext4/super.c (ffffffff81636f4b)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_parse_param
```
```
In fs/hugetlbfs/inode.c (ffffffff81666cd9)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In fs/fat/inode.c (ffffffff8167379d)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - fs/fat/inode.c:parse_options
```
```
In fs/fuse/inode.c (ffffffff8169c60f)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_parse_param
```
```
In fs/debugfs/inode.c (ffffffff816a5b98)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_parse_options
```
```
In fs/tracefs/inode.c (ffffffff816aa198)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_parse_options
```
```
In fs/efivarfs/super.c (ffffffff816aee2a)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_parse_param
```
```
In ipc/util.c (ffffffff816b1c80)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - ipc/util.c:ipc_update_perm
```
```
In security/keys/keyctl.c (ffffffff816c878f)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_chown_key
```
```
In security/keys/persistent.c (ffffffff816ce6a4)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/commoncap.c (ffffffff816d68ef)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - security/commoncap.c:cap_convert_nscap
```
```
In security/tomoyo/tomoyo.c (ffffffff8172e295)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - security/tomoyo/tomoyo.c:tomoyo_path_chown
```
```
In security/safesetid/securityfs.c (ffffffff81768c20)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/integrity/ima/ima_policy.c (ffffffff81776088)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
  - security/integrity/ima/ima_policy.c:ima_parse_rule
```
```
In block/ioprio.c (ffffffff817d1b17)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_set
```
```
In drivers/net/tun.c (ffffffff81cff049)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:tun_fill_info
```
```
In net/core/scm.c (ffffffff81edfea8)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
  - net/core/scm.c:__scm_send
```
```
In net/core/net_namespace.c (ffffffff81ee15c7)
Location: include/linux/uidgid.h:103
Inline: True
```
```
In net/core/fib_rules.c (ffffffff81f4a361)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/sysctl_net.c (ffffffff82130493)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - net/sysctl_net.c:net_ctl_set_ownership
```
```
In lib/kobject_uevent.c (ffffffff8217c7ee)
Location: include/linux/uidgid.h:103
Inline: True
Inline callers:
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/auditfilter.c (ffff8000101ee7fc)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffff8000101f03f4)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/safesetid/securityfs.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/auditfilter.c (c042e754)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (c04315d0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/safesetid/securityfs.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/auditfilter.c (c000000000261480)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (c00000000026370c)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/safesetid/securityfs.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/auditfilter.c (ffffffe000162828)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffe000163ffc)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/safesetid/securityfs.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81171ae2)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff811746e2)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/safesetid/securityfs.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81164c82)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff81167882)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/safesetid/securityfs.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8116f8b2)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff811724b2)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/safesetid/securityfs.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/netfilter/nfnetlink_log.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/netfilter/nf_conntrack_standalone.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/netfilter/nf_conntrack_expect.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
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
In kernel/sys.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/audit.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8117d0b7)
Location: include/linux/uidgid.h:111
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8117fdb2)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/open.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/attr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/xattr.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/proc/proc_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In ipc/util.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/keys/persistent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/commoncap.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/tomoyo/tomoyo.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/safesetid/securityfs.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In block/ioprio.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In net/sysctl_net.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/linux/uidgid.h:111
Inline: True
```
</details>
</li>
</ul>

## Differences
