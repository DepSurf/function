# Function: <code>inode_mode_to_security_class</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81342fe5)
Location: security/selinux/hooks.c:1163
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137944a)
Location: security/selinux/hooks.c:1234
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8138d923)
Location: security/selinux/hooks.c:1236
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a37a1)
Location: security/selinux/hooks.c:1214
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813c95a1)
Location: security/selinux/hooks.c:1217
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fd843)
Location: security/selinux/hooks.c:1299
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81419a79)
Location: security/selinux/hooks.c:1109
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814474a9)
Location: security/selinux/hooks.c:1144
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81461039)
Location: security/selinux/hooks.c:1146
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b5859)
Location: security/selinux/hooks.c:1097
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d352e)
Location: security/selinux/hooks.c:1098
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d9ace)
Location: security/selinux/hooks.c:1156
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815329ce)
Location: security/selinux/hooks.c:1146
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c8266)
Location: security/selinux/hooks.c:1084
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81675376)
Location: security/selinux/hooks.c:1083
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816ad706)
Location: security/selinux/hooks.c:1094
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816ea799)
Location: security/selinux/hooks.c:1136
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054e8ac)
Location: security/selinux/hooks.c:1146
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c06fe264)
Location: security/selinux/hooks.c:1146
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006aebb8)
Location: security/selinux/hooks.c:1146
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a85f8)
Location: security/selinux/hooks.c:1146
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81459619)
Location: security/selinux/hooks.c:1146
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144a049)
Location: security/selinux/hooks.c:1146
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814556b9)
Location: security/selinux/hooks.c:1146
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81469ad6)
Location: security/selinux/hooks.c:1146
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_task_to_inode
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
</details>
</li>
</ul>

## Differences
