# Function: <code>ext4_xattr_inode_dec_ref_all</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133a670)
Location: fs/ext4/xattr.c:1113
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8133a670-ffffffff8133a907: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8135ea40)
Location: fs/ext4/xattr.c:1132
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8135ea40-ffffffff8135ecff: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138d3b0)
Location: fs/ext4/xattr.c:1160
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8138d3b0-ffffffff8138d672: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a5fc0)
Location: fs/ext4/xattr.c:1152
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813a5fc0-ffffffff813a6282: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d02f0)
Location: fs/ext4/xattr.c:1153
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813d02f0-ffffffff813d05a8: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e99c0)
Location: fs/ext4/xattr.c:1153
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813e99c0-ffffffff813e9c78: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81436fc0)
Location: fs/ext4/xattr.c:1124
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81436fc0-ffffffff814372a2: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8144fac0)
Location: fs/ext4/xattr.c:1127
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8144fac0-ffffffff8144fda2: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814552b0)
Location: fs/ext4/xattr.c:1127
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff814552b0-ffffffff81455593: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814a9330)
Location: fs/ext4/xattr.c:1128
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff814a9330-ffffffff814a961e: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81530dc0)
Location: fs/ext4/xattr.c:1127
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81530dc0-ffffffff815310e1: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815cf420)
Location: fs/ext4/xattr.c:1143
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff815cf420-ffffffff815cf741: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81606d00)
Location: fs/ext4/xattr.c:1171
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81606d00-ffffffff81607021: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8163fa40)
Location: fs/ext4/xattr.c:1171
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8163fa40-ffffffff8163fd61: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c3d40)
Location: fs/ext4/xattr.c:1153
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffff8000104c3d40-ffff8000104c3ff0: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0686978)
Location: fs/ext4/xattr.c:1153
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
c0686978-c0686c50: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005f9ae0)
Location: fs/ext4/xattr.c:1153
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
c0000000005f9ae0-c0000000005f9ee8: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00033dac8)
Location: fs/ext4/xattr.c:1153
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffe00033dac8-ffffffe00033dd02: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e1fa0)
Location: fs/ext4/xattr.c:1153
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813e1fa0-ffffffff813e2258: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d2a20)
Location: fs/ext4/xattr.c:1153
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813d2a20-ffffffff813d2cd8: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813df320)
Location: fs/ext4/xattr.c:1153
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813df320-ffffffff813df5d8: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_xattr_inode_dec_ref_all(handle_t *handle, struct inode *parent, struct buffer_head *bh, struct ext4_xattr_entry *first, bool block_csum, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits, bool skip_quota);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f4740)
Location: fs/ext4/xattr.c:1153
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813f4740-ffffffff813f49f8: ext4_xattr_inode_dec_ref_all (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
