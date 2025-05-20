# Function: <code>fc_drop_locked</code>

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
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8130acc0)
Location: fs/fs_context.c:330
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff8130acc0-ffffffff8130acf1: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8131dca0)
Location: fs/fs_context.c:328
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff8131dca0-ffffffff8131dcd1: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81357a60)
Location: fs/fs_context.c:302
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_new_mount_fc
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81357a60-ffffffff81357a91: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81364550)
Location: fs/fs_context.c:302
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_new_mount_fc
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81364550-ffffffff81364581: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8136afb0)
Location: fs/fs_context.c:302
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff8136afb0-ffffffff8136afe1: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813b9c70)
Location: fs/fs_context.c:325
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff813b9c70-ffffffff813b9ca1: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8143f750)
Location: fs/fs_context.c:325
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff8143f750-ffffffff8143f787: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff814ce430)
Location: fs/fs_context.c:325
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff814ce430-ffffffff814ce467: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81504680)
Location: fs/fs_context.c:346
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:__do_sys_fsconfig
```
**Symbols:**

```
ffffffff81504680-ffffffff815046b7: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81539340)
Location: fs/fs_context.c:374
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_new_mount
  - fs/fsopen.c:vfs_cmd_create
```
**Symbols:**

```
ffffffff81539340-ffffffff81539377: fc_drop_locked (STB_GLOBAL)
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
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffff8000103d5e18)
Location: fs/fs_context.c:328
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__arm64_sys_fsconfig
```
**Symbols:**

```
ffff8000103d5e18-ffff8000103d5e54: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c05afaf0)
Location: fs/fs_context.c:328
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c05afaf0-c05afb28: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c0000000004d94f0)
Location: fs/fs_context.c:328
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
c0000000004d94f0-c0000000004d9554: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffe00028fcd4)
Location: fs/fs_context.c:328
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__se_sys_fsconfig
```
**Symbols:**

```
ffffffe00028fcd4-ffffffe00028fd14: fc_drop_locked (STB_GLOBAL)
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
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81316280)
Location: fs/fs_context.c:328
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff81316280-ffffffff813162b1: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81306e70)
Location: fs/fs_context.c:328
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff81306e70-ffffffff81306ea1: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81314070)
Location: fs/fs_context.c:328
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff81314070-ffffffff813140a1: fc_drop_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fc_drop_locked(struct fs_context *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813258c0)
Location: fs/fs_context.c:328
Inline: False
Direct callers:
  - fs/super.c:vfs_get_tree
  - fs/namespace.c:do_mount
  - fs/fsopen.c:__ia32_sys_fsconfig
  - fs/fsopen.c:__x64_sys_fsconfig
```
**Symbols:**

```
ffffffff813258c0-ffffffff813258f1: fc_drop_locked (STB_GLOBAL)
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
