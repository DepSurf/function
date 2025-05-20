# Function: <code>devcgroup_check_permission</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127f08f)
Location: include/linux/device_cgroup.h:24
Inline: True
```
```
In fs/block_dev.c (ffffffff812b4e9a)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In fs/namei.c (ffffffff812a7a95)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff812dd023)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In fs/namei.c (ffffffff812bcb35)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff812f2483)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In fs/namei.c (ffffffff812d9642)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff81313eb9)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In fs/namei.c (ffffffff812eb152)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff81327699)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81513470)
Location: security/device_cgroup.c:835
Inline: False
Direct callers:
  - fs/namei.c:vfs_mknod
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff81513470-ffffffff81513514: devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff815305c0)
Location: security/device_cgroup.c:835
Inline: False
Direct callers:
  - fs/namei.c:vfs_mknod
```
**Symbols:**

```
ffffffff815305c0-ffffffff8153066d: devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff815367c0)
Location: security/device_cgroup.c:835
Inline: False
Direct callers:
  - fs/namei.c:vfs_mknod
```
**Symbols:**

```
ffffffff815367c0-ffffffff8153686e: devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81594ef0)
Location: security/device_cgroup.c:835
Inline: False
Direct callers:
  - fs/namei.c:vfs_mknod
  - block/bdev.c:blkdev_get_by_path
```
**Symbols:**

```
ffffffff81594ef0-ffffffff81594f9b: devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81637090)
Location: security/device_cgroup.c:836
Inline: False
Direct callers:
  - fs/namei.c:vfs_mknod
  - block/bdev.c:blkdev_get_by_path
```
**Symbols:**

```
ffffffff81637090-ffffffff81637148: devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff816ee2e0)
Location: security/device_cgroup.c:861
Inline: False
Direct callers:
  - fs/namei.c:vfs_mknod
  - block/bdev.c:blkdev_get_by_path
```
**Symbols:**

```
ffffffff816ee2e0-ffffffff816ee398: devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81728770)
Location: security/device_cgroup.c:860
Inline: False
Direct callers:
  - fs/namei.c:vfs_mknod
  - block/bdev.c:blkdev_get_by_path
```
**Symbols:**

```
ffffffff81728770-ffffffff8172883e: devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81769aa0)
Location: security/device_cgroup.c:860
Inline: False
Direct callers:
  - fs/namei.c:vfs_mknod
  - block/bdev.c:bdev_open_by_dev
```
**Symbols:**

```
ffffffff81769aa0-ffffffff81769b6e: devcgroup_check_permission (STB_GLOBAL)
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
In fs/namei.c (ffff80001039482c)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffff8000103e25ec)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In fs/namei.c (c0579d18)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (c05ba7e0)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In fs/namei.c (c00000000048b250)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (c0000000004e82d8)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In fs/namei.c (ffffffe0002632e4)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffe000298a5a)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In fs/namei.c (ffffffff812e3732)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8131fc79)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In fs/namei.c (ffffffff812d4372)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff81310819)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In fs/namei.c (ffffffff812e1542)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8131d749)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In fs/namei.c (ffffffff812f0b22)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8132f449)
Location: include/linux/device_cgroup.h:24
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
