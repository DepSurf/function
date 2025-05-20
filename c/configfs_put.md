# Function: <code>configfs_put</code>

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
In fs/configfs/inode.c (ffffffff812de3a6)
Location: fs/configfs/configfs_internal.h:167
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff812e0fc7)
Location: fs/configfs/configfs_internal.h:167
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff812e1753)
Location: fs/configfs/configfs_internal.h:167
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
In fs/configfs/inode.c (ffffffff81302ce6)
Location: fs/configfs/configfs_internal.h:167
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81305957)
Location: fs/configfs/configfs_internal.h:167
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81306093)
Location: fs/configfs/configfs_internal.h:167
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
In fs/configfs/inode.c (ffffffff81330c34)
Location: fs/configfs/configfs_internal.h:167
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81333917)
Location: fs/configfs/configfs_internal.h:167
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff8133409e)
Location: fs/configfs/configfs_internal.h:167
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
In fs/configfs/inode.c (ffffffff81348024)
Location: fs/configfs/configfs_internal.h:167
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8134aca7)
Location: fs/configfs/configfs_internal.h:167
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff8134b418)
Location: fs/configfs/configfs_internal.h:167
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
In fs/configfs/inode.c (ffffffff813704ba)
Location: fs/configfs/configfs_internal.h:164
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8137359c)
Location: fs/configfs/configfs_internal.h:164
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81373dd0)
Location: fs/configfs/configfs_internal.h:164
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
In fs/configfs/inode.c (ffffffff813889aa)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8138acbe)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff8138c012)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (ffffffff813d36ea)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813d5d6d)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff813d7352)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (ffffffff813e542a)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813e7a3d)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff813e8ff2)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (ffffffff813ec03a)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff813ee660)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff813efb62)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (ffffffff8143ddf5)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81440580)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81441a52)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (ffffffff814b96f6)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff814bb379)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff814bd63f)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (ffffffff81550e86)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81552cb9)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff815552bf)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (ffffffff81588b66)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8158aa39)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff8158d05f)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (ffffffff815c1739)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff815c370f)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff815c5da5)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (ffff800010458cdc)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffff80001045af28)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffff80001045d7a4)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (c061aa28)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (c061c38c)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:detach_attrs
  - fs/configfs/dir.c:detach_attrs
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (c061e528)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (c000000000573950)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (c000000000576104)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (c000000000579494)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (ffffffe0002e9ce4)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffe0002eb066)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffe0002ed7d8)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (ffffffff81380f8a)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8138329e)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff813845f2)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (ffffffff81371a1a)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81373d2e)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81375082)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (ffffffff8137ea5a)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff81380d6e)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff813820c2)
Location: fs/configfs/configfs_internal.h:153
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
In fs/configfs/inode.c (ffffffff81392558)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffff8139482c)
Location: fs/configfs/configfs_internal.h:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffff81395beb)
Location: fs/configfs/configfs_internal.h:153
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
