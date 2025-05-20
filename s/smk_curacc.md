# Function: <code>smk_curacc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81362e80)
Location: security/smack/smack_access.c:280
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff81362e80-ffffffff81362eaf: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81399050)
Location: security/smack/smack_access.c:280
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff81399050-ffffffff8139907f: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813afc30)
Location: security/smack/smack_access.c:275
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff813afc30-ffffffff813afc5f: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813c67f0)
Location: security/smack/smack_access.c:275
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff813c67f0-ffffffff813c6829: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813ecae0)
Location: security/smack/smack_access.c:275
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff813ecae0-ffffffff813ecb19: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8141d920)
Location: security/smack/smack_access.c:275
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff8141d920-ffffffff8141d94f: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81439f10)
Location: security/smack/smack_access.c:275
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff81439f10-ffffffff81439f49: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81467ad0)
Location: security/smack/smack_access.c:271
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff81467ad0-ffffffff81467b06: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814818b0)
Location: security/smack/smack_access.c:271
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff814818b0-ffffffff814818e6: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814d78a0)
Location: security/smack/smack_access.c:271
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff814d78a0-ffffffff814d78d6: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814f4e10)
Location: security/smack/smack_access.c:271
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff814f4e10-ffffffff814f4e46: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814fbd80)
Location: security/smack/smack_access.c:271
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff814fbd80-ffffffff814fbdb6: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff815569f0)
Location: security/smack/smack_access.c:270
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff815569f0-ffffffff81556a26: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff815f0e10)
Location: security/smack/smack_access.c:270
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff815f0e10-ffffffff815f0e52: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816a1290)
Location: security/smack/smack_access.c:270
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_remove_acl
  - security/smack/smack_lsm.c:smack_inode_get_acl
  - security/smack/smack_lsm.c:smack_inode_set_acl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff816a1290-ffffffff816a12d2: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816d9be0)
Location: security/smack/smack_access.c:270
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_remove_acl
  - security/smack/smack_lsm.c:smack_inode_get_acl
  - security/smack/smack_lsm.c:smack_inode_set_acl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff816d9be0-ffffffff816d9c22: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81716680)
Location: security/smack/smack_access.c:270
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_remove_acl
  - security/smack/smack_lsm.c:smack_inode_get_acl
  - security/smack/smack_lsm.c:smack_inode_set_acl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_setattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff81716680-ffffffff817166c5: smk_curacc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffff800010573328)
Location: security/smack/smack_access.c:271
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffff800010573328-ffff800010573384: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c0726464)
Location: security/smack/smack_access.c:271
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
c0726464-c07264b8: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c0000000006db640)
Location: security/smack/smack_access.c:271
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
c0000000006db640-c0000000006db680: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffe0003c67d4)
Location: security/smack/smack_access.c:271
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffe0003c67d4-ffffffe0003c681e: smk_curacc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81479e90)
Location: security/smack/smack_access.c:271
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff81479e90-ffffffff81479ec6: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8146a8b0)
Location: security/smack/smack_access.c:271
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff8146a8b0-ffffffff8146a8e6: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81475f30)
Location: security/smack/smack_access.c:271
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff81475f30-ffffffff81475f66: smk_curacc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smk_curacc(struct smack_known *obj_known, u32 mode, struct smk_audit_info *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8148d9b0)
Location: security/smack/smack_access.c:271
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_ipc_permission
  - security/smack/smack_lsm.c:smk_curacc_msq
  - security/smack/smack_lsm.c:smk_curacc_sem
  - security/smack/smack_lsm.c:smk_curacc_shm
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_file_receive
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_fcntl
  - security/smack/smack_lsm.c:smack_file_lock
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_file_ioctl
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_getxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_getattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rename
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_rmdir
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_unlink
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_inode_link
  - security/smack/smack_lsm.c:smack_sb_statfs
```
**Symbols:**

```
ffffffff8148d9b0-ffffffff8148d9e6: smk_curacc (STB_GLOBAL)
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
