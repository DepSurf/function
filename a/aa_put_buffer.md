# Function: <code>aa_put_buffer</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void aa_put_buffer(char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff82d0661c)
Location: security/apparmor/lsm.c:1743
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
  - security/apparmor/lsm.c:alloc_buffers
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
ffffffff81505530-ffffffff81505587: aa_put_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void aa_put_buffer(char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff82ff39b9)
Location: security/apparmor/lsm.c:1743
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
  - security/apparmor/lsm.c:alloc_buffers
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
ffffffff81522700-ffffffff81522757: aa_put_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void aa_put_buffer(char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff831fe4d6)
Location: security/apparmor/lsm.c:1753
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
  - security/apparmor/lsm.c:alloc_buffers
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
ffffffff815288e0-ffffffff81528937: aa_put_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void aa_put_buffer(char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff832e57e8)
Location: security/apparmor/lsm.c:1753
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
  - security/apparmor/lsm.c:alloc_buffers
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
ffffffff81586b80-ffffffff81586bd7: aa_put_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void aa_put_buffer(char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8349c61b)
Location: security/apparmor/lsm.c:1993
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
Direct callers:
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
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
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
ffffffff81626f10-ffffffff81626f75: aa_put_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void aa_put_buffer(char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816dae00)
Location: security/apparmor/lsm.c:2116
Inline: False
Direct callers:
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/lsm.c:alloc_buffers
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
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
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
ffffffff816dae00-ffffffff816daf52: aa_put_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aa_put_buffer(char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81714520)
Location: security/apparmor/lsm.c:2272
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:listener_ioctl
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/lsm.c:alloc_buffers
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
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
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
ffffffff81714520-ffffffff81714668: aa_put_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aa_put_buffer(char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81752f80)
Location: security/apparmor/lsm.c:2283
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:listener_ioctl
  - security/apparmor/ipc.c:aa_mqueue_perm
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
  - security/apparmor/lsm.c:alloc_buffers
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
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_new_mount
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
ffffffff81752f80-ffffffff8175307a: aa_put_buffer (STB_GLOBAL)
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
