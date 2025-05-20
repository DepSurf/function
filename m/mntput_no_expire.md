# Function: <code>mntput_no_expire</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122cec0)
Location: fs/namespace.c:1091
Inline: True
Direct callers:
  - fs/namespace.c:drop_mountpoint
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mount_subtree
```
**Symbols:**

```
ffffffff8122cec0-ffffffff8122d03b: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81255650)
Location: fs/namespace.c:1091
Inline: True
Direct callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:drop_mountpoint
```
**Symbols:**

```
ffffffff81255650-ffffffff812557db: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81268a40)
Location: fs/namespace.c:1136
Inline: True
Direct callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:drop_mountpoint
```
**Symbols:**

```
ffffffff81268a40-ffffffff81268bcb: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812761f0)
Location: fs/namespace.c:1137
Inline: True
Direct callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:drop_mountpoint
```
**Symbols:**

```
ffffffff812761f0-ffffffff8127636b: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81298b30)
Location: fs/namespace.c:1202
Inline: True
Direct callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:drop_mountpoint
```
**Symbols:**

```
ffffffff81298b30-ffffffff81298cc0: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bed10)
Location: fs/namespace.c:1213
Inline: True
Direct callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:drop_mountpoint
```
**Symbols:**

```
ffffffff812bed10-ffffffff812beeaf: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d3fe0)
Location: fs/namespace.c:1125
Inline: True
Direct callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:drop_mountpoint
```
**Symbols:**

```
ffffffff812d3fe0-ffffffff812d417f: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f0fd0)
Location: fs/namespace.c:1131
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
```
**Symbols:**

```
ffffffff812f0fd0-ffffffff812f1212: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81302b70)
Location: fs/namespace.c:1131
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
```
**Symbols:**

```
ffffffff81302b70-ffffffff81302db2: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133c500)
Location: fs/namespace.c:1147
Inline: False
Direct callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff8133c500-ffffffff8133c76b: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813483a0)
Location: fs/namespace.c:1147
Inline: False
Direct callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:path_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff813483a0-ffffffff81348629: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134e760)
Location: fs/namespace.c:1157
Inline: False
Direct callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:path_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff8134e760-ffffffff8134e9f4: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139c790)
Location: fs/namespace.c:1166
Inline: False
Direct callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:path_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff8139c790-ffffffff8139ca53: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141f690)
Location: fs/namespace.c:1207
Inline: False
Direct callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:path_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff8141f690-ffffffff8141f945: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814abc00)
Location: fs/namespace.c:1312
Inline: False
Direct callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:path_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff814abc00-ffffffff814abe56: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e09c0)
Location: fs/namespace.c:1275
Inline: False
Direct callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:kern_unmount
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:path_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff814e09c0-ffffffff814e0c1c: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81514a90)
Location: fs/namespace.c:1288
Inline: False
Direct callers:
  - fs/namespace.c:kern_unmount_array
  - fs/namespace.c:kern_unmount
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:path_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff81514a90-ffffffff81514cec: mntput_no_expire (STB_LOCAL)
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
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b5ed8)
Location: fs/namespace.c:1131
Inline: False
Direct callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
```
**Symbols:**

```
ffff8000103b5ed8-ffff8000103b6194: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0594248)
Location: fs/namespace.c:1131
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
```
**Symbols:**

```
c0594248-c05944d4: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b2320)
Location: fs/namespace.c:1131
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
```
**Symbols:**

```
c0000000004b2320-c0000000004b26f4: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000278c20)
Location: fs/namespace.c:1131
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
```
**Symbols:**

```
ffffffe000278c20-ffffffe000278ea8: mntput_no_expire (STB_LOCAL)
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
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fb150)
Location: fs/namespace.c:1131
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
```
**Symbols:**

```
ffffffff812fb150-ffffffff812fb392: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ebd70)
Location: fs/namespace.c:1131
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
```
**Symbols:**

```
ffffffff812ebd70-ffffffff812ebfb2: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f8f40)
Location: fs/namespace.c:1131
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
```
**Symbols:**

```
ffffffff812f8f40-ffffffff812f9182: mntput_no_expire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mntput_no_expire(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130a260)
Location: fs/namespace.c:1131
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:mntput
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:cleanup_mnt
```
**Symbols:**

```
ffffffff8130a260-ffffffff8130a4ad: mntput_no_expire (STB_LOCAL)
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
