# Function: <code>fat_time_unix2fat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff812fe0a0)
Location: fs/fat/misc.c:227
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff812fe0a0-ffffffff812fe1e8: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81332090)
Location: fs/fat/misc.c:227
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81332090-ffffffff813321e7: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81347e30)
Location: fs/fat/misc.c:227
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81347e30-ffffffff81347f87: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8135c840)
Location: fs/fat/misc.c:227
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff8135c840-ffffffff8135c997: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81381540)
Location: fs/fat/misc.c:227
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81381540-ffffffff81381697: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813b0130)
Location: fs/fat/misc.c:227
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff813b0130-ffffffff813b0286: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813c9590)
Location: fs/fat/misc.c:233
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff813c9590-ffffffff813c96e8: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813f4140)
Location: fs/fat/misc.c:234
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff813f4140-ffffffff813f428e: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8140e010)
Location: fs/fat/misc.c:234
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff8140e010-ffffffff8140e15e: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8145bde0)
Location: fs/fat/misc.c:234
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff8145bde0-ffffffff8145bf2e: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81477ce0)
Location: fs/fat/misc.c:234
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff81477ce0-ffffffff81477e2e: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8147d750)
Location: fs/fat/misc.c:234
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff8147d750-ffffffff8147d89e: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff814d4fd0)
Location: fs/fat/misc.c:237
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff814d4fd0-ffffffff814d511e: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81561fc0)
Location: fs/fat/misc.c:243
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff81561fc0-ffffffff81562144: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81604720)
Location: fs/fat/misc.c:243
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff81604720-ffffffff816048a4: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8163c640)
Location: fs/fat/misc.c:243
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff8163c640-ffffffff8163c7c0: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81675bd0)
Location: fs/fat/misc.c:243
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff81675bd0-ffffffff81675d50: fat_time_unix2fat (STB_GLOBAL)
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
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffff8000104eeb20)
Location: fs/fat/misc.c:234
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffff8000104eeb20-ffff8000104eec94: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (c06ac610)
Location: fs/fat/misc.c:234
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
c06ac610-c06ac774: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (c00000000062db60)
Location: fs/fat/misc.c:234
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
c00000000062db60-c00000000062dd3c: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffe00035ec9a)
Location: fs/fat/misc.c:234
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffe00035ec9a-ffffffe00035edd6: fat_time_unix2fat (STB_GLOBAL)
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
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff814065f0)
Location: fs/fat/misc.c:234
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff814065f0-ffffffff8140673e: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff813f7070)
Location: fs/fat/misc.c:234
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff813f7070-ffffffff813f71be: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81403970)
Location: fs/fat/misc.c:234
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff81403970-ffffffff81403abe: fat_time_unix2fat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fat_time_unix2fat(struct msdos_sb_info *sbi, struct timespec64 *ts, __le16 *time, __le16 *date, u8 *time_cs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff814195e0)
Location: fs/fat/misc.c:234
Inline: False
Direct callers:
  - fs/fat/dir.c:fat_alloc_new_dir
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/inode.c:__fat_write_inode
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff814195e0-ffffffff8141972e: fat_time_unix2fat (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *ts</code> ➡️ <code>struct timespec64 *ts</code>
</li>
</ul>
</details>
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
