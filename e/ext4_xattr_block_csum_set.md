# Function: <code>ext4_xattr_block_csum_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff812dd12c)
Location: fs/ext4/xattr.c:150
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8130d5b8)
Location: fs/ext4/xattr.c:149
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81322840)
Location: fs/ext4/xattr.c:148
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff81322840-ffffffff813228e1: ext4_xattr_block_csum_set.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133a4a0)
Location: fs/ext4/xattr.c:162
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8133a4a0-ffffffff8133a4e6: ext4_xattr_block_csum_set.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8135e870)
Location: fs/ext4/xattr.c:163
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8135e870-ffffffff8135e8b8: ext4_xattr_block_csum_set.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138d1c0)
Location: fs/ext4/xattr.c:164
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff8138d1c0-ffffffff8138d207: ext4_xattr_block_csum_set.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a5dd0)
Location: fs/ext4/xattr.c:164
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813a5dd0-ffffffff813a5e17: ext4_xattr_block_csum_set.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813cfe10)
Location: fs/ext4/xattr.c:164
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813cfe10-ffffffff813cfe55: ext4_xattr_block_csum_set.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e94e0)
Location: fs/ext4/xattr.c:164
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813e94e0-ffffffff813e9525: ext4_xattr_block_csum_set.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_xattr_block_csum_set(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81436f70)
Location: fs/ext4/xattr.c:166
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff81436f70-ffffffff81436fb6: ext4_xattr_block_csum_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ext4_xattr_block_csum_set(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8144fa70)
Location: fs/ext4/xattr.c:166
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff8144fa70-ffffffff8144fab6: ext4_xattr_block_csum_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ext4_xattr_block_csum_set(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81455260)
Location: fs/ext4/xattr.c:166
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff81455260-ffffffff814552a6: ext4_xattr_block_csum_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ext4_xattr_block_csum_set(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814a92e0)
Location: fs/ext4/xattr.c:166
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff814a92e0-ffffffff814a9326: ext4_xattr_block_csum_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ext4_xattr_block_csum_set(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81530d50)
Location: fs/ext4/xattr.c:166
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff81530d50-ffffffff81530dba: ext4_xattr_block_csum_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ext4_xattr_block_csum_set(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815cf3a0)
Location: fs/ext4/xattr.c:168
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff815cf3a0-ffffffff815cf40a: ext4_xattr_block_csum_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ext4_xattr_block_csum_set(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81606c80)
Location: fs/ext4/xattr.c:168
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff81606c80-ffffffff81606cea: ext4_xattr_block_csum_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_xattr_block_csum_set(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8163f9c0)
Location: fs/ext4/xattr.c:168
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff8163f9c0-ffffffff8163fa2a: ext4_xattr_block_csum_set (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c23e0)
Location: fs/ext4/xattr.c:164
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffff8000104c23e0-ffff8000104c2474: ext4_xattr_block_csum_set.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ext4_xattr_block_csum_set(struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0686330)
Location: fs/ext4/xattr.c:164
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
c0686330-c06863e8: ext4_xattr_block_csum_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (c0000000005f9340)
Location: fs/ext4/xattr.c:164
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
c0000000005f9340-c0000000005f93b8: ext4_xattr_block_csum_set.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00033d8ec)
Location: fs/ext4/xattr.c:164
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffe00033d8ec-ffffffe00033d956: ext4_xattr_block_csum_set.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e1ac0)
Location: fs/ext4/xattr.c:164
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813e1ac0-ffffffff813e1b05: ext4_xattr_block_csum_set.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d2540)
Location: fs/ext4/xattr.c:164
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813d2540-ffffffff813d2585: ext4_xattr_block_csum_set.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813dee40)
Location: fs/ext4/xattr.c:164
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813dee40-ffffffff813dee85: ext4_xattr_block_csum_set.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f4260)
Location: fs/ext4/xattr.c:164
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
**Symbols:**

```
ffffffff813f4260-ffffffff813f42a5: ext4_xattr_block_csum_set.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
