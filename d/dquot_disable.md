# Function: <code>dquot_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81273110)
Location: fs/quota/dquot.c:2071
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_off
  - fs/quota/dquot.c:dquot_quota_disable
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff81273110-ffffffff81273899: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8129f9c0)
Location: fs/quota/dquot.c:2104
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_disable
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8129f9c0-ffffffff812a015e: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812b4f20)
Location: fs/quota/dquot.c:2093
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_disable
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff812b4f20-ffffffff812b56d1: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812c1840)
Location: fs/quota/dquot.c:2127
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff812c1840-ffffffff812c1f19: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812e5650)
Location: fs/quota/dquot.c:2163
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff812e5650-ffffffff812e5d4e: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81312a90)
Location: fs/quota/dquot.c:2160
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff81312a90-ffffffff81313195: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81329a20)
Location: fs/quota/dquot.c:2160
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff81329a20-ffffffff8132a125: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81351600)
Location: fs/quota/dquot.c:2168
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff81351600-ffffffff81351cf7: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81369980)
Location: fs/quota/dquot.c:2170
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff81369980-ffffffff8136a077: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b1690)
Location: fs/quota/dquot.c:2184
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff813b1690-ffffffff813b1a08: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c2c90)
Location: fs/quota/dquot.c:2185
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff813c2c90-ffffffff813c3008: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c9e30)
Location: fs/quota/dquot.c:2183
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff813c9e30-ffffffff813ca2ad: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8141a7d0)
Location: fs/quota/dquot.c:2188
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff8141a7d0-ffffffff8141ad78: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff814909b0)
Location: fs/quota/dquot.c:2198
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:__ext4_remount
```
**Symbols:**

```
ffffffff814909b0-ffffffff81490f55: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81524560)
Location: fs/quota/dquot.c:2205
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:__ext4_remount
```
**Symbols:**

```
ffffffff81524560-ffffffff81524b05: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8155c980)
Location: fs/quota/dquot.c:2263
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:__ext4_remount
```
**Symbols:**

```
ffffffff8155c980-ffffffff8155cf89: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81593150)
Location: fs/quota/dquot.c:2217
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:dquot_load_quota_sb
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:__ext4_remount
```
**Symbols:**

```
ffffffff81593150-ffffffff81593668: dquot_disable (STB_GLOBAL)
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
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffff800010431c50)
Location: fs/quota/dquot.c:2170
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffff800010431c50-ffff8000104324d0: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c05f9c6c)
Location: fs/quota/dquot.c:2170
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
c05f9c6c-c05fa464: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c000000000542e00)
Location: fs/quota/dquot.c:2170
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
c000000000542e00-c00000000054383c: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffe0002cdf9a)
Location: fs/quota/dquot.c:2170
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffe0002cdf9a-ffffffe0002ce716: dquot_disable (STB_GLOBAL)
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
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81361f60)
Location: fs/quota/dquot.c:2170
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff81361f60-ffffffff81362657: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81352c00)
Location: fs/quota/dquot.c:2170
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff81352c00-ffffffff813532f7: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135fa30)
Location: fs/quota/dquot.c:2170
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff8135fa30-ffffffff81360127: dquot_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dquot_disable(struct super_block *sb, int type, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81372500)
Location: fs/quota/dquot.c:2170
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_enable
  - fs/quota/dquot.c:vfs_load_quota_inode
  - fs/quota/dquot.c:dquot_quota_off
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff81372500-ffffffff81372bdc: dquot_disable (STB_GLOBAL)
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
