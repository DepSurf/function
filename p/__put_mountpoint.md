# Function: <code>__put_mountpoint</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f0510)
Location: fs/namespace.c:755
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff812f0510-ffffffff812f05a7: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813020b0)
Location: fs/namespace.c:755
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff813020b0-ffffffff81302147: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff813409f6)
Location: fs/namespace.c:771
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff8133b2a0-ffffffff8133b32d: __put_mountpoint.part.0 (STB_LOCAL)
ffffffff8133b330-ffffffff8133b347: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8134ca86)
Location: fs/namespace.c:771
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff81347140-ffffffff813471cd: __put_mountpoint.part.0 (STB_LOCAL)
ffffffff813471d0-ffffffff813471e7: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff81353654)
Location: fs/namespace.c:785
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff8134d8f0-ffffffff8134d97d: __put_mountpoint.part.0 (STB_LOCAL)
ffffffff8134d980-ffffffff8134d997: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff813a1aa4)
Location: fs/namespace.c:787
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff8139b8c0-ffffffff8139b94d: __put_mountpoint.part.0 (STB_LOCAL)
ffffffff8139b950-ffffffff8139b967: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff814254a7)
Location: fs/namespace.c:830
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff8141d670-ffffffff8141d702: __put_mountpoint.part.0 (STB_LOCAL)
ffffffff8141d710-ffffffff8141d73b: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff814b1c27)
Location: fs/namespace.c:941
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff814a9a60-ffffffff814a9af2: __put_mountpoint.part.0 (STB_LOCAL)
ffffffff814a9b10-ffffffff814a9b3b: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff814e6c76)
Location: fs/namespace.c:850
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff814de940-ffffffff814de9d2: __put_mountpoint.part.0 (STB_LOCAL)
ffffffff814de9f0-ffffffff814dea1b: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8151aab6)
Location: fs/namespace.c:838
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff81511570-ffffffff81511602: __put_mountpoint.part.0 (STB_LOCAL)
ffffffff81511620-ffffffff8151164b: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b53c0)
Location: fs/namespace.c:755
Inline: True
Direct callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffff8000103b53c0-ffff8000103b54ac: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (c059885c)
Location: fs/namespace.c:755
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:umount_mnt
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:umount_mnt
```
**Symbols:**

```
c05933cc-c0593464: __put_mountpoint.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (c0000000004b8358)
Location: fs/namespace.c:755
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:umount_mnt
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
  - fs/namespace.c:umount_mnt
```
**Symbols:**

```
c0000000004b0570-c0000000004b0680: __put_mountpoint.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000278408)
Location: fs/namespace.c:755
Inline: True
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffe000278408-ffffffe0002784cc: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fa690)
Location: fs/namespace.c:755
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff812fa690-ffffffff812fa727: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812eb2b0)
Location: fs/namespace.c:755
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff812eb2b0-ffffffff812eb347: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f8480)
Location: fs/namespace.c:755
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff812f8480-ffffffff812f8517: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __put_mountpoint(struct mountpoint *mp, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813099c0)
Location: fs/namespace.c:755
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:unlock_mount
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:mnt_change_mountpoint
```
**Symbols:**

```
ffffffff813099c0-ffffffff81309a55: __put_mountpoint (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
