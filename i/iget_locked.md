# Function: <code>iget_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81228530)
Location: fs/inode.c:1081
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff81228530-ffffffff812286be: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81250c60)
Location: fs/inode.c:1090
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff81250c60-ffffffff81250deb: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81263d40)
Location: fs/inode.c:1100
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff81263d40-ffffffff81263ee6: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81271700)
Location: fs/inode.c:1101
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff81271700-ffffffff812718a6: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81294020)
Location: fs/inode.c:1101
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff81294020-ffffffff812941c6: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ba4e0)
Location: fs/inode.c:1122
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff812ba4e0-ffffffff812ba686: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cf810)
Location: fs/inode.c:1149
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff812cf810-ffffffff812cf9c8: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ec760)
Location: fs/inode.c:1162
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff812ec760-ffffffff812ec920: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fe2b0)
Location: fs/inode.c:1173
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff812fe2b0-ffffffff812fe470: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81336ee0)
Location: fs/inode.c:1174
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff81336ee0-ffffffff81337105: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81342820)
Location: fs/inode.c:1173
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff81342820-ffffffff81342a45: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81348c20)
Location: fs/inode.c:1180
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff81348c20-ffffffff81348ddd: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1184
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff81cc3d24-ffffffff81cc3d48: iget_locked.cold (STB_LOCAL)
ffffffff813968d0-ffffffff81396a96: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1265
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff81e765bb-ffffffff81e765df: iget_locked.cold (STB_LOCAL)
ffffffff81418b90-ffffffff81418d9b: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1267
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff82068b2a-ffffffff82068b4e: iget_locked.cold (STB_LOCAL)
ffffffff814a44c0-ffffffff814a46cd: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1311
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff820e8468-ffffffff820e848c: iget_locked.cold (STB_LOCAL)
ffffffff814d9650-ffffffff814d985d: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1259
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff821c51c2-ffffffff821c51e6: iget_locked.cold (STB_LOCAL)
ffffffff8150be00-ffffffff8150c008: iget_locked (STB_GLOBAL)
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
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103aec60)
Location: fs/inode.c:1173
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffff8000103aec60-ffff8000103aef18: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058eb7c)
Location: fs/inode.c:1173
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
c058eb7c-c058ed7c: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004aa3d0)
Location: fs/inode.c:1173
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
c0000000004aa3d0-c0000000004aa79c: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000273a64)
Location: fs/inode.c:1173
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffe000273a64-ffffffe000273cb6: iget_locked (STB_GLOBAL)
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
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f6890)
Location: fs/inode.c:1173
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff812f6890-ffffffff812f6a50: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e74b0)
Location: fs/inode.c:1173
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff812e74b0-ffffffff812e7670: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f46a0)
Location: fs/inode.c:1173
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff812f46a0-ffffffff812f4860: iget_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *iget_locked(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813055e0)
Location: fs/inode.c:1173
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_get_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/squashfs/inode.c:squashfs_iget
```
**Symbols:**

```
ffffffff813055e0-ffffffff81305786: iget_locked (STB_GLOBAL)
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
