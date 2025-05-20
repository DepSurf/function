# Function: <code>lock_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81223b3f)
Location: fs/dcache.c:585
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
```
```
In fs/ecryptfs/inode.c (ffffffff813018ae)
Location: fs/ecryptfs/inode.c:39
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124c2da)
Location: fs/dcache.c:587
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
```
```
In fs/ecryptfs/inode.c (ffffffff8133669b)
Location: fs/ecryptfs/inode.c:38
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125f2ba)
Location: fs/dcache.c:587
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
```
```
In fs/ecryptfs/inode.c (ffffffff8134c35b)
Location: fs/ecryptfs/inode.c:38
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126cc0a)
Location: fs/dcache.c:621
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
```
```
In fs/ecryptfs/inode.c (ffffffff81360ebc)
Location: fs/ecryptfs/inode.c:38
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128ef7a)
Location: fs/dcache.c:628
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:shrink_dentry_list
  - fs/dcache.c:d_prune_aliases
```
```
In fs/ecryptfs/inode.c (ffffffff81385b8c)
Location: fs/ecryptfs/inode.c:38
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b5fce)
Location: fs/dcache.c:612
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
```
```
In fs/ecryptfs/inode.c (ffffffff813b48eb)
Location: fs/ecryptfs/inode.c:38
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cb4be)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
```
```
In fs/ecryptfs/inode.c (ffffffff813cde0b)
Location: fs/ecryptfs/inode.c:38
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e7b9e)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
```
```
In fs/ecryptfs/inode.c (ffffffff813f894b)
Location: fs/ecryptfs/inode.c:24
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f972e)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
```
```
In fs/ecryptfs/inode.c (ffffffff814127ab)
Location: fs/ecryptfs/inode.c:24
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81332be3)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
```
```
In fs/ecryptfs/inode.c (ffffffff8146041a)
Location: fs/ecryptfs/inode.c:24
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133e14e)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
```
```
In fs/ecryptfs/inode.c (ffffffff8147c03a)
Location: fs/ecryptfs/inode.c:24
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8134453e)
Location: fs/dcache.c:628
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
```
```
In fs/ecryptfs/inode.c (ffffffff81481ab5)
Location: fs/ecryptfs/inode.c:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8139202e)
Location: fs/dcache.c:628
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dentry_kill
```
```
In fs/ecryptfs/inode.c (ffffffff814d9875)
Location: fs/ecryptfs/inode.c:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81413c13)
Location: fs/dcache.c:653
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
```
```
In fs/ecryptfs/inode.c (ffffffff815670b5)
Location: fs/ecryptfs/inode.c:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149f023)
Location: fs/dcache.c:653
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
```
```
In fs/ecryptfs/inode.c (ffffffff8160a6d5)
Location: fs/ecryptfs/inode.c:27
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d4343)
Location: fs/dcache.c:653
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
```
```
In fs/ecryptfs/inode.c (ffffffff816425b5)
Location: fs/ecryptfs/inode.c:27
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
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
In fs/ecryptfs/inode.c (ffffffff8167bbe5)
Location: fs/ecryptfs/inode.c:27
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_rmdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a7d78)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
```
```
In fs/ecryptfs/inode.c (ffff8000104f3ba4)
Location: fs/ecryptfs/inode.c:24
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0589d10)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
```
```
In fs/ecryptfs/inode.c (c06b15a0)
Location: fs/ecryptfs/inode.c:24
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a2fd0)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
```
```
In fs/ecryptfs/inode.c (c000000000633f68)
Location: fs/ecryptfs/inode.c:24
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026e326)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
```
```
In fs/ecryptfs/inode.c (ffffffe000362fe0)
Location: fs/ecryptfs/inode.c:24
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1d0e)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
```
```
In fs/ecryptfs/inode.c (ffffffff8140ad8b)
Location: fs/ecryptfs/inode.c:24
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e293e)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
```
```
In fs/ecryptfs/inode.c (ffffffff813fb80b)
Location: fs/ecryptfs/inode.c:24
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812efb1e)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
```
```
In fs/ecryptfs/inode.c (ffffffff8140810b)
Location: fs/ecryptfs/inode.c:24
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81300fee)
Location: fs/dcache.c:625
Inline: True
Inline callers:
  - fs/dcache.c:d_prune_aliases
  - fs/dcache.c:dput
```
```
In fs/ecryptfs/inode.c (ffffffff8141ddcb)
Location: fs/ecryptfs/inode.c:24
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_link
  - fs/ecryptfs/inode.c:ecryptfs_create
```
</details>
</li>
</ul>

## Differences
