# Function: <code>lsmblob_init</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811902dd)
Location: include/linux/security.h:193
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_exit
```
```
In security/security.c (ffffffff814a86a5)
Location: include/linux/security.h:193
Inline: True
Inline callers:
  - security/security.c:security_secctx_to_secid
  - security/security.c:security_ipc_getsecid
  - security/security.c:security_task_getsecid
  - security/security.c:security_cred_getsecid
  - security/security.c:security_inode_getsecid
```
```
In security/smack/smackfs.c (ffffffff814d7952)
Location: include/linux/security.h:193
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_netlabel_audit_set
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
In kernel/auditsc.c (ffffffff8118d55d)
Location: include/linux/security.h:195
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_exit
```
```
In security/security.c (ffffffff814c5c35)
Location: include/linux/security.h:195
Inline: True
Inline callers:
  - security/security.c:security_secctx_to_secid
  - security/security.c:security_ipc_getsecid
  - security/security.c:security_task_getsecid
  - security/security.c:security_cred_getsecid
  - security/security.c:security_inode_getsecid
```
```
In security/smack/smack_access.c (ffffffff814f49c5)
Location: include/linux/security.h:195
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/smack/smackfs.c (ffffffff814f4ed2)
Location: include/linux/security.h:195
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_netlabel_audit_set
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
In kernel/auditsc.c (ffffffff8118e3ad)
Location: include/linux/security.h:196
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_exit
```
```
In security/security.c (ffffffff814cbf12)
Location: include/linux/security.h:196
Inline: True
Inline callers:
  - security/security.c:security_secctx_to_secid
  - security/security.c:security_ipc_getsecid
  - security/security.c:security_task_getsecid_obj
  - security/security.c:security_task_getsecid_subj
  - security/security.c:security_cred_getsecid
  - security/security.c:security_inode_getsecid
```
```
In security/smack/smack_access.c (ffffffff814fb935)
Location: include/linux/security.h:196
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/smack/smackfs.c (ffffffff814fbe42)
Location: include/linux/security.h:196
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_netlabel_audit_set
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
In kernel/auditsc.c (ffffffff811b71c9)
Location: include/linux/security.h:196
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_exit
```
```
In security/security.c (ffffffff81524e92)
Location: include/linux/security.h:196
Inline: True
Inline callers:
  - security/security.c:security_secctx_to_secid
  - security/security.c:security_ipc_getsecid
  - security/security.c:security_task_getsecid_obj
  - security/security.c:security_task_getsecid_subj
  - security/security.c:security_cred_getsecid
  - security/security.c:security_inode_getsecid
```
```
In security/smack/smack_access.c (ffffffff815565a5)
Location: include/linux/security.h:196
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/smack/smackfs.c (ffffffff81556ab8)
Location: include/linux/security.h:196
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_netlabel_audit_set
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
In kernel/auditsc.c (ffffffff811e74bb)
Location: include/linux/security.h:180
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_reset_context
```
```
In security/security.c (ffffffff815b8e56)
Location: include/linux/security.h:180
Inline: True
Inline callers:
  - security/security.c:security_secctx_to_secid
  - security/security.c:security_ipc_getsecid
  - security/security.c:security_task_getsecid_obj
  - security/security.c:security_current_getsecid_subj
  - security/security.c:security_cred_getsecid
  - security/security.c:security_inode_getsecid
```
```
In security/smack/smackfs.c (ffffffff815f3fd3)
Location: include/linux/security.h:180
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
```
```
In net/netlink/af_netlink.c (ffffffff81caaa76)
Location: include/linux/security.h:180
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cde9ed)
Location: include/linux/security.h:180
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/unix/af_unix.c (ffffffff81d7d9b6)
Location: include/linux/security.h:180
Inline: True
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
In kernel/auditsc.c (ffffffff8122d62a)
Location: include/linux/security.h:200
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_reset_context
```
```
In security/security.c (ffffffff81664546)
Location: include/linux/security.h:200
Inline: True
Inline callers:
  - security/security.c:security_secctx_to_secid
  - security/security.c:security_ipc_getsecid
  - security/security.c:security_task_getsecid_obj
  - security/security.c:security_current_getsecid_subj
  - security/security.c:security_cred_getsecid
  - security/security.c:security_inode_getsecid
```
```
In security/smack/smackfs.c (ffffffff816a4963)
Location: include/linux/security.h:200
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
```
```
In net/netlink/af_netlink.c (ffffffff81e67b66)
Location: include/linux/security.h:200
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9e90d)
Location: include/linux/security.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/unix/af_unix.c (ffffffff81f4aaf6)
Location: include/linux/security.h:200
Inline: True
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
In kernel/auditsc.c (ffffffff812433ba)
Location: include/linux/security.h:200
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_reset_context
```
```
In security/security.c (ffffffff8169ca1f)
Location: include/linux/security.h:200
Inline: True
Inline callers:
  - security/security.c:security_secctx_to_secid
  - security/security.c:security_ipc_getsecid
  - security/security.c:security_task_getsecid_obj
  - security/security.c:security_current_getsecid_subj
  - security/security.c:security_cred_getsecid
  - security/security.c:security_inode_getsecid
```
```
In security/smack/smackfs.c (ffffffff816dccb3)
Location: include/linux/security.h:200
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
```
```
In net/netlink/af_netlink.c (ffffffff81ec3a04)
Location: include/linux/security.h:200
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efd10c)
Location: include/linux/security.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/unix/af_unix.c (0)
Location: include/linux/security.h:200
Inline: True
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
In kernel/auditsc.c (ffffffff8125d366)
Location: include/linux/security.h:305
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_reset_context
```
```
In security/security.c (ffffffff816dda85)
Location: include/linux/security.h:305
Inline: True
Inline callers:
  - security/security.c:security_ipc_getlsmblob
  - security/security.c:security_task_getlsmblob_obj
  - security/security.c:security_current_getlsmblob_subj
  - security/security.c:security_cred_getlsmblob
```
</details>
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
