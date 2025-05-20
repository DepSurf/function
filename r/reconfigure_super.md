# Function: <code>reconfigure_super</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cfad0)
Location: fs/super.c:897
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812cfad0-ffffffff812cfcf4: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e1560)
Location: fs/super.c:903
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:vfs_get_super
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812e1560-ffffffff812e1784: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813188e0)
Location: fs/super.c:903
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff813188e0-ffffffff81318af7: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81323e20)
Location: fs/super.c:850
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81323e20-ffffffff81324037: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81329ee0)
Location: fs/super.c:851
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81329ee0-ffffffff8132a101: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81377510)
Location: fs/super.c:851
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81377510-ffffffff81377731: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:850
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81e76078-ffffffff81e760b0: reconfigure_super.cold (STB_LOCAL)
ffffffff813f6760-ffffffff813f69b5: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:893
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:vfs_get_super
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff82068740-ffffffff82068778: reconfigure_super.cold (STB_LOCAL)
ffffffff8147f880-ffffffff8147fad8: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:900
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:vfs_get_super
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff820e8043-ffffffff820e807b: reconfigure_super.cold (STB_LOCAL)
ffffffff814b4560-ffffffff814b47cb: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1010
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff821c4d7f-ffffffff821c4db7: reconfigure_super.cold (STB_LOCAL)
ffffffff814e6a50-ffffffff814e6cbb: reconfigure_super (STB_GLOBAL)
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
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010388950)
Location: fs/super.c:903
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:vfs_get_super
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__arm64_sys_fsconfig
```
**Symbols:**

```
ffff800010388950-ffff800010388b28: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c0570f6c)
Location: fs/super.c:903
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:vfs_get_super
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c0570f6c-c0571184: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047f6d0)
Location: fs/super.c:903
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:vfs_get_super
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c00000000047f6d0-c00000000047f9d0: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025aef6)
Location: fs/super.c:903
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:vfs_get_super
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
ffffffe00025aef6-ffffffe00025b0a6: reconfigure_super (STB_GLOBAL)
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
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d9b40)
Location: fs/super.c:903
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:vfs_get_super
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812d9b40-ffffffff812d9d64: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812ca7c0)
Location: fs/super.c:903
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:vfs_get_super
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812ca7c0-ffffffff812ca9e4: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7950)
Location: fs/super.c:903
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:vfs_get_super
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812d7950-ffffffff812d7b74: reconfigure_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int reconfigure_super(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e8790)
Location: fs/super.c:903
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:vfs_get_super
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff812e8790-ffffffff812e89b4: reconfigure_super (STB_GLOBAL)
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
