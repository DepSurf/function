# Function: <code>fsnotify_rmdir</code>

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
In fs/namei.c (ffffffff812da732)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/configfs/dir.c (ffffffff813721aa)
Location: include/linux/fsnotify.h:219
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/debugfs/inode.c (ffffffff81417623)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81419e37)
Location: include/linux/fsnotify.h:219
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
In fs/namei.c (ffffffff812ec242)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/configfs/dir.c (ffffffff8138a7ba)
Location: include/linux/fsnotify.h:219
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/debugfs/inode.c (ffffffff814314e3)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81433c87)
Location: include/linux/fsnotify.h:219
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
In fs/namei.c (ffffffff81322594)
Location: include/linux/fsnotify.h:236
Inline: True
```
```
In fs/libfs.c (ffffffff81345f7c)
Location: include/linux/fsnotify.h:236
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff813d5b6d)
Location: include/linux/fsnotify.h:236
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
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
In fs/namei.c (ffffffff8132db5a)
Location: include/linux/fsnotify.h:234
Inline: True
```
```
In fs/libfs.c (ffffffff8135244d)
Location: include/linux/fsnotify.h:234
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff813e785d)
Location: include/linux/fsnotify.h:234
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
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
In fs/namei.c (ffffffff8133563b)
Location: include/linux/fsnotify.h:234
Inline: True
```
```
In fs/libfs.c (ffffffff81358e86)
Location: include/linux/fsnotify.h:234
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff813ee22d)
Location: include/linux/fsnotify.h:234
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
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
In fs/libfs.c (ffffffff813a76ee)
Location: include/linux/fsnotify.h:279
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
```
```
In fs/configfs/dir.c (ffffffff8143fa56)
Location: include/linux/fsnotify.h:279
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
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
In fs/libfs.c (0)
Location: include/linux/fsnotify.h:296
Inline: True
```
```
In fs/configfs/dir.c (ffffffff814bbfbb)
Location: include/linux/fsnotify.h:296
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
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
In fs/libfs.c (0)
Location: include/linux/fsnotify.h:296
Inline: True
```
```
In fs/configfs/dir.c (ffffffff81553ae6)
Location: include/linux/fsnotify.h:296
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
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
In fs/libfs.c (0)
Location: include/linux/fsnotify.h:298
Inline: True
```
```
In fs/configfs/dir.c (ffffffff8158b876)
Location: include/linux/fsnotify.h:298
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
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
In fs/libfs.c (0)
Location: include/linux/fsnotify.h:336
Inline: True
```
```
In fs/configfs/dir.c (ffffffff815c45ac)
Location: include/linux/fsnotify.h:336
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
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
In fs/namei.c (ffff8000103959dc)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/configfs/dir.c (ffff80001045ade0)
Location: include/linux/fsnotify.h:219
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/debugfs/inode.c (ffff800010516214)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/tracefs/inode.c (ffff800010519738)
Location: include/linux/fsnotify.h:219
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
In fs/namei.c (c057addc)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/configfs/dir.c (c061c998)
Location: include/linux/fsnotify.h:219
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/debugfs/inode.c (c06d0fa8)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/tracefs/inode.c (c06d3df8)
Location: include/linux/fsnotify.h:219
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
In fs/namei.c (c00000000048d418)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/configfs/dir.c (c000000000576838)
Location: include/linux/fsnotify.h:219
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/debugfs/inode.c (c00000000065ed8c)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/tracefs/inode.c (c000000000662c38)
Location: include/linux/fsnotify.h:219
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
In fs/namei.c (ffffffe000264138)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/configfs/dir.c (ffffffe0002eb6ec)
Location: include/linux/fsnotify.h:219
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/debugfs/inode.c (ffffffe00037f962)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/tracefs/inode.c (ffffffe000382a6e)
Location: include/linux/fsnotify.h:219
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
In fs/namei.c (ffffffff812e4822)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/configfs/dir.c (ffffffff81382d9a)
Location: include/linux/fsnotify.h:219
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/debugfs/inode.c (ffffffff81429ac3)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8142c267)
Location: include/linux/fsnotify.h:219
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
In fs/namei.c (ffffffff812d5462)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/configfs/dir.c (ffffffff8137382a)
Location: include/linux/fsnotify.h:219
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/debugfs/inode.c (ffffffff8141a543)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8141cce7)
Location: include/linux/fsnotify.h:219
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
In fs/namei.c (ffffffff812e2632)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/configfs/dir.c (ffffffff8138086a)
Location: include/linux/fsnotify.h:219
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/debugfs/inode.c (ffffffff81425c63)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff81428407)
Location: include/linux/fsnotify.h:219
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
In fs/namei.c (ffffffff812f21c0)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/configfs/dir.c (ffffffff81394326)
Location: include/linux/fsnotify.h:219
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_unregister_subsystem
  - fs/configfs/dir.c:configfs_unregister_group
```
```
In fs/debugfs/inode.c (ffffffff8143cb23)
Location: include/linux/fsnotify.h:219
Inline: True
```
```
In fs/tracefs/inode.c (ffffffff8143f2c7)
Location: include/linux/fsnotify.h:219
Inline: True
```
</details>
</li>
</ul>

## Differences
