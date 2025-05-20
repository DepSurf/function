# Function: <code>ext4_get_encryption_info</code>

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
In fs/ext4/dir.c (ffffffff812909a6)
Location: fs/ext4/ext4.h:2305
Inline: True
```
```
In fs/ext4/file.c (ffffffff81291a32)
Location: fs/ext4/ext4.h:2305
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_open
```
```
In fs/ext4/ialloc.c (ffffffff812944c8)
Location: fs/ext4/ext4.h:2305
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/namei.c (ffffffff812a28cd)
Location: fs/ext4/ext4.h:2305
Inline: True
Inline callers:
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_symlink
```
```
In fs/ext4/symlink.c (ffffffff812be598)
Location: fs/ext4/ext4.h:2305
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_follow_link
```
```
In fs/ext4/crypto_policy.c (ffffffff812e4b88)
Location: fs/ext4/ext4.h:2305
Inline: True
Inline callers:
  - fs/ext4/crypto_policy.c:ext4_is_child_context_consistent_with_parent
  - fs/ext4/crypto_policy.c:ext4_is_child_context_consistent_with_parent
  - fs/ext4/crypto_policy.c:ext4_inherit_context
  - fs/ext4/crypto_policy.c:ext4_inherit_context
```
```
In fs/ext4/crypto_fname.c (ffffffff812e684f)
Location: fs/ext4/ext4.h:2305
Inline: True
Inline callers:
  - fs/ext4/crypto_fname.c:ext4_fname_setup_filename
```
</details>
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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
