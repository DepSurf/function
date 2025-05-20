# Function: <code>is_anon_ns</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (0)
Location: fs/mount.h:152
Inline: True
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
In fs/namespace.c (0)
Location: fs/mount.h:152
Inline: True
```
```
In fs/d_path.c (0)
Location: fs/mount.h:152
Inline: True
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
In fs/namespace.c (ffffffff81340ddf)
Location: fs/mount.h:156
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:dissolve_on_fput
```
```
In fs/d_path.c (ffffffff813544cf)
Location: fs/mount.h:156
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
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
In fs/namespace.c (ffffffff8134ce9b)
Location: fs/mount.h:155
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:dissolve_on_fput
```
```
In fs/pnode.c (ffffffff8135c6de)
Location: fs/mount.h:155
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:next_group
  - fs/pnode.c:propagation_next
```
```
In fs/d_path.c (ffffffff81360dcb)
Location: fs/mount.h:155
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
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
In fs/namespace.c (ffffffff81353a7b)
Location: fs/mount.h:145
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:dissolve_on_fput
```
```
In fs/pnode.c (ffffffff813631a3)
Location: fs/mount.h:145
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:next_group
  - fs/pnode.c:propagation_next
```
```
In fs/d_path.c (ffffffff813678b8)
Location: fs/mount.h:145
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
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
In fs/namespace.c (ffffffff813a1ecb)
Location: fs/mount.h:145
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:dissolve_on_fput
```
```
In fs/pnode.c (ffffffff813b19a3)
Location: fs/mount.h:145
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:next_group
  - fs/pnode.c:propagation_next
```
```
In fs/d_path.c (ffffffff813b6516)
Location: fs/mount.h:145
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
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
In fs/namespace.c (ffffffff8142596b)
Location: fs/mount.h:145
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:dissolve_on_fput
```
```
In fs/pnode.c (ffffffff81436946)
Location: fs/mount.h:145
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:next_group
  - fs/pnode.c:propagation_next
```
```
In fs/d_path.c (ffffffff8143bade)
Location: fs/mount.h:145
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
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
In fs/namespace.c (ffffffff814b213b)
Location: fs/mount.h:144
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:dissolve_on_fput
```
```
In fs/pnode.c (ffffffff814c49a6)
Location: fs/mount.h:144
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:next_group
  - fs/pnode.c:propagation_next
```
```
In fs/d_path.c (ffffffff814ca0ee)
Location: fs/mount.h:144
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
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
In fs/namespace.c (ffffffff814e718b)
Location: fs/mount.h:144
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:dissolve_on_fput
```
```
In fs/pnode.c (ffffffff814f9e26)
Location: fs/mount.h:144
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagation_would_overmount
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:next_group
  - fs/pnode.c:propagation_next
```
```
In fs/d_path.c (ffffffff8150032e)
Location: fs/mount.h:144
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
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
In fs/namespace.c (ffffffff8151b01b)
Location: fs/mount.h:141
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:dissolve_on_fput
```
```
In fs/pnode.c (ffffffff8152e67e)
Location: fs/mount.h:141
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagation_would_overmount
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:propagate_mnt
  - fs/pnode.c:next_group
  - fs/pnode.c:propagation_next
```
```
In fs/d_path.c (ffffffff81534f4e)
Location: fs/mount.h:141
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
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
In fs/namespace.c (0)
Location: fs/mount.h:152
Inline: True
```
```
In fs/d_path.c (0)
Location: fs/mount.h:152
Inline: True
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
In fs/namespace.c (c0598b28)
Location: fs/mount.h:152
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:dissolve_on_fput
```
```
In fs/d_path.c (c05ac5c4)
Location: fs/mount.h:152
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
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
In fs/namespace.c (c0000000004b86a8)
Location: fs/mount.h:152
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:dissolve_on_fput
```
```
In fs/d_path.c (c0000000004d4304)
Location: fs/mount.h:152
Inline: True
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
In fs/namespace.c (ffffffe00027ac52)
Location: fs/mount.h:152
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:free_mnt_ns
  - fs/namespace.c:dissolve_on_fput
```
```
In fs/d_path.c (ffffffe00028cf62)
Location: fs/mount.h:152
Inline: True
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
In fs/namespace.c (0)
Location: fs/mount.h:152
Inline: True
```
```
In fs/d_path.c (0)
Location: fs/mount.h:152
Inline: True
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
In fs/namespace.c (0)
Location: fs/mount.h:152
Inline: True
```
```
In fs/d_path.c (0)
Location: fs/mount.h:152
Inline: True
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
In fs/namespace.c (0)
Location: fs/mount.h:152
Inline: True
```
```
In fs/d_path.c (0)
Location: fs/mount.h:152
Inline: True
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
In fs/namespace.c (0)
Location: fs/mount.h:152
Inline: True
```
```
In fs/d_path.c (0)
Location: fs/mount.h:152
Inline: True
```
</details>
</li>
</ul>

## Differences
