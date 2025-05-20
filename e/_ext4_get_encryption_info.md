# Function: <code>_ext4_get_encryption_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _ext4_get_encryption_info(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto_key.c (ffffffff812e59c0)
Location: fs/ext4/crypto_key.c:114
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_symlink
  - fs/ext4/symlink.c:ext4_encrypted_follow_link
  - fs/ext4/crypto_policy.c:ext4_is_child_context_consistent_with_parent
  - fs/ext4/crypto_policy.c:ext4_is_child_context_consistent_with_parent
  - fs/ext4/crypto_policy.c:ext4_inherit_context
  - fs/ext4/crypto_policy.c:ext4_inherit_context
  - fs/ext4/crypto_fname.c:ext4_fname_setup_filename
```
**Symbols:**

```
ffffffff812e59c0-ffffffff812e5ed8: _ext4_get_encryption_info (STB_GLOBAL)
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
<b>Regular</b>
<ul>
</ul>
