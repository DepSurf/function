# Function: <code>fsnotify_inode_delete</code>

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
In fs/inode.c (ffffffff81227b79)
Location: include/linux/fsnotify.h:120
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/inode_mark.c (ffffffff81250199)
Location: include/linux/fsnotify.h:120
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
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
In fs/inode.c (ffffffff812502a9)
Location: include/linux/fsnotify.h:99
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/inode_mark.c (ffffffff812788f5)
Location: include/linux/fsnotify.h:99
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
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
In fs/inode.c (ffffffff81263349)
Location: include/linux/fsnotify.h:103
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/inode_mark.c (ffffffff8128c567)
Location: include/linux/fsnotify.h:103
Inline: True
Inline callers:
  - fs/notify/inode_mark.c:fsnotify_unmount_inodes
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
In fs/inode.c (ffffffff81270b76)
Location: include/linux/fsnotify.h:103
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff81298c78)
Location: include/linux/fsnotify.h:103
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
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
In fs/inode.c (ffffffff812934a6)
Location: include/linux/fsnotify.h:104
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff812bc008)
Location: include/linux/fsnotify.h:104
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
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
In fs/inode.c (ffffffff812b90d6)
Location: include/linux/fsnotify.h:104
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff812e4c2a)
Location: include/linux/fsnotify.h:104
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
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
In fs/inode.c (ffffffff812ce21f)
Location: include/linux/fsnotify.h:116
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff812f96b5)
Location: include/linux/fsnotify.h:116
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (ffffffff812eb0df)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff81319d15)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (ffffffff812fcc1f)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff8132cb45)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (ffffffff8133548f)
Location: include/linux/fsnotify.h:157
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff81366695)
Location: include/linux/fsnotify.h:157
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
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
In fs/inode.c (ffffffff81340e04)
Location: include/linux/fsnotify.h:160
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff8137380d)
Location: include/linux/fsnotify.h:160
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
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
In fs/inode.c (ffffffff813471f4)
Location: include/linux/fsnotify.h:160
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff8137a16d)
Location: include/linux/fsnotify.h:160
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
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
In fs/inode.c (ffffffff81394c54)
Location: include/linux/fsnotify.h:169
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff813c6e2b)
Location: include/linux/fsnotify.h:169
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (ffffffff81416ffc)
Location: include/linux/fsnotify.h:174
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff8144e162)
Location: include/linux/fsnotify.h:174
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (ffffffff814a25fc)
Location: include/linux/fsnotify.h:174
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff814dc852)
Location: include/linux/fsnotify.h:174
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (ffffffff814d775c)
Location: include/linux/fsnotify.h:176
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff815130a2)
Location: include/linux/fsnotify.h:176
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (ffffffff81509a6c)
Location: include/linux/fsnotify.h:214
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff81547552)
Location: include/linux/fsnotify.h:214
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (ffff8000103acdf0)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffff8000103e855c)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (c058dccc)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (c05bfefc)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (c0000000004a85d8)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (c0000000004eefc0)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (ffffffe000271c1a)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffe00029d224)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (ffffffff812f51ff)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff81325125)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (ffffffff812e5e1f)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff81315cc5)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (ffffffff812f300f)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff81322bf5)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
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
In fs/inode.c (ffffffff81304953)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/notify/fsnotify.c (ffffffff81334941)
Location: include/linux/fsnotify.h:141
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
</details>
</li>
</ul>

## Differences
