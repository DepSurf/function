# Function: <code>smk_of_current</code>

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
In security/smack/smack_lsm.c (ffffffff8135dc76)
Location: security/smack/smack.h:393
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_msg_queue_alloc_security
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_syslog
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_sk_alloc_security
```
```
In security/smack/smack_access.c (ffffffff81362d36)
Location: security/smack/smack.h:393
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged
```
```
In security/smack/smackfs.c (ffffffff81363e48)
Location: security/smack/smack.h:393
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_cipso_doi
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_write_net4addr
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
In security/smack/smack_lsm.c (ffffffff81393ed6)
Location: security/smack/smack.h:393
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_msg_queue_alloc_security
  - security/smack/smack_lsm.c:smack_sem_alloc_security
  - security/smack/smack_lsm.c:smack_shm_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smack_access.c (ffffffff81398f06)
Location: security/smack/smack.h:393
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged
```
```
In security/smack/smackfs.c (ffffffff8139bf54)
Location: security/smack/smack.h:393
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff813aaaf6)
Location: security/smack/smack.h:402
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_msg_queue_alloc_security
  - security/smack/smack_lsm.c:smack_sem_alloc_security
  - security/smack/smack_lsm.c:smack_shm_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smack_access.c (ffffffff813afae6)
Location: security/smack/smack.h:402
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged
```
```
In security/smack/smackfs.c (ffffffff813b26b4)
Location: security/smack/smack.h:402
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff813c1506)
Location: security/smack/smack.h:485
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_msg_queue_alloc_security
  - security/smack/smack_lsm.c:smack_sem_alloc_security
  - security/smack/smack_lsm.c:smack_shm_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smack_access.c (ffffffff813c6688)
Location: security/smack/smack.h:485
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged
```
```
In security/smack/smackfs.c (ffffffff813c90d9)
Location: security/smack/smack.h:485
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff813e7696)
Location: security/smack/smack.h:485
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_msg_queue_alloc_security
  - security/smack/smack_lsm.c:smack_sem_alloc_security
  - security/smack/smack_lsm.c:smack_shm_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smack_access.c (ffffffff813ec978)
Location: security/smack/smack.h:485
Inline: True
Inline callers:
  - security/smack/smack_access.c:smack_privileged
```
```
In security/smack/smackfs.c (ffffffff813ef569)
Location: security/smack/smack.h:485
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff81418575)
Location: security/smack/smack.h:406
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff814205c7)
Location: security/smack/smack.h:406
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff81434b85)
Location: security/smack/smack.h:445
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff8143c803)
Location: security/smack/smack.h:445
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff814625d5)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff8146a409)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff8147c385)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff814841e9)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff814d5ccf)
Location: security/smack/smack.h:426
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff814d7915)
Location: security/smack/smack.h:426
Inline: True
Inline callers:
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
In security/smack/smack_lsm.c (ffffffff814f33af)
Location: security/smack/smack.h:419
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff814f4e95)
Location: security/smack/smack.h:419
Inline: True
Inline callers:
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
In security/smack/smack_lsm.c (ffffffff814fa15f)
Location: security/smack/smack.h:441
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff814fbe05)
Location: security/smack/smack.h:441
Inline: True
Inline callers:
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
In security/smack/smack_lsm.c (ffffffff81554d3f)
Location: security/smack/smack.h:441
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff81556a65)
Location: security/smack/smack.h:441
Inline: True
Inline callers:
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
In security/smack/smack_lsm.c (ffffffff815eeda3)
Location: security/smack/smack.h:425
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_current_getsecid_subj
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff815f3f01)
Location: security/smack/smack.h:425
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff8169f073)
Location: security/smack/smack.h:416
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_current_getsecid_subj
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff816a4891)
Location: security/smack/smack.h:416
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff816d7e53)
Location: security/smack/smack.h:417
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_current_getsecid_subj
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff816dcbe1)
Location: security/smack/smack.h:417
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff81714533)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_watch_key
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_getselfattr
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_current_getlsmblob_subj
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff81719b62)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffff80001056d090)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffff8000105760b8)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (c072086c)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (c07290b8)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (c0000000006d1600)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (c0000000006df974)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffe0003c1984)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffe0003c8eca)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff81474965)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff8147c7c9)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff81465385)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff8146d1e9)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff81470a05)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff81478869)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smack_lsm.c (ffffffff814881e5)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sock_graft
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_ipc_alloc_security
  - security/smack/smack_lsm.c:smack_msg_msg_alloc_security
  - security/smack/smack_lsm.c:smack_sk_alloc_security
  - security/smack/smack_lsm.c:smack_file_set_fowner
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_file_alloc_security
  - security/smack/smack_lsm.c:smack_inode_init_security
  - security/smack/smack_lsm.c:smack_inode_alloc_security
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_syslog
```
```
In security/smack/smackfs.c (ffffffff81490319)
Location: security/smack/smack.h:433
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
</details>
</li>
</ul>

## Differences
