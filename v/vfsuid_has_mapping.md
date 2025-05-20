# Function: <code>vfsuid_has_mapping</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810fa85b)
Location: include/linux/mnt_idmapping.h:293
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/exec.c (ffffffff81483741)
Location: include/linux/mnt_idmapping.h:293
Inline: True
Inline callers:
  - fs/exec.c:bprm_fill_uid
```
```
In fs/inode.c (ffffffff814a252f)
Location: include/linux/mnt_idmapping.h:293
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
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
In kernel/capability.c (ffffffff811068d2)
Location: include/linux/mnt_idmapping.h:152
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/exec.c (ffffffff814bb603)
Location: include/linux/mnt_idmapping.h:152
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/inode.c (ffffffff814d709a)
Location: include/linux/mnt_idmapping.h:152
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
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
In kernel/capability.c (ffffffff81110222)
Location: include/linux/mnt_idmapping.h:152
Inline: True
Inline callers:
  - kernel/capability.c:privileged_wrt_inode_uidgid
```
```
In fs/exec.c (ffffffff814edb73)
Location: include/linux/mnt_idmapping.h:152
Inline: True
Inline callers:
  - fs/exec.c:begin_new_exec
```
```
In fs/inode.c (ffffffff8150941a)
Location: include/linux/mnt_idmapping.h:152
Inline: True
Inline callers:
  - fs/inode.c:inode_owner_or_capable
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
