# Function: <code>fsnotify_add_inode_mark_locked</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_tree.c (ffffffff8115a4f8)
Location: include/linux/fsnotify_backend.h:413
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812e6943)
Location: include/linux/fsnotify_backend.h:413
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812e7517)
Location: include/linux/fsnotify_backend.h:413
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In kernel/audit_tree.c (ffffffff811673f4)
Location: include/linux/fsnotify_backend.h:446
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812fb4d6)
Location: include/linux/fsnotify_backend.h:446
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff812fc4f3)
Location: include/linux/fsnotify_backend.h:446
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In kernel/audit_tree.c (ffffffff8117414b)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8131bdb7)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8131ce6d)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In kernel/audit_tree.c (ffffffff8117ffbb)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8132ebc0)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132fcad)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In kernel/audit_tree.c (ffffffff81192fb6)
Location: include/linux/fsnotify_backend.h:489
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81368a90)
Location: include/linux/fsnotify_backend.h:489
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81369b4a)
Location: include/linux/fsnotify_backend.h:489
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
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
In kernel/audit_tree.c (ffffffff81190126)
Location: include/linux/fsnotify_backend.h:538
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81375dba)
Location: include/linux/fsnotify_backend.h:538
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81376e4e)
Location: include/linux/fsnotify_backend.h:538
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
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
In kernel/audit_tree.c (ffffffff81191456)
Location: include/linux/fsnotify_backend.h:544
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8137c758)
Location: include/linux/fsnotify_backend.h:544
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137d94f)
Location: include/linux/fsnotify_backend.h:544
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In kernel/audit_tree.c (ffffffff811ba316)
Location: include/linux/fsnotify_backend.h:544
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In fs/notify/dnotify/dnotify.c (ffffffff813c95f1)
Location: include/linux/fsnotify_backend.h:544
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813ca88f)
Location: include/linux/fsnotify_backend.h:544
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In kernel/audit_tree.c (ffffffff811ed6a0)
Location: include/linux/fsnotify_backend.h:706
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81451020)
Location: include/linux/fsnotify_backend.h:706
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81451cec)
Location: include/linux/fsnotify_backend.h:706
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
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
In kernel/audit_tree.c (ffffffff81233c70)
Location: include/linux/fsnotify_backend.h:783
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In fs/notify/dnotify/dnotify.c (ffffffff814dfa90)
Location: include/linux/fsnotify_backend.h:783
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0a5c)
Location: include/linux/fsnotify_backend.h:783
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
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
In kernel/audit_tree.c (ffffffff8124a960)
Location: include/linux/fsnotify_backend.h:783
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81516314)
Location: include/linux/fsnotify_backend.h:783
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8151730c)
Location: include/linux/fsnotify_backend.h:783
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
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
In kernel/audit_tree.c (ffffffff81264870)
Location: include/linux/fsnotify_backend.h:779
Inline: True
Inline callers:
  - kernel/audit_tree.c:create_chunk
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8154a6b0)
Location: include/linux/fsnotify_backend.h:779
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b6fc)
Location: include/linux/fsnotify_backend.h:779
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
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
In kernel/audit_tree.c (ffff8000101f526c)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In fs/notify/dnotify/dnotify.c (ffff8000103eb5fc)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ed060)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
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
In kernel/audit_tree.c (c0435418)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In fs/notify/dnotify/dnotify.c (c05c25f0)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (c05c39d4)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
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
In kernel/audit_tree.c (c00000000026a7ac)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In fs/notify/dnotify/dnotify.c (c0000000004f29d0)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f40f0)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
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
In kernel/audit_tree.c (ffffffe0001682f2)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In fs/notify/dnotify/dnotify.c (ffffffe00029f9dc)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffe0002a0c0c)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
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
In kernel/audit_tree.c (ffffffff811785db)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In fs/notify/dnotify/dnotify.c (ffffffff813271a0)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132828d)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In kernel/audit_tree.c (ffffffff8116b77b)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81317d40)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81318e2d)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In kernel/audit_tree.c (ffffffff811763ab)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81324c70)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81325d5d)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
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
In kernel/audit_tree.c (ffffffff81183c7f)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81336a16)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81337bc2)
Location: include/linux/fsnotify_backend.h:462
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
</details>
</li>
</ul>

## Differences
