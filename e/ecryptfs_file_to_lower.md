# Function: <code>ecryptfs_file_to_lower</code>

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
In fs/ecryptfs/file.c (ffffffff81300c65)
Location: fs/ecryptfs/ecryptfs_kernel.h:443
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff81302446)
Location: fs/ecryptfs/ecryptfs_kernel.h:443
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff81334c7e)
Location: fs/ecryptfs/ecryptfs_kernel.h:442
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff8133645c)
Location: fs/ecryptfs/ecryptfs_kernel.h:442
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff8134aa4e)
Location: fs/ecryptfs/ecryptfs_kernel.h:442
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff8134c11c)
Location: fs/ecryptfs/ecryptfs_kernel.h:442
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff8135f5de)
Location: fs/ecryptfs/ecryptfs_kernel.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff81360c02)
Location: fs/ecryptfs/ecryptfs_kernel.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff8138424e)
Location: fs/ecryptfs/ecryptfs_kernel.h:458
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff813858d6)
Location: fs/ecryptfs/ecryptfs_kernel.h:458
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff813b3005)
Location: fs/ecryptfs/ecryptfs_kernel.h:458
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff813b4649)
Location: fs/ecryptfs/ecryptfs_kernel.h:458
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff813cc4e5)
Location: fs/ecryptfs/ecryptfs_kernel.h:458
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff813cdb69)
Location: fs/ecryptfs/ecryptfs_kernel.h:458
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff813f7045)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff813f870c)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff81410f15)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff8141256c)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff8145ef15)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff81460bad)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff8147abb5)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff8147c7bd)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff814805f5)
Location: fs/ecryptfs/ecryptfs_kernel.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff81482274)
Location: fs/ecryptfs/ecryptfs_kernel.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff814d7e95)
Location: fs/ecryptfs/ecryptfs_kernel.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff814d915c)
Location: fs/ecryptfs/ecryptfs_kernel.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff81565515)
Location: fs/ecryptfs/ecryptfs_kernel.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff8156696c)
Location: fs/ecryptfs/ecryptfs_kernel.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff81608735)
Location: fs/ecryptfs/ecryptfs_kernel.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff81609ee8)
Location: fs/ecryptfs/ecryptfs_kernel.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff81640575)
Location: fs/ecryptfs/ecryptfs_kernel.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff81641da8)
Location: fs/ecryptfs/ecryptfs_kernel.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff81679b25)
Location: fs/ecryptfs/ecryptfs_kernel.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff8167b3cb)
Location: fs/ecryptfs/ecryptfs_kernel.h:441
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffff8000104f2104)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffff8000104f394c)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (c06afa84)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (c06b1390)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (c000000000631bfc)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (c000000000633be4)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffe0003619e8)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffe000362e3a)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff814094f5)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff8140ab4c)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff813f9f75)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff813fb5cc)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff81406875)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff81407ecc)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
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
In fs/ecryptfs/file.c (ffffffff8141c535)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/file.c:ecryptfs_compat_ioctl
  - fs/ecryptfs/file.c:ecryptfs_unlocked_ioctl
  - fs/ecryptfs/file.c:ecryptfs_fasync
  - fs/ecryptfs/file.c:ecryptfs_dir_llseek
  - fs/ecryptfs/file.c:ecryptfs_dir_release
  - fs/ecryptfs/file.c:ecryptfs_flush
  - fs/ecryptfs/file.c:ecryptfs_mmap
  - fs/ecryptfs/file.c:ecryptfs_readdir
```
```
In fs/ecryptfs/inode.c (ffffffff8141db8c)
Location: fs/ecryptfs/ecryptfs_kernel.h:444
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
</details>
</li>
</ul>

## Differences
