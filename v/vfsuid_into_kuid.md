# Function: <code>vfsuid_into_kuid</code>

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
In fs/stat.c (0)
Location: include/linux/mnt_idmapping.h:307
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/mnt_idmapping.h:307
Inline: True
```
```
In fs/posix_acl.c (ffffffff8151761d)
Location: include/linux/mnt_idmapping.h:307
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
```
```
In security/commoncap.c (ffffffff81661dfa)
Location: include/linux/mnt_idmapping.h:307
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/apparmor/domain.c (ffffffff816ca7c0)
Location: include/linux/mnt_idmapping.h:307
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/mnt_idmapping.h:307
Inline: True
```
```
In security/apparmor/file.c (0)
Location: include/linux/mnt_idmapping.h:307
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
In fs/stat.c (0)
Location: include/linux/mnt_idmapping.h:166
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/mnt_idmapping.h:166
Inline: True
```
```
In fs/posix_acl.c (ffffffff8154eed9)
Location: include/linux/mnt_idmapping.h:166
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
```
```
In security/commoncap.c (ffffffff8169a3d3)
Location: include/linux/mnt_idmapping.h:166
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/apparmor/domain.c (ffffffff817033fe)
Location: include/linux/mnt_idmapping.h:166
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/mnt_idmapping.h:166
Inline: True
```
```
In security/apparmor/file.c (0)
Location: include/linux/mnt_idmapping.h:166
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
In fs/stat.c (0)
Location: include/linux/mnt_idmapping.h:166
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/mnt_idmapping.h:166
Inline: True
```
```
In fs/posix_acl.c (ffffffff81584d19)
Location: include/linux/mnt_idmapping.h:166
Inline: True
Inline callers:
  - fs/posix_acl.c:do_get_acl
```
```
In security/commoncap.c (ffffffff816d6b13)
Location: include/linux/mnt_idmapping.h:166
Inline: True
Inline callers:
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/apparmor/domain.c (ffffffff81740bf7)
Location: include/linux/mnt_idmapping.h:166
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
```
In security/apparmor/lsm.c (0)
Location: include/linux/mnt_idmapping.h:166
Inline: True
```
```
In security/apparmor/file.c (0)
Location: include/linux/mnt_idmapping.h:166
Inline: True
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
