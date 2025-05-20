# Function: <code>ext4_write_trylock_xattr</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81324559)
Location: fs/ext4/xattr.h:121
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8130320d)
Location: fs/ext4/xattr.h:134
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81327c00)
Location: fs/ext4/xattr.h:135
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81355857)
Location: fs/ext4/xattr.h:146
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136db87)
Location: fs/ext4/xattr.h:146
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813971ab)
Location: fs/ext4/xattr.h:146
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813afbdb)
Location: fs/ext4/xattr.h:146
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f6480)
Location: fs/ext4/xattr.h:147
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81408de7)
Location: fs/ext4/xattr.h:147
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8141452f)
Location: fs/ext4/xattr.h:147
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814678af)
Location: fs/ext4/xattr.h:147
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e754c)
Location: fs/ext4/xattr.h:160
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81580f0c)
Location: fs/ext4/xattr.h:160
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b84bc)
Location: fs/ext4/xattr.h:160
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815f125c)
Location: fs/ext4/xattr.h:160
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff8000104846a4)
Location: fs/ext4/xattr.h:146
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0645c78)
Location: fs/ext4/xattr.h:146
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a9998)
Location: fs/ext4/xattr.h:146
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030ca98)
Location: fs/ext4/xattr.h:146
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a81bb)
Location: fs/ext4/xattr.h:146
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81398c4b)
Location: fs/ext4/xattr.h:146
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a5a1b)
Location: fs/ext4/xattr.h:146
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ba156)
Location: fs/ext4/xattr.h:146
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
</ul>

## Differences
