# Function: <code>ext4_clear_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff812d88a0)
Location: fs/ext4/indirect.c:934
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff812d88a0-ffffffff812d8b0f: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81308640)
Location: fs/ext4/indirect.c:822
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff81308640-ffffffff813088a6: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8131e630)
Location: fs/ext4/indirect.c:822
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff8131e630-ffffffff8131e8b4: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff812f7150)
Location: fs/ext4/indirect.c:822
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff812f7150-ffffffff812f7494: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8131b790)
Location: fs/ext4/indirect.c:823
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff8131b790-ffffffff8131bad4: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813496c0)
Location: fs/ext4/indirect.c:829
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff813496c0-ffffffff813499d7: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81361880)
Location: fs/ext4/indirect.c:829
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff81361880-ffffffff81361b97: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8138ac40)
Location: fs/ext4/indirect.c:823
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff8138ac40-ffffffff8138af90: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813a3690)
Location: fs/ext4/indirect.c:823
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff813a3690-ffffffff813a39e0: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813efa80)
Location: fs/ext4/indirect.c:845
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff813efa80-ffffffff813efc1e: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff814021e0)
Location: fs/ext4/indirect.c:846
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff814021e0-ffffffff8140237e: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff814085e0)
Location: fs/ext4/indirect.c:846
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff814085e0-ffffffff8140877e: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8145b040)
Location: fs/ext4/indirect.c:849
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff8145b040-ffffffff8145b1de: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff814d8dd0)
Location: fs/ext4/indirect.c:849
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff814d8dd0-ffffffff814d8f9b: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81571bf0)
Location: fs/ext4/indirect.c:856
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff81571bf0-ffffffff81571dbb: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815a9980)
Location: fs/ext4/indirect.c:864
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff815a9980-ffffffff815a9b4b: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815e2720)
Location: fs/ext4/indirect.c:864
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff815e2720-ffffffff815e28eb: ext4_clear_blocks (STB_LOCAL)
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
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffff800010476d18)
Location: fs/ext4/indirect.c:823
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffff800010476d18-ffff800010477050: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (c0638838)
Location: fs/ext4/indirect.c:823
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
c0638838-c0638b3c: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (c000000000598cc0)
Location: fs/ext4/indirect.c:823
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
c000000000598cc0-c000000000599140: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffe000302264)
Location: fs/ext4/indirect.c:823
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffe000302264-ffffffe0003024f0: ext4_clear_blocks (STB_LOCAL)
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
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8139bc70)
Location: fs/ext4/indirect.c:823
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff8139bc70-ffffffff8139bfc0: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8138c700)
Location: fs/ext4/indirect.c:823
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff8138c700-ffffffff8138ca50: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813994d0)
Location: fs/ext4/indirect.c:823
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff813994d0-ffffffff81399820: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_clear_blocks(handle_t *handle, struct inode *inode, struct buffer_head *bh, ext4_fsblk_t block_to_free, long unsigned int count, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813ad5c0)
Location: fs/ext4/indirect.c:823
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_data
  - fs/ext4/indirect.c:ext4_free_data
```
**Symbols:**

```
ffffffff813ad5c0-ffffffff813ad910: ext4_clear_blocks (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
