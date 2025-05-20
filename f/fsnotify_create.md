# Function: <code>fsnotify_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81218449)
Location: include/linux/fsnotify.h:158
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
```
In fs/devpts/inode.c (ffffffff8128e537)
Location: include/linux/fsnotify.h:158
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8131de27)
Location: include/linux/fsnotify.h:158
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8131f4a7)
Location: include/linux/fsnotify.h:158
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81242cce)
Location: include/linux/fsnotify.h:137
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
```
In fs/devpts/inode.c (ffffffff812bbac9)
Location: include/linux/fsnotify.h:137
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff813529d2)
Location: include/linux/fsnotify.h:137
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81354977)
Location: include/linux/fsnotify.h:137
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81255c45)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
```
In fs/devpts/inode.c (ffffffff812d1111)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81368c82)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8136ac37)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81260cdd)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
```
In fs/devpts/inode.c (ffffffff812e2780)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8137d312)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8137f287)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81284648)
Location: include/linux/fsnotify.h:142
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
```
In fs/devpts/inode.c (ffffffff813071b0)
Location: include/linux/fsnotify.h:142
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff813a2226)
Location: include/linux/fsnotify.h:142
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff813a42c7)
Location: include/linux/fsnotify.h:142
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812aa155)
Location: include/linux/fsnotify.h:142
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff81335145)
Location: include/linux/fsnotify.h:142
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff813d146e)
Location: include/linux/fsnotify.h:142
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff813d3697)
Location: include/linux/fsnotify.h:142
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c097e)
Location: include/linux/fsnotify.h:154
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff8134c3d5)
Location: include/linux/fsnotify.h:154
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff813ebd2c)
Location: include/linux/fsnotify.h:154
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff813edd87)
Location: include/linux/fsnotify.h:154
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dc7b9)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff81374d9f)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81417e1d)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8141a03c)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff812ee2de)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff8138d01f)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81431cdd)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81433eb6)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff813253a6)
Location: include/linux/fsnotify.h:187
Inline: True
Inline callers:
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff813d846f)
Location: include/linux/fsnotify.h:187
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814815dd)
Location: include/linux/fsnotify.h:187
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81483c66)
Location: include/linux/fsnotify.h:187
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff81330b26)
Location: include/linux/fsnotify.h:185
Inline: True
Inline callers:
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff813ea10e)
Location: include/linux/fsnotify.h:185
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8149f102)
Location: include/linux/fsnotify.h:185
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a12c6)
Location: include/linux/fsnotify.h:185
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff81337364)
Location: include/linux/fsnotify.h:185
Inline: True
Inline callers:
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff813f0c4e)
Location: include/linux/fsnotify.h:185
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814a50e5)
Location: include/linux/fsnotify.h:185
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a73f6)
Location: include/linux/fsnotify.h:185
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff81384da6)
Location: include/linux/fsnotify.h:194
Inline: True
Inline callers:
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff81442b3e)
Location: include/linux/fsnotify.h:194
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff814fd226)
Location: include/linux/fsnotify.h:194
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814ff6e4)
Location: include/linux/fsnotify.h:194
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff814021fb)
Location: include/linux/fsnotify.h:203
Inline: True
Inline callers:
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff814be8da)
Location: include/linux/fsnotify.h:203
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8158da70)
Location: include/linux/fsnotify.h:203
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81590743)
Location: include/linux/fsnotify.h:203
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff8148c458)
Location: include/linux/fsnotify.h:203
Inline: True
Inline callers:
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff8155677a)
Location: include/linux/fsnotify.h:203
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff81634160)
Location: include/linux/fsnotify.h:203
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81637bd3)
Location: include/linux/fsnotify.h:203
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff814c3284)
Location: include/linux/fsnotify.h:205
Inline: True
Inline callers:
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff8158e53a)
Location: include/linux/fsnotify.h:205
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8166c470)
Location: include/linux/fsnotify.h:205
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8166ffd3)
Location: include/linux/fsnotify.h:205
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff814f575a)
Location: include/linux/fsnotify.h:243
Inline: True
Inline callers:
  - fs/namei.c:vfs_mknod
  - fs/namei.c:open_last_lookups
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff815c7250)
Location: include/linux/fsnotify.h:243
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff816a6ce6)
Location: include/linux/fsnotify.h:243
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff816aad14)
Location: include/linux/fsnotify.h:243
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffff800010397aec)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffff80001045ed08)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffff800010516a50)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffff800010519960)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (c057ded4)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (c061f754)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (c06d1808)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (c06d4068)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (c000000000491a20)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (c00000000057ae94)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (c00000000065fa7c)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (c00000000066303c)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffe000265a8e)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffe0002ee87a)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffe000380126)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffe000382c3e)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff812e68be)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff813855ff)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8142a2bd)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8142c496)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff812d74fe)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff8137608f)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8141ad3d)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8141cf16)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff812e46ce)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff813830cf)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8142645d)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81428636)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
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
In fs/namei.c (ffffffff812f564e)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
```
In fs/devpts/inode.c (ffffffff81396bef)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_new
```
```
In fs/debugfs/inode.c (ffffffff8143d31d)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8143f4f6)
Location: include/linux/fsnotify.h:171
Inline: True
Inline callers:
  - fs/tracefs/inode.c:tracefs_create_file
```
</details>
</li>
</ul>

## Differences
