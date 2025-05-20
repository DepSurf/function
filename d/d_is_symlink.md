# Function: <code>d_is_symlink</code>

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
In fs/namei.c (ffffffff8121aa91)
Location: include/linux/dcache.h:440
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
```
In fs/namespace.c (0)
Location: include/linux/dcache.h:440
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/linux/dcache.h:440
Inline: True
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
In fs/namei.c (ffffffff81244535)
Location: include/linux/dcache.h:414
Inline: True
Inline callers:
  - fs/namei.c:do_file_open_root
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff812568bb)
Location: include/linux/dcache.h:414
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff8124b60b)
Location: include/linux/dcache.h:414
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
```
```
In fs/namei.c (ffffffff812506b5)
Location: include/linux/dcache.h:414
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff8126a50b)
Location: include/linux/dcache.h:414
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff8125773d)
Location: include/linux/dcache.h:420
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
```
```
In fs/namei.c (ffffffff8125c845)
Location: include/linux/dcache.h:420
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff81277c8d)
Location: include/linux/dcache.h:420
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff8127998d)
Location: include/linux/dcache.h:421
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
```
```
In fs/namei.c (ffffffff8127eb65)
Location: include/linux/dcache.h:421
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff8129a6cd)
Location: include/linux/dcache.h:421
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff812a0429)
Location: include/linux/dcache.h:422
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812a54f5)
Location: include/linux/dcache.h:422
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff812c079d)
Location: include/linux/dcache.h:422
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff812b5409)
Location: include/linux/dcache.h:419
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812ba665)
Location: include/linux/dcache.h:419
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff812d59ed)
Location: include/linux/dcache.h:419
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff812d21b9)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812d7265)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff812f3bcc)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff812e3d49)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812e8dc5)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff8130577c)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff8131a629)
Location: include/linux/dcache.h:419
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff81321475)
Location: include/linux/dcache.h:419
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:step_into
```
```
In fs/namespace.c (ffffffff8133f0a0)
Location: include/linux/dcache.h:419
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff81325cb9)
Location: include/linux/dcache.h:420
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff8132ca15)
Location: include/linux/dcache.h:420
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:step_into
```
```
In fs/namespace.c (ffffffff8134b100)
Location: include/linux/dcache.h:420
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff8132bded)
Location: include/linux/dcache.h:423
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff813325e5)
Location: include/linux/dcache.h:423
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:step_into
```
```
In fs/namespace.c (ffffffff813519b0)
Location: include/linux/dcache.h:423
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff8137955d)
Location: include/linux/dcache.h:423
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff8137fd75)
Location: include/linux/dcache.h:423
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:step_into
```
```
In fs/namespace.c (ffffffff8139fd20)
Location: include/linux/dcache.h:423
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff813f8a27)
Location: include/linux/dcache.h:413
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff813fffc5)
Location: include/linux/dcache.h:413
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:step_into
```
```
In fs/namespace.c (ffffffff81423310)
Location: include/linux/dcache.h:413
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff81481fa7)
Location: include/linux/dcache.h:413
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff8148a005)
Location: include/linux/dcache.h:413
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:step_into
```
```
In fs/namespace.c (ffffffff814afa50)
Location: include/linux/dcache.h:413
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff814b6bb7)
Location: include/linux/dcache.h:413
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff814beee5)
Location: include/linux/dcache.h:413
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:step_into
```
```
In fs/namespace.c (ffffffff814e4a80)
Location: include/linux/dcache.h:413
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff814e8ee7)
Location: include/linux/dcache.h:420
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff814f1585)
Location: include/linux/dcache.h:420
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:step_into
```
```
In fs/namespace.c (ffffffff815188a0)
Location: include/linux/dcache.h:420
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffff80001038a7d8)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffff8000103921dc)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffff8000103b8e94)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (c0572d70)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (c057972c)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (c0596814)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (c000000000482b88)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (c00000000048a9c0)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (c0000000004b5fc4)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffe00025cada)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffe0002613c0)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffe00027b23a)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff812dc329)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812e13a5)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff812fdd5c)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff812ccfa9)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812d1fe5)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff812ee97c)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff812da139)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812df1b5)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff812fbb4c)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
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
In fs/stat.c (ffffffff812eb049)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/stat.c:do_readlinkat
```
```
In fs/namei.c (ffffffff812f05a5)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namei.c:vfs_get_link
  - fs/namei.c:vfs_readlink
  - fs/namei.c:do_file_open_root
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
```
In fs/namespace.c (ffffffff8130ce6c)
Location: include/linux/dcache.h:417
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
```
</details>
</li>
</ul>

## Differences
