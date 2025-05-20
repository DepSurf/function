# Function: <code>RULE_MEDIATES</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816093a1)
Location: security/apparmor/include/policy.h:276
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
```
```
In security/apparmor/task.c (ffffffff816108fb)
Location: security/apparmor/include/policy.h:276
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_may_ptrace
  - security/apparmor/task.c:aa_may_ptrace
```
```
In security/apparmor/ipc.c (ffffffff81610fa6)
Location: security/apparmor/include/policy.h:276
Inline: True
Inline callers:
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
  - security/apparmor/ipc.c:profile_signal_perm
```
```
In security/apparmor/lsm.c (ffffffff81626b00)
Location: security/apparmor/include/policy.h:276
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_setprocattr
```
```
In security/apparmor/file.c (ffffffff81628635)
Location: security/apparmor/include/policy.h:276
Inline: True
Inline callers:
  - security/apparmor/file.c:__aa_path_perm
  - security/apparmor/file.c:__aa_path_perm
```
```
In security/apparmor/mount.c (ffffffff8162feed)
Location: security/apparmor/include/policy.h:276
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/net.c (ffffffff816315ee)
Location: security/apparmor/include/policy.h:276
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_profile_af_perm
```
```
In security/apparmor/af_unix.c (ffffffff81634bdc)
Location: security/apparmor/include/policy.h:276
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_sk_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/apparmorfs.c (ffffffff816bae81)
Location: security/apparmor/include/policy.h:282
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
```
```
In security/apparmor/task.c (ffffffff816c333d)
Location: security/apparmor/include/policy.h:282
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_may_ptrace
  - security/apparmor/task.c:aa_may_ptrace
```
```
In security/apparmor/ipc.c (ffffffff816c3a06)
Location: security/apparmor/include/policy.h:282
Inline: True
Inline callers:
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
  - security/apparmor/ipc.c:profile_signal_perm
```
```
In security/apparmor/lsm.c (ffffffff816d6e0c)
Location: security/apparmor/include/policy.h:282
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_prctl
```
```
In security/apparmor/file.c (ffffffff816dcd9a)
Location: security/apparmor/include/policy.h:282
Inline: True
Inline callers:
  - security/apparmor/file.c:__aa_path_perm
  - security/apparmor/file.c:__aa_path_perm
```
```
In security/apparmor/mount.c (ffffffff816e4b5f)
Location: security/apparmor/include/policy.h:282
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/net.c (ffffffff816e632e)
Location: security/apparmor/include/policy.h:282
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_profile_af_perm
```
```
In security/apparmor/af_unix.c (ffffffff816e9b48)
Location: security/apparmor/include/policy.h:282
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/apparmorfs.c (ffffffff816f48b6)
Location: security/apparmor/include/policy.h:313
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
```
```
In security/apparmor/task.c (ffffffff816fbe7a)
Location: security/apparmor/include/policy.h:313
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
  - security/apparmor/task.c:aa_may_ptrace
  - security/apparmor/task.c:aa_may_ptrace
```
```
In security/apparmor/ipc.c (ffffffff816fc5f6)
Location: security/apparmor/include/policy.h:313
Inline: True
Inline callers:
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
  - security/apparmor/ipc.c:profile_signal_perm
```
```
In security/apparmor/lsm.c (ffffffff8170fdc2)
Location: security/apparmor/include/policy.h:313
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_userns_create
  - security/apparmor/lsm.c:apparmor_task_prctl
```
```
In security/apparmor/file.c (ffffffff81716397)
Location: security/apparmor/include/policy.h:313
Inline: True
Inline callers:
  - security/apparmor/file.c:__aa_path_perm
  - security/apparmor/file.c:__aa_path_perm
```
```
In security/apparmor/mount.c (ffffffff8171e1bf)
Location: security/apparmor/include/policy.h:313
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/net.c (ffffffff8171fa32)
Location: security/apparmor/include/policy.h:313
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_profile_af_perm
```
```
In security/apparmor/af_unix.c (ffffffff81723339)
Location: security/apparmor/include/policy.h:313
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:aa_unix_peer_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
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
In security/apparmor/apparmorfs.c (ffffffff8173166f)
Location: security/apparmor/include/policy.h:310
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:profile_query_cb
```
```
In security/apparmor/capability.c (ffffffff81737edb)
Location: security/apparmor/include/policy.h:310
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_profile_capget
  - security/apparmor/capability.c:profile_capable
```
```
In security/apparmor/task.c (ffffffff81738e24)
Location: security/apparmor/include/policy.h:310
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_profile_ns_perm
```
```
In security/apparmor/ipc.c (ffffffff81739b46)
Location: security/apparmor/include/policy.h:310
Inline: True
Inline callers:
  - security/apparmor/ipc.c:aa_profile_mqueue_perm
  - security/apparmor/ipc.c:profile_signal_perm
```
```
In security/apparmor/policy.c (ffffffff81743ff3)
Location: security/apparmor/include/policy.h:310
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff8174b875)
Location: security/apparmor/include/policy.h:310
Inline: True
```
```
In security/apparmor/file.c (ffffffff81754e4a)
Location: security/apparmor/include/policy.h:310
Inline: True
Inline callers:
  - security/apparmor/file.c:__aa_path_perm
  - security/apparmor/file.c:__aa_path_perm
```
```
In security/apparmor/mount.c (ffffffff8175cc08)
Location: security/apparmor/include/policy.h:310
Inline: True
Inline callers:
  - security/apparmor/mount.c:build_pivotroot
  - security/apparmor/mount.c:profile_umount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:match_mnt_path_str
```
```
In security/apparmor/net.c (ffffffff8175e457)
Location: security/apparmor/include/policy.h:310
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_profile_af_perm
```
```
In security/apparmor/af_unix.c (ffffffff81760b9a)
Location: security/apparmor/include/policy.h:310
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_listen_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_bind_perm
  - security/apparmor/af_unix.c:profile_create_perm
  - security/apparmor/af_unix.c:profile_create_perm
```
```
In security/apparmor/af_inet.c (ffffffff817643e4)
Location: security/apparmor/include/policy.h:310
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:aa_inet_file_perm
  - security/apparmor/af_inet.c:aa_inet_file_perm
  - security/apparmor/af_inet.c:inet_label_sock_perm
  - security/apparmor/af_inet.c:inet_label_sock_perm
  - security/apparmor/af_inet.c:aa_inet_opt_perm
  - security/apparmor/af_inet.c:aa_inet_opt_perm
  - security/apparmor/af_inet.c:aa_inet_accept_perm
  - security/apparmor/af_inet.c:aa_inet_accept_perm
  - security/apparmor/af_inet.c:aa_inet_listen_perm
  - security/apparmor/af_inet.c:aa_inet_listen_perm
  - security/apparmor/af_inet.c:aa_inet_bind_perm
  - security/apparmor/af_inet.c:aa_inet_bind_perm
  - security/apparmor/af_inet.c:aa_inet_create_perm
  - security/apparmor/af_inet.c:aa_inet_create_perm
  - security/apparmor/af_inet.c:profile_remote_perm
  - security/apparmor/af_inet.c:profile_remote_perm
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
