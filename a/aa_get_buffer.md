# Function: <code>aa_get_buffer</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
char *aa_get_buffer(bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:1702
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff8150560b-ffffffff81505623: aa_get_buffer.cold (STB_LOCAL)
ffffffff81505420-ffffffff81505527: aa_get_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
char *aa_get_buffer(bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:1702
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff81bf17a3-ffffffff81bf17bb: aa_get_buffer.cold (STB_LOCAL)
ffffffff815225f0-ffffffff815226f7: aa_get_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
char *aa_get_buffer(bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:1712
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff81be37b3-ffffffff81be37cb: aa_get_buffer.cold (STB_LOCAL)
ffffffff815287d0-ffffffff815288d7: aa_get_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
char *aa_get_buffer(bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:1712
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff81cd66a7-ffffffff81cd66d3: aa_get_buffer.cold (STB_LOCAL)
ffffffff81586a60-ffffffff81586b73: aa_get_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *aa_get_buffer(bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:1952
Inline: False
Direct callers:
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff81e895d0-ffffffff81e895fd: aa_get_buffer.cold (STB_LOCAL)
ffffffff81626df0-ffffffff81626f0f: aa_get_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
char *aa_get_buffer(bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:2051
Inline: False
Direct callers:
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff82074c8c-ffffffff82074ca1: aa_get_buffer.cold (STB_LOCAL)
ffffffff816dab60-ffffffff816dade2: aa_get_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
char *aa_get_buffer(bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:2207
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:listener_ioctl
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff820f4891-ffffffff820f48a6: aa_get_buffer.cold (STB_LOCAL)
ffffffff81714290-ffffffff8171450a: aa_get_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
char *aa_get_buffer(bool in_atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:2220
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:listener_ioctl
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/file.c:__file_mqueue_perm
  - security/apparmor/file.c:__file_path_perm
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_link
  - security/apparmor/file.c:aa_path_perm
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_umount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff821d1d25-ffffffff821d1d3a: aa_get_buffer.cold (STB_LOCAL)
ffffffff81752d30-ffffffff81752f6c: aa_get_buffer (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
