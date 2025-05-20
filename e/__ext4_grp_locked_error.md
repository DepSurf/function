# Function: <code>__ext4_grp_locked_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ba620)
Location: fs/ext4/super.c:660
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
```
**Symbols:**

```
ffffffff812ba620-ffffffff812ba85f: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e9550)
Location: fs/ext4/super.c:689
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff812e9550-ffffffff812e978b: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ff2c0)
Location: fs/ext4/super.c:692
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff812ff2c0-ffffffff812ff4fb: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81334090)
Location: fs/ext4/super.c:712
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff81334090-ffffffff813342e1: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813585a0)
Location: fs/ext4/super.c:711
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff813585a0-ffffffff813587fe: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:717
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff8138bc7f-ffffffff8138bd13: __ext4_grp_locked_error.cold.143 (STB_LOCAL)
ffffffff81386ea0-ffffffff813870a1: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:759
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff813a47fe-ffffffff813a4892: __ext4_grp_locked_error.cold.147 (STB_LOCAL)
ffffffff8139f9b0-ffffffff8139fbb1: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:770
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff813ce9dc-ffffffff813cea71: __ext4_grp_locked_error.cold (STB_LOCAL)
ffffffff813c9cd0-ffffffff813c9eab: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:765
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff813e809b-ffffffff813e8130: __ext4_grp_locked_error.cold (STB_LOCAL)
ffffffff813e2fd0-ffffffff813e31ab: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:796
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff81434c44-ffffffff81434cd4: __ext4_grp_locked_error.cold (STB_LOCAL)
ffffffff81430580-ffffffff81430742: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:952
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff81beca3e-ffffffff81becad7: __ext4_grp_locked_error.cold (STB_LOCAL)
ffffffff814492d0-ffffffff814494d1: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:961
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff81bdeaee-ffffffff81bdeb87: __ext4_grp_locked_error.cold (STB_LOCAL)
ffffffff8144ec50-ffffffff8144ee50: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:960
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff81ccdc6d-ffffffff81ccdd06: __ext4_grp_locked_error.cold (STB_LOCAL)
ffffffff814a2790-ffffffff814a298d: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:992
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff81e80bbd-ffffffff81e80c9c: __ext4_grp_locked_error.cold (STB_LOCAL)
ffffffff81529b10-ffffffff81529db1: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:985
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff82070b98-ffffffff82070bf6: __ext4_grp_locked_error.cold (STB_LOCAL)
ffffffff815c8390-ffffffff815c86e3: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:985
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff820f0998-ffffffff820f09f6: __ext4_grp_locked_error.cold (STB_LOCAL)
ffffffff816001a0-ffffffff816004f0: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:1054
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_find_extent
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff821cdb4f-ffffffff821cdbad: __ext4_grp_locked_error.cold (STB_LOCAL)
ffffffff81638ef0-ffffffff81639240: __ext4_grp_locked_error (STB_GLOBAL)
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
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104bc3d0)
Location: fs/ext4/super.c:765
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffff8000104bc3d0-ffff8000104bc708: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067fa8c)
Location: fs/ext4/super.c:765
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
c067fa8c-c067fd84: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f2150)
Location: fs/ext4/super.c:765
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
c0000000005f2150-c0000000005f2488: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe0003381fe)
Location: fs/ext4/super.c:765
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffe0003381fe-ffffffe00033844a: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:765
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff813e067b-ffffffff813e0710: __ext4_grp_locked_error.cold (STB_LOCAL)
ffffffff813db5b0-ffffffff813db78b: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:765
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff813d10fb-ffffffff813d1190: __ext4_grp_locked_error.cold (STB_LOCAL)
ffffffff813cc030-ffffffff813cc20b: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:765
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff813dd9fb-ffffffff813dda90: __ext4_grp_locked_error.cold (STB_LOCAL)
ffffffff813d8a50-ffffffff813d8c2b: __ext4_grp_locked_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __ext4_grp_locked_error(const char *function, unsigned int line, struct super_block *sb, ext4_group_t grp, long unsigned int ino, ext4_fsblk_t block, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:765
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_free_metadata
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
**Symbols:**

```
ffffffff813f2e27-ffffffff813f2ebc: __ext4_grp_locked_error.cold (STB_LOCAL)
ffffffff813edcf0-ffffffff813edee2: __ext4_grp_locked_error (STB_GLOBAL)
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
