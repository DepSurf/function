# Function: <code>fat_truncate_atime</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 fat_truncate_atime(const struct msdos_sb_info *sbi, const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff815621ab)
Location: fs/fat/misc.c:287
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
Direct callers:
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff81562650-ffffffff815626c0: fat_truncate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 fat_truncate_atime(const struct msdos_sb_info *sbi, const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8160491b)
Location: fs/fat/misc.c:287
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
Direct callers:
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff81605010-ffffffff81605080: fat_truncate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 fat_truncate_atime(const struct msdos_sb_info *sbi, const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff8163c82b)
Location: fs/fat/misc.c:287
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
Direct callers:
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff8163cf20-ffffffff8163cf90: fat_truncate_atime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 fat_truncate_atime(const struct msdos_sb_info *sbi, const struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/misc.c (ffffffff81675dbb)
Location: fs/fat/misc.c:287
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_truncate_time
Direct callers:
  - fs/fat/inode.c:fat_fill_inode
```
**Symbols:**

```
ffffffff81676490-ffffffff81676500: fat_truncate_atime (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
