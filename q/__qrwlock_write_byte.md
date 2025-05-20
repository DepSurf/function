# Function: <code>__qrwlock_write_byte</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/exit.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/resource.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/sys.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/locking/spinlock.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/exec.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In security/integrity/iint.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/sched/ematch.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/asm-generic/qrwlock.h:154
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
In kernel/fork.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/exit.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/resource.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/sys.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/locking/spinlock.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/exec.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In security/integrity/iint.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/sched/ematch.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/asm-generic/qrwlock.h:154
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
In kernel/fork.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/exit.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/resource.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/sys.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/locking/spinlock.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/exec.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/fcntl.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/filesystems.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/jbd2/transaction.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/jbd2/checkpoint.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In security/integrity/iint.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/sched/ematch.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/asm-generic/qrwlock.h:154
Inline: True
```
</details>
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
