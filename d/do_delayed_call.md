# Function: <code>do_delayed_call</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81246310)
Location: include/linux/delayed_call.h:24
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:generic_readlink
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:unlazy_walk
  - fs/namei.c:terminate_walk
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
In fs/namei.c (ffffffff81259310)
Location: include/linux/delayed_call.h:24
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:unlazy_walk
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffffffff8134b365)
Location: include/linux/delayed_call.h:24
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff812653d0)
Location: include/linux/delayed_call.h:24
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffffffff8135ff05)
Location: include/linux/delayed_call.h:24
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff81287c70)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffffffff81384bc5)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff812a609e)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:link_path_walk
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffffffff813b39d9)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff812bb20e)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffffffff813cceb9)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff812dfca8)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffffffff813f7a27)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff812f17d8)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffffffff814118f7)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff81329a74)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffffffff8145f7a3)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff81334fd4)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffffffff8147b3c3)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff8133b164)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:terminate_walk
```
```
In fs/crypto/hooks.c (ffffffff813a9e2f)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_symlink_getattr
```
```
In fs/ecryptfs/inode.c (ffffffff81480e13)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff81388d84)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:terminate_walk
```
```
In fs/crypto/hooks.c (ffffffff813f966f)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_symlink_getattr
```
```
In fs/ecryptfs/inode.c (ffffffff814d8713)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff81409e02)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/crypto/hooks.c (ffffffff8146c59d)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_symlink_getattr
```
```
In fs/ecryptfs/inode.c (ffffffff81565e5d)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff81494552)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/crypto/hooks.c (ffffffff814fd94d)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_symlink_getattr
```
```
In fs/ecryptfs/inode.c (ffffffff816091ad)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff814c95c2)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/crypto/hooks.c (ffffffff81534ead)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_symlink_getattr
```
```
In fs/ecryptfs/inode.c (ffffffff8164106d)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff814fbe82)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:open_last_lookups
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/crypto/hooks.c (ffffffff81569e6d)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_symlink_getattr
```
```
In fs/ecryptfs/inode.c (ffffffff8167a620)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffff80001039b060)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffff8000104f2c68)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (c0581498)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (c06b0418)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (c000000000495f3c)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (c000000000632a9c)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffe000268590)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffffffe0003622c8)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff812e9db8)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffffffff81409ed7)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff812da9f8)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffffffff813fa957)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff812e7bc8)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffffffff81407257)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
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
In fs/namei.c (ffffffff812f8b38)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
  - fs/namei.c:pick_link
  - fs/namei.c:legitimize_links
  - fs/namei.c:terminate_walk
```
```
In fs/ecryptfs/inode.c (ffffffff8141cf17)
Location: include/linux/delayed_call.h:25
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_readlink_lower
```
</details>
</li>
</ul>

## Differences
