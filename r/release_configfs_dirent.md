# Function: <code>release_configfs_dirent</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff812de3b3)
Location: fs/configfs/configfs_internal.h:150
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff812df5fe)
Location: fs/configfs/configfs_internal.h:150
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff812e17f2)
Location: fs/configfs/configfs_internal.h:150
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
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
In fs/configfs/inode.c (ffffffff81302cf3)
Location: fs/configfs/configfs_internal.h:150
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81303f7e)
Location: fs/configfs/configfs_internal.h:150
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81306135)
Location: fs/configfs/configfs_internal.h:150
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
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
In fs/configfs/inode.c (ffffffff81330c41)
Location: fs/configfs/configfs_internal.h:150
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81331cfe)
Location: fs/configfs/configfs_internal.h:150
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81334144)
Location: fs/configfs/configfs_internal.h:150
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
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
In fs/configfs/inode.c (ffffffff81348031)
Location: fs/configfs/configfs_internal.h:150
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813491fe)
Location: fs/configfs/configfs_internal.h:150
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff8134b4ba)
Location: fs/configfs/configfs_internal.h:150
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
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
In fs/configfs/inode.c (ffffffff813704cb)
Location: fs/configfs/configfs_internal.h:146
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81371bb1)
Location: fs/configfs/configfs_internal.h:146
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81373e72)
Location: fs/configfs/configfs_internal.h:146
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
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
In fs/configfs/inode.c (ffffffff813889b7)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81389ff1)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff8138c093)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (ffffffff813d36f7)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813d4a11)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff813d73d3)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (ffffffff813e5437)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813e6731)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff813e9073)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (ffffffff813ec047)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813ed141)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff813efbe3)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (ffffffff8143de02)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8143f041)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81441ad3)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (ffffffff814b9709)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff814bb19c)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff814bd6c8)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (ffffffff81550e99)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81552acc)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81555348)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (ffffffff81588b79)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8158a84f)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff8158d0e8)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (ffffffff815c174c)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff815c351f)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff815c5e2e)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (ffff800010458d00)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffff80001045a4d0)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffff80001045d87c)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (c061aa5c)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (c061c274)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:detach_attrs
  - fs/configfs/dir.c:detach_attrs
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (c061e5fc)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (c000000000573a10)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (c000000000575df4)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (c0000000005795b0)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (ffffffe0002e9cf8)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffe0002eaf8a)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffe0002ed880)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
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
In fs/configfs/inode.c (ffffffff81380f97)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813825d1)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81384673)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (ffffffff81371a27)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81373061)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81375103)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (ffffffff8137ea67)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813800a1)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81382143)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/inode.c (ffffffff81392565)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81393b8f)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81395c6a)
Location: fs/configfs/configfs_internal.h:135
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
</details>
</li>
</ul>

## Differences
