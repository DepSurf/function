# Function: <code>vfs_create_mount</code>

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
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f0870)
Location: fs/namespace.c:941
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812f0870-ffffffff812f0968: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81302410)
Location: fs/namespace.c:941
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff81302410-ffffffff81302508: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133ba10)
Location: fs/namespace.c:957
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount_fc
```
**Symbols:**

```
ffffffff8133ba10-ffffffff8133bb08: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813478b0)
Location: fs/namespace.c:957
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount_fc
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff813478b0-ffffffff813479a8: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134dd60)
Location: fs/namespace.c:964
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount
  - fs/fuse/dir.c:fuse_dentry_automount
```
**Symbols:**

```
ffffffff8134dd60-ffffffff8134de5b: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139bd60)
Location: fs/namespace.c:973
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff8139bd60-ffffffff8139be5b: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141ebc0)
Location: fs/namespace.c:1009
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff8141ebc0-ffffffff8141ed42: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814ab100)
Location: fs/namespace.c:1120
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff814ab100-ffffffff814ab217: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814dff00)
Location: fs/namespace.c:1083
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff814dff00-ffffffff814e0017: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff815131d0)
Location: fs/namespace.c:1096
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff815131d0-ffffffff815132e7: vfs_create_mount (STB_GLOBAL)
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
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b5008)
Location: fs/namespace.c:941
Inline: False
Direct callers:
  - fs/namespace.c:__arm64_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffff8000103b5008-ffff8000103b517c: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0593c2c)
Location: fs/namespace.c:941
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
c0593c2c-c0593d50: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b15f0)
Location: fs/namespace.c:941
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
c0000000004b15f0-c0000000004b1790: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe0002780e0)
Location: fs/namespace.c:941
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffe0002780e0-ffffffe00027822c: vfs_create_mount (STB_GLOBAL)
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
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fa9f0)
Location: fs/namespace.c:941
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812fa9f0-ffffffff812faae8: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812eb610)
Location: fs/namespace.c:941
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812eb610-ffffffff812eb708: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f87e0)
Location: fs/namespace.c:941
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812f87e0-ffffffff812f88d8: vfs_create_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vfsmount *vfs_create_mount(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81309020)
Location: fs/namespace.c:941
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_fsmount
  - fs/namespace.c:__x64_sys_fsmount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff81309020-ffffffff81309116: vfs_create_mount (STB_GLOBAL)
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
