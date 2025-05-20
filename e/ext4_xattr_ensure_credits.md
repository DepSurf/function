# Function: <code>ext4_xattr_ensure_credits</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ensure_credits(handle_t *handle, struct inode *inode, int credits, struct buffer_head *bh, bool dirty, bool block_csum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133a4f0)
Location: fs/ext4/xattr.c:930
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff8133a4f0-ffffffff8133a66c: ext4_xattr_ensure_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ensure_credits(handle_t *handle, struct inode *inode, int credits, struct buffer_head *bh, bool dirty, bool block_csum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8135e8c0)
Location: fs/ext4/xattr.c:945
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff8135e8c0-ffffffff8135ea3c: ext4_xattr_ensure_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ensure_credits(handle_t *handle, struct inode *inode, int credits, struct buffer_head *bh, bool dirty, bool block_csum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138d210)
Location: fs/ext4/xattr.c:973
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff8138d210-ffffffff8138d3a7: ext4_xattr_ensure_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ensure_credits(handle_t *handle, struct inode *inode, int credits, struct buffer_head *bh, bool dirty, bool block_csum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a5e20)
Location: fs/ext4/xattr.c:969
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff813a5e20-ffffffff813a5fb7: ext4_xattr_ensure_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ensure_credits(handle_t *handle, struct inode *inode, int credits, struct buffer_head *bh, bool dirty, bool block_csum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813cfe60)
Location: fs/ext4/xattr.c:970
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff813cfe60-ffffffff813d000d: ext4_xattr_ensure_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ensure_credits(handle_t *handle, struct inode *inode, int credits, struct buffer_head *bh, bool dirty, bool block_csum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e9530)
Location: fs/ext4/xattr.c:970
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff813e9530-ffffffff813e96dd: ext4_xattr_ensure_credits (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ensure_credits(handle_t *handle, struct inode *inode, int credits, struct buffer_head *bh, bool dirty, bool block_csum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c2478)
Location: fs/ext4/xattr.c:970
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffff8000104c2478-ffff8000104c2638: ext4_xattr_ensure_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ensure_credits(handle_t *handle, struct inode *inode, int credits, struct buffer_head *bh, bool dirty, bool block_csum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c06863e8)
Location: fs/ext4/xattr.c:970
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
c06863e8-c0686570: ext4_xattr_ensure_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ensure_credits(handle_t *handle, struct inode *inode, int credits, struct buffer_head *bh, bool dirty, bool block_csum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005f93c0)
Location: fs/ext4/xattr.c:970
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
c0000000005f93c0-c0000000005f9644: ext4_xattr_ensure_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ensure_credits(handle_t *handle, struct inode *inode, int credits, struct buffer_head *bh, bool dirty, bool block_csum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00033d956)
Location: fs/ext4/xattr.c:970
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffe00033d956-ffffffe00033dac8: ext4_xattr_ensure_credits (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ensure_credits(handle_t *handle, struct inode *inode, int credits, struct buffer_head *bh, bool dirty, bool block_csum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e1b10)
Location: fs/ext4/xattr.c:970
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff813e1b10-ffffffff813e1cbd: ext4_xattr_ensure_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ensure_credits(handle_t *handle, struct inode *inode, int credits, struct buffer_head *bh, bool dirty, bool block_csum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d2590)
Location: fs/ext4/xattr.c:970
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff813d2590-ffffffff813d273d: ext4_xattr_ensure_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ensure_credits(handle_t *handle, struct inode *inode, int credits, struct buffer_head *bh, bool dirty, bool block_csum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813dee90)
Location: fs/ext4/xattr.c:970
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff813dee90-ffffffff813df03d: ext4_xattr_ensure_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_ensure_credits(handle_t *handle, struct inode *inode, int credits, struct buffer_head *bh, bool dirty, bool block_csum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f42b0)
Location: fs/ext4/xattr.c:970
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff813f42b0-ffffffff813f445d: ext4_xattr_ensure_credits (STB_LOCAL)
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
