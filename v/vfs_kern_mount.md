# Function: <code>vfs_kern_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122c640)
Location: fs/namespace.c:934
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:kern_mount_data
  - fs/namespace.c:mnt_init
  - fs/namespace.c:do_mount
  - fs/libfs.c:simple_pin_fs
```
**Symbols:**

```
ffffffff8122c640-ffffffff8122c74e: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81254dd0)
Location: fs/namespace.c:934
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_automount
  - fs/namespace.c:kern_mount_data
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
```
**Symbols:**

```
ffffffff81254dd0-ffffffff81254ede: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81268330)
Location: fs/namespace.c:962
Inline: False
Direct callers:
  - fs/namespace.c:kern_mount_data
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
```
**Symbols:**

```
ffffffff81268330-ffffffff8126843e: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff81275dc5)
Location: fs/namespace.c:963
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount_data
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount_data
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
```
**Symbols:**

```
ffffffff81275c90-ffffffff81275d97: vfs_kern_mount.part.20 (STB_LOCAL)
ffffffff81275da0-ffffffff81275dbd: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff81298595)
Location: fs/namespace.c:1030
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount_data
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount_data
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
```
**Symbols:**

```
ffffffff81298420-ffffffff81298527: vfs_kern_mount.part.23 (STB_LOCAL)
ffffffff81298530-ffffffff8129854d: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812be655)
Location: fs/namespace.c:1040
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount_data
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount_data
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
```
**Symbols:**

```
ffffffff812be4e0-ffffffff812be5e7: vfs_kern_mount.part.36 (STB_LOCAL)
ffffffff812be5f0-ffffffff812be60d: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812d3a55)
Location: fs/namespace.c:952
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount_data
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount_data
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
```
**Symbols:**

```
ffffffff812d38e0-ffffffff812d39ee: vfs_kern_mount.part.38 (STB_LOCAL)
ffffffff812d39f0-ffffffff812d3a0d: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812f0ab8)
Location: fs/namespace.c:979
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
```
**Symbols:**

```
ffffffff812f09c0-ffffffff812f0a4b: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffff812f0a50-ffffffff812f0a6d: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff81302658)
Location: fs/namespace.c:979
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff81302560-ffffffff813025eb: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffff813025f0-ffffffff8130260d: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8133bc78)
Location: fs/namespace.c:995
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:init_mount_tree
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:init_mount_tree
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff8133bb60-ffffffff8133bc0b: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffff8133bc10-ffffffff8133bc2d: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff81347b18)
Location: fs/namespace.c:995
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:init_mount_tree
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:init_mount_tree
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff81347a00-ffffffff81347aab: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffff81347ab0-ffffffff81347acd: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8134dfc8)
Location: fs/namespace.c:1002
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff8134deb0-ffffffff8134df5b: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffff8134df60-ffffffff8134df7d: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8139bfc8)
Location: fs/namespace.c:1011
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff8139beb0-ffffffff8139bf5b: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffff8139bf60-ffffffff8139bf7d: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8141ef25)
Location: fs/namespace.c:1052
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff8141edb0-ffffffff8141ee75: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffff8141ee80-ffffffff8141eeb5: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff814ab445)
Location: fs/namespace.c:1158
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff814ab2a0-ffffffff814ab365: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffff814ab380-ffffffff814ab3b5: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff814e0245)
Location: fs/namespace.c:1121
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff814e00a0-ffffffff814e0165: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffff814e0180-ffffffff814e01b5: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff81513515)
Location: fs/namespace.c:1134
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff81513370-ffffffff81513435: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffff81513450-ffffffff81513485: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffff8000103b5390)
Location: fs/namespace.c:979
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffff8000103b51d8-ffff8000103b5298: vfs_kern_mount.part.0 (STB_LOCAL)
ffff8000103b5298-ffff8000103b52ec: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (c0593ec8)
Location: fs/namespace.c:979
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
c0593d90-c0593e2c: vfs_kern_mount.part.0 (STB_LOCAL)
c0593e2c-c0593e58: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (c0000000004b19c8)
Location: fs/namespace.c:979
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
c0000000004b1810-c0000000004b1914: vfs_kern_mount.part.0 (STB_LOCAL)
c0000000004b1920-c0000000004b1948: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffe0002783e0)
Location: fs/namespace.c:979
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffe00027827c-ffffffe000278314: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffe000278314-ffffffe00027835a: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812fac38)
Location: fs/namespace.c:979
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff812fab40-ffffffff812fabcb: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffff812fabd0-ffffffff812fabed: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812eb858)
Location: fs/namespace.c:979
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff812eb760-ffffffff812eb7eb: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffff812eb7f0-ffffffff812eb80d: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812f8a28)
Location: fs/namespace.c:979
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff812f8930-ffffffff812f89bb: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffff812f89c0-ffffffff812f89dd: vfs_kern_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct vfsmount *vfs_kern_mount(struct file_system_type *type, int flags, const char *name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff81309e28)
Location: fs/namespace.c:979
Inline: True
Inline callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
Direct callers:
  - fs/namespace.c:kern_mount
  - fs/namespace.c:mnt_init
  - fs/libfs.c:simple_pin_fs
  - drivers/base/devtmpfs.c:devtmpfs_init
```
**Symbols:**

```
ffffffff81309d70-ffffffff81309dfb: vfs_kern_mount.part.0 (STB_LOCAL)
ffffffff81309e00-ffffffff81309e1d: vfs_kern_mount (STB_GLOBAL)
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
