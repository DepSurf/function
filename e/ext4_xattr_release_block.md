# Function: <code>ext4_xattr_release_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff812dd060)
Location: fs/ext4/xattr.c:542
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
```
**Symbols:**

```
ffffffff812dd060-ffffffff812dd36e: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8130cb30)
Location: fs/ext4/xattr.c:567
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8130cb30-ffffffff8130ce5d: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81322b20)
Location: fs/ext4/xattr.c:572
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81322b20-ffffffff81322d39: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133ade0)
Location: fs/ext4/xattr.c:1196
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8133ade0-ffffffff8133b034: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8135efe0)
Location: fs/ext4/xattr.c:1217
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8135efe0-ffffffff8135f234: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138d800)
Location: fs/ext4/xattr.c:1245
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8138d800-ffffffff8138da45: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a7370)
Location: fs/ext4/xattr.c:1237
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813a7370-ffffffff813a75b6: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d05b0)
Location: fs/ext4/xattr.c:1238
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813d05b0-ffffffff813d07fd: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e9c80)
Location: fs/ext4/xattr.c:1238
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813e9c80-ffffffff813e9ecd: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81437720)
Location: fs/ext4/xattr.c:1220
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81437720-ffffffff81437969: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81450250)
Location: fs/ext4/xattr.c:1223
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81450250-ffffffff81450499: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81455b20)
Location: fs/ext4/xattr.c:1223
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81455b20-ffffffff81455d65: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:1225
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff814aa560-ffffffff814aa7bd: ext4_xattr_release_block (STB_LOCAL)
ffffffff81cce13c-ffffffff81cce17d: ext4_xattr_release_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:1224
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff815316d0-ffffffff815319da: ext4_xattr_release_block (STB_LOCAL)
ffffffff81e810e5-ffffffff81e81126: ext4_xattr_release_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:1240
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff815cfc30-ffffffff815cff41: ext4_xattr_release_block (STB_LOCAL)
ffffffff82070fb1-ffffffff82070ff2: ext4_xattr_release_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:1268
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81608530-ffffffff81608841: ext4_xattr_release_block (STB_LOCAL)
ffffffff820f0d15-ffffffff820f0d56: ext4_xattr_release_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:1268
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81641270-ffffffff81641581: ext4_xattr_release_block (STB_LOCAL)
ffffffff821cdecc-ffffffff821cdf0d: ext4_xattr_release_block.cold (STB_LOCAL)
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
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c3ff0)
Location: fs/ext4/xattr.c:1238
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffff8000104c3ff0-ffff8000104c42d8: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0686c50)
Location: fs/ext4/xattr.c:1238
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
c0686c50-c0686f5c: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005f9ef0)
Location: fs/ext4/xattr.c:1238
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
c0000000005f9ef0-c0000000005fa280: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00033dd02)
Location: fs/ext4/xattr.c:1238
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffe00033dd02-ffffffe00033df20: ext4_xattr_release_block (STB_LOCAL)
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
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e2260)
Location: fs/ext4/xattr.c:1238
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813e2260-ffffffff813e24ad: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d2ce0)
Location: fs/ext4/xattr.c:1238
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813d2ce0-ffffffff813d2f2d: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813df5e0)
Location: fs/ext4/xattr.c:1238
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813df5e0-ffffffff813df82d: ext4_xattr_release_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_xattr_release_block(handle_t *handle, struct inode *inode, struct buffer_head *bh, struct ext4_xattr_inode_array **ea_inode_array, int extra_credits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f4a00)
Location: fs/ext4/xattr.c:1238
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_delete_inode
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff813f4a00-ffffffff813f4c4b: ext4_xattr_release_block (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ext4_xattr_inode_array **ea_inode_array</code>
</li>
<li>
<b>Param added. </b>
<code>int extra_credits</code>
</li>
</ul>
</details>
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
