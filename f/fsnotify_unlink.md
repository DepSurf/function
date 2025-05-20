# Function: <code>fsnotify_unlink</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812da8f6)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/devpts/inode.c (ffffffff81374eb8)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffffffff814175e8)
Location: include/linux/fsnotify.h:196
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81419de5)
Location: include/linux/fsnotify.h:196
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
In fs/namei.c (ffffffff812ec406)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/devpts/inode.c (ffffffff8138d138)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffffffff814314a8)
Location: include/linux/fsnotify.h:196
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81433c35)
Location: include/linux/fsnotify.h:196
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
In fs/namei.c (ffffffff81325a5d)
Location: include/linux/fsnotify.h:213
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/libfs.c (ffffffff81346069)
Location: include/linux/fsnotify.h:213
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/devpts/inode.c (ffffffff813d85ab)
Location: include/linux/fsnotify.h:213
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
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
In fs/namei.c (ffffffff8132fa97)
Location: include/linux/fsnotify.h:211
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/libfs.c (ffffffff8135251c)
Location: include/linux/fsnotify.h:211
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/devpts/inode.c (ffffffff813ea228)
Location: include/linux/fsnotify.h:211
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
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
In fs/namei.c (ffffffff813357f7)
Location: include/linux/fsnotify.h:211
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/libfs.c (ffffffff81358f2e)
Location: include/linux/fsnotify.h:211
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/devpts/inode.c (ffffffff813f0d68)
Location: include/linux/fsnotify.h:211
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
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
In fs/namei.c (ffffffff81386094)
Location: include/linux/fsnotify.h:256
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/libfs.c (ffffffff813a77ba)
Location: include/linux/fsnotify.h:256
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/devpts/inode.c (ffffffff81442c74)
Location: include/linux/fsnotify.h:256
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
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
In fs/namei.c (ffffffff81403a99)
Location: include/linux/fsnotify.h:269
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/libfs.c (ffffffff8142c35e)
Location: include/linux/fsnotify.h:269
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/devpts/inode.c (ffffffff814bea30)
Location: include/linux/fsnotify.h:269
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
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
In fs/namei.c (ffffffff8148dee9)
Location: include/linux/fsnotify.h:269
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/libfs.c (ffffffff814b9a6e)
Location: include/linux/fsnotify.h:269
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/devpts/inode.c (ffffffff815568f0)
Location: include/linux/fsnotify.h:269
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
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
In fs/namei.c (ffffffff814c2549)
Location: include/linux/fsnotify.h:271
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/libfs.c (ffffffff814eea19)
Location: include/linux/fsnotify.h:271
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/devpts/inode.c (ffffffff8158e6b0)
Location: include/linux/fsnotify.h:271
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
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
In fs/namei.c (ffffffff814f4a09)
Location: include/linux/fsnotify.h:309
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/libfs.c (ffffffff81522a1b)
Location: include/linux/fsnotify.h:309
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/devpts/inode.c (ffffffff815c73c3)
Location: include/linux/fsnotify.h:309
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
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
In fs/namei.c (ffff800010395bf8)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/devpts/inode.c (ffff80001045ee50)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffff8000105161dc)
Location: include/linux/fsnotify.h:196
Inline: True
```
```
In fs/tracefs/inode.c (ffff8000105196dc)
Location: include/linux/fsnotify.h:196
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
In fs/namei.c (c057afec)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/devpts/inode.c (c061f868)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (c06d0f64)
Location: include/linux/fsnotify.h:196
Inline: True
```
```
In fs/tracefs/inode.c (c06d3d98)
Location: include/linux/fsnotify.h:196
Inline: True
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
In fs/namei.c (c00000000048dfe8)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/devpts/inode.c (c00000000057b018)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (c00000000065ecd0)
Location: include/linux/fsnotify.h:196
Inline: True
```
```
In fs/tracefs/inode.c (c000000000662ba0)
Location: include/linux/fsnotify.h:196
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
In fs/namei.c (ffffffe000264304)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/devpts/inode.c (ffffffe0002ee954)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffffffe00037f8fa)
Location: include/linux/fsnotify.h:196
Inline: True
```
```
In fs/tracefs/inode.c (ffffffe000382a18)
Location: include/linux/fsnotify.h:196
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
In fs/namei.c (ffffffff812e49e6)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/devpts/inode.c (ffffffff81385718)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffffffff81429a88)
Location: include/linux/fsnotify.h:196
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8142c215)
Location: include/linux/fsnotify.h:196
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
In fs/namei.c (ffffffff812d5626)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/devpts/inode.c (ffffffff813761a8)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffffffff8141a508)
Location: include/linux/fsnotify.h:196
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8141cc95)
Location: include/linux/fsnotify.h:196
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
In fs/namei.c (ffffffff812e27f6)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/devpts/inode.c (ffffffff813831e8)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffffffff81425c28)
Location: include/linux/fsnotify.h:196
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff814283b5)
Location: include/linux/fsnotify.h:196
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
In fs/namei.c (ffffffff812f2384)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/namei.c:vfs_unlink
```
```
In fs/devpts/inode.c (ffffffff81396d08)
Location: include/linux/fsnotify.h:196
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_pty_kill
```
```
In fs/debugfs/inode.c (ffffffff8143cae8)
Location: include/linux/fsnotify.h:196
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8143f275)
Location: include/linux/fsnotify.h:196
Inline: True
```
</details>
</li>
</ul>

## Differences
