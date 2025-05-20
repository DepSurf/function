# Function: <code>ext4_handle_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff812b8340)
Location: fs/ext4/super.c:375
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_error
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_grp_locked_error
Direct callers:
  - fs/ext4/super.c:__ext4_error
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_grp_locked_error
```
**Symbols:**

```
ffffffff812b8340-ffffffff812b83db: ext4_handle_error.part.191 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff812e9602)
Location: fs/ext4/super.c:404
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff812e7040-ffffffff812e70db: ext4_handle_error.part.191 (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff812ff372)
Location: fs/ext4/super.c:406
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff812fcc20-ffffffff812fccbb: ext4_handle_error.part.193 (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff81334171)
Location: fs/ext4/super.c:411
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff81331880-ffffffff8133191b: ext4_handle_error.part.199 (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff8135868e)
Location: fs/ext4/super.c:411
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff81355d30-ffffffff81355dcb: ext4_handle_error.part.200 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:411
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff81384110-ffffffff813841b0: ext4_handle_error (STB_LOCAL)
ffffffff8138b8a3-ffffffff8138b8b6: ext4_handle_error.cold.134 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff8139cc41)
Location: fs/ext4/super.c:453
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff8139cbf0-ffffffff8139cc90: ext4_handle_error (STB_LOCAL)
ffffffff813a4403-ffffffff813a4416: ext4_handle_error.cold.138 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813c6e61)
Location: fs/ext4/super.c:460
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff813c6e10-ffffffff813c6eb3: ext4_handle_error (STB_LOCAL)
ffffffff813ce624-ffffffff813ce637: ext4_handle_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813e0221)
Location: fs/ext4/super.c:455
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff813e01d0-ffffffff813e0273: ext4_handle_error (STB_LOCAL)
ffffffff813e7ce3-ffffffff813e7cf6: ext4_handle_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:496
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff8142c9f0-ffffffff8142ca82: ext4_handle_error (STB_LOCAL)
ffffffff814347a3-ffffffff814347b6: ext4_handle_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb, bool force_ro, int error, __u32 ino, __u64 block, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:639
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff81445730-ffffffff8144589b: ext4_handle_error (STB_LOCAL)
ffffffff81bec636-ffffffff81bec649: ext4_handle_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb, bool force_ro, int error, __u32 ino, __u64 block, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:639
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff8144afc0-ffffffff8144b16d: ext4_handle_error (STB_LOCAL)
ffffffff81bde6e8-ffffffff81bde6fb: ext4_handle_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb, bool force_ro, int error, __u32 ino, __u64 block, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:636
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff8149ef00-ffffffff8149f0ec: ext4_handle_error (STB_LOCAL)
ffffffff81ccd757-ffffffff81ccd76a: ext4_handle_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb, bool force_ro, int error, __u32 ino, __u64 block, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:655
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff815256b0-ffffffff815258bc: ext4_handle_error (STB_LOCAL)
ffffffff81e805c3-ffffffff81e8064a: ext4_handle_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb, bool force_ro, int error, __u32 ino, __u64 block, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:648
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff815c2d30-ffffffff815c2f52: ext4_handle_error (STB_LOCAL)
ffffffff82070967-ffffffff820709db: ext4_handle_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb, bool force_ro, int error, __u32 ino, __u64 block, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:648
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff815fa490-ffffffff815fa6af: ext4_handle_error (STB_LOCAL)
ffffffff820f05f0-ffffffff820f0664: ext4_handle_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb, bool force_ro, int error, __u32 ino, __u64 block, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:708
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff81633070-ffffffff8163328f: ext4_handle_error (STB_LOCAL)
ffffffff821cd7c3-ffffffff821cd837: ext4_handle_error.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b92d0)
Location: fs/ext4/super.c:455
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffff8000104b92d0-ffff8000104b93ac: ext4_handle_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067c910)
Location: fs/ext4/super.c:455
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
c067c910-c067ca2c: ext4_handle_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005ee510)
Location: fs/ext4/super.c:455
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
c0000000005ee510-c0000000005ee674: ext4_handle_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000335b28)
Location: fs/ext4/super.c:455
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffe000335b28-ffffffe000335bf4: ext4_handle_error (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8801)
Location: fs/ext4/super.c:455
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff813d87b0-ffffffff813d8853: ext4_handle_error (STB_LOCAL)
ffffffff813e02c3-ffffffff813e02d6: ext4_handle_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813c9281)
Location: fs/ext4/super.c:455
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff813c9230-ffffffff813c92d3: ext4_handle_error (STB_LOCAL)
ffffffff813d0d43-ffffffff813d0d56: ext4_handle_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813d5c91)
Location: fs/ext4/super.c:455
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff813d5c40-ffffffff813d5ce3: ext4_handle_error (STB_LOCAL)
ffffffff813dd643-ffffffff813dd656: ext4_handle_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_handle_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813eaf01)
Location: fs/ext4/super.c:455
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff813eaeb0-ffffffff813eaf53: ext4_handle_error (STB_LOCAL)
ffffffff813f2a73-ffffffff813f2a86: ext4_handle_error.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool force_ro</code>
</li>
<li>
<b>Param added. </b>
<code>int error</code>
</li>
<li>
<b>Param added. </b>
<code>__u32 ino</code>
</li>
<li>
<b>Param added. </b>
<code>__u64 block</code>
</li>
<li>
<b>Param added. </b>
<code>const char *func</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int line</code>
</li>
</ul>
</details>
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
