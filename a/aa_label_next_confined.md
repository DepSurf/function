# Function: <code>aa_label_next_confined</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8138a3a0)
Location: security/apparmor/label.c:466
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/file.c:path_name
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/net.c:aa_label_sk_perm
  - security/apparmor/net.c:aa_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
```
**Symbols:**

```
ffffffff8138a3a0-ffffffff8138a432: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c5080)
Location: security/apparmor/label.c:466
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff813c5080-ffffffff813c512e: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813dc6d0)
Location: security/apparmor/label.c:482
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff813dc6d0-ffffffff813dc77e: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ed210)
Location: security/apparmor/label.c:485
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_label_sk_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff813ed210-ffffffff813ed25b: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81414c20)
Location: security/apparmor/label.c:485
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_label_sk_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff81414c20-ffffffff81414c6b: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81447020)
Location: security/apparmor/label.c:484
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_label_sk_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff81447020-ffffffff81447067: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81463f50)
Location: security/apparmor/label.c:485
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff81463f50-ffffffff81463f97: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81491210)
Location: security/apparmor/label.c:481
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff81491210-ffffffff81491243: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814ab0c0)
Location: security/apparmor/label.c:475
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff814ab0c0-ffffffff814ab0f3: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81509af0)
Location: security/apparmor/label.c:475
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff81509af0-ffffffff81509b23: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81526960)
Location: security/apparmor/label.c:475
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff81526960-ffffffff81526993: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8152c2f0)
Location: security/apparmor/label.c:475
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff8152c2f0-ffffffff8152c323: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8158a6e0)
Location: security/apparmor/label.c:475
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff8158a6e0-ffffffff8158a713: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8162bb70)
Location: security/apparmor/label.c:477
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff8162bb70-ffffffff8162bbaf: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff816e0570)
Location: security/apparmor/label.c:477
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/lsm.c:apparmor_task_prctl
  - security/apparmor/lsm.c:apparmor_task_prctl
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff816e0570-ffffffff816e05af: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81719b80)
Location: security/apparmor/label.c:477
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/lsm.c:apparmor_task_prctl
  - security/apparmor/lsm.c:apparmor_task_prctl
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff81719b80-ffffffff81719bbf: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81758620)
Location: security/apparmor/label.c:483
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:apparmor_secmark_check
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff81758620-ffffffff8175865f: aa_label_next_confined (STB_GLOBAL)
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
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a2080)
Location: security/apparmor/label.c:475
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffff8000105a2080-ffff8000105a20ec: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c07526fc)
Location: security/apparmor/label.c:475
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:path_name
  - security/apparmor/file.c:path_name
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
c07526fc-c075274c: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071d080)
Location: security/apparmor/label.c:475
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
c00000000071d080-c00000000071d0e4: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ecaaa)
Location: security/apparmor/label.c:475
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffe0003ecaaa-ffffffe0003ecaf8: aa_label_next_confined (STB_GLOBAL)
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
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a36a0)
Location: security/apparmor/label.c:475
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff814a36a0-ffffffff814a36d3: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814940c0)
Location: security/apparmor/label.c:475
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff814940c0-ffffffff814940f3: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149f740)
Location: security/apparmor/label.c:475
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff8149f740-ffffffff8149f773: aa_label_next_confined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_label_next_confined(struct aa_label *label, int i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b7d70)
Location: security/apparmor/label.c:475
Inline: False
Direct callers:
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/capability.c:aa_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:__aa_transition_rlimits
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/resource.c:aa_task_setrlimit
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/net.c:aa_af_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_label_sk_perm
  - security/apparmor/af_unix.c:aa_unix_create_perm
```
**Symbols:**

```
ffffffff814b7d70-ffffffff814b7da3: aa_label_next_confined (STB_GLOBAL)
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
