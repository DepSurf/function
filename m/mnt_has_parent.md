# Function: <code>mnt_has_parent</code>

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
In fs/namespace.c (ffffffff8122c161)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:is_path_reachable
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
In fs/namespace.c (ffffffff81258454)
Location: fs/mount.h:77
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
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
In fs/namespace.c (ffffffff8126b8e4)
Location: fs/mount.h:80
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:umount_tree
  - fs/namespace.c:umount_tree
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
In fs/namespace.c (ffffffff812790b4)
Location: fs/mount.h:81
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:umount_tree
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
In fs/namespace.c (ffffffff8129baf4)
Location: fs/mount.h:82
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:umount_tree
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
In fs/namespace.c (ffffffff812c1c34)
Location: fs/mount.h:82
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:umount_tree
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
In fs/namespace.c (ffffffff812d6ed4)
Location: fs/mount.h:82
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:umount_tree
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
In fs/namespace.c (ffffffff812f5343)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
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
In fs/namespace.c (ffffffff81306ec3)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
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
In fs/namei.c (ffffffff81321afd)
Location: fs/mount.h:90
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:choose_mountpoint
```
```
In fs/namespace.c (ffffffff8133b121)
Location: fs/mount.h:90
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:umount_tree
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
In fs/namei.c (ffffffff8132c0f1)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namei.c:choose_mountpoint_rcu
```
```
In fs/namespace.c (ffffffff81346ed1)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:umount_tree
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
In fs/namei.c (ffffffff81332131)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namei.c:choose_mountpoint_rcu
```
```
In fs/namespace.c (ffffffff8134cf3b)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:path_is_under
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:umount_tree
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
In fs/namei.c (ffffffff8137f8c1)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namei.c:choose_mountpoint_rcu
```
```
In fs/namespace.c (ffffffff8139aecb)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:path_is_under
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:umount_tree
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
In fs/namei.c (ffffffff813ffa41)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namei.c:choose_mountpoint_rcu
```
```
In fs/namespace.c (ffffffff8141e5f1)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:umount_tree
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
In fs/namei.c (ffffffff81489a01)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namei.c:choose_mountpoint_rcu
```
```
In fs/namespace.c (ffffffff814aad91)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:umount_tree
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
In fs/namei.c (ffffffff814be931)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namei.c:choose_mountpoint_rcu
```
```
In fs/namespace.c (ffffffff814dfb91)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:path_is_under
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:umount_tree
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
In fs/namei.c (ffffffff814f0db1)
Location: fs/mount.h:87
Inline: True
Inline callers:
  - fs/namei.c:choose_mountpoint_rcu
```
```
In fs/namespace.c (ffffffff8151476e)
Location: fs/mount.h:87
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_listmount
  - fs/namespace.c:__ia32_sys_listmount
  - fs/namespace.c:__x64_sys_listmount
  - fs/namespace.c:__x64_sys_listmount
  - fs/namespace.c:do_statmount
  - fs/namespace.c:path_is_under
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:umount_tree
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
In fs/namespace.c (ffff8000103ba614)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
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
In fs/namespace.c (c059843c)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
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
In fs/namespace.c (c0000000004b7e08)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
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
In fs/namespace.c (ffffffe00027cb30)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
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
In fs/namespace.c (ffffffff812ff4a3)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
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
In fs/namespace.c (ffffffff812f00c3)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
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
In fs/namespace.c (ffffffff812fd293)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
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
In fs/namespace.c (ffffffff8130e5f3)
Location: fs/mount.h:84
Inline: True
Inline callers:
  - fs/namespace.c:is_path_reachable
```
</details>
</li>
</ul>

## Differences
