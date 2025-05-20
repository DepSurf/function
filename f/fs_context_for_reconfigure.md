# Function: <code>fs_context_for_reconfigure</code>

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
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8130ac70)
Location: fs/fs_context.c:314
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
**Symbols:**

```
ffffffff8130ac70-ffffffff8130ac98: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8131dc50)
Location: fs/fs_context.c:312
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
**Symbols:**

```
ffffffff8131dc50-ffffffff8131dc78: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81357a10)
Location: fs/fs_context.c:286
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fspick
```
**Symbols:**

```
ffffffff81357a10-ffffffff81357a38: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81364500)
Location: fs/fs_context.c:286
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fspick
```
**Symbols:**

```
ffffffff81364500-ffffffff81364528: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8136af60)
Location: fs/fs_context.c:286
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fspick
```
**Symbols:**

```
ffffffff8136af60-ffffffff8136af88: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813b9c20)
Location: fs/fs_context.c:309
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__do_sys_fspick
```
**Symbols:**

```
ffffffff813b9c20-ffffffff813b9c48: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8143f6e0)
Location: fs/fs_context.c:309
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
**Symbols:**

```
ffffffff8143f6e0-ffffffff8143f717: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff814ce3a0)
Location: fs/fs_context.c:309
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
**Symbols:**

```
ffffffff814ce3a0-ffffffff814ce3d7: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff815045a0)
Location: fs/fs_context.c:309
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
**Symbols:**

```
ffffffff815045a0-ffffffff815045d7: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81539260)
Location: fs/fs_context.c:337
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
**Symbols:**

```
ffffffff81539260-ffffffff81539297: fs_context_for_reconfigure (STB_GLOBAL)
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
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffff8000103d5d88)
Location: fs/fs_context.c:312
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__arm64_sys_fspick
```
**Symbols:**

```
ffff8000103d5d88-ffff8000103d5dd8: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c05af32c)
Location: fs/fs_context.c:312
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_umount
  - fs/fsopen.c:__se_sys_fspick
```
**Symbols:**

```
c05af32c-c05af36c: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c0000000004d94a0)
Location: fs/fs_context.c:312
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__se_sys_fspick
```
**Symbols:**

```
c0000000004d94a0-c0000000004d94cc: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffe00028f622)
Location: fs/fs_context.c:312
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__se_sys_fspick
```
**Symbols:**

```
ffffffe00028f622-ffffffe00028f662: fs_context_for_reconfigure (STB_GLOBAL)
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
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81316230)
Location: fs/fs_context.c:312
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
**Symbols:**

```
ffffffff81316230-ffffffff81316258: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81306e20)
Location: fs/fs_context.c:312
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
**Symbols:**

```
ffffffff81306e20-ffffffff81306e48: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81314020)
Location: fs/fs_context.c:312
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
**Symbols:**

```
ffffffff81314020-ffffffff81314048: fs_context_for_reconfigure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fs_context *fs_context_for_reconfigure(struct dentry *dentry, unsigned int sb_flags, unsigned int sb_flags_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81325870)
Location: fs/fs_context.c:312
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
  - fs/fsopen.c:__ia32_sys_fspick
  - fs/fsopen.c:__x64_sys_fspick
```
**Symbols:**

```
ffffffff81325870-ffffffff81325898: fs_context_for_reconfigure (STB_GLOBAL)
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
