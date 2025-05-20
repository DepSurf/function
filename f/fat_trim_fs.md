# Function: <code>fat_trim_fs</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff813c4f80)
Location: fs/fat/fatent.c:701
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff813c4f80-ffffffff813c53f6: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff813ef8d0)
Location: fs/fat/fatent.c:701
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff813ef8d0-ffffffff813efd82: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81409940)
Location: fs/fat/fatent.c:704
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff81409940-ffffffff81409df2: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81457540)
Location: fs/fat/fatent.c:760
Inline: False
Direct callers:
  - fs/fat/file.c:fat_ioctl_fitrim
```
**Symbols:**

```
ffffffff81457540-ffffffff81457a80: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81473900)
Location: fs/fat/fatent.c:760
Inline: False
Direct callers:
  - fs/fat/file.c:fat_ioctl_fitrim
```
**Symbols:**

```
ffffffff81473900-ffffffff81473e40: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81479350)
Location: fs/fat/fatent.c:760
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff81479350-ffffffff8147988c: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:761
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff81ccfc8d-ffffffff81ccfe25: fat_trim_fs.cold (STB_LOCAL)
ffffffff814d0860-ffffffff814d0e65: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:762
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff81e82ece-ffffffff81e83083: fat_trim_fs.cold (STB_LOCAL)
ffffffff8155d3a0-ffffffff8155da1a: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:762
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff8207203b-ffffffff820721f0: fat_trim_fs.cold (STB_LOCAL)
ffffffff815ff3f0-ffffffff815ffa6a: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:762
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff820f1c9e-ffffffff820f1e13: fat_trim_fs.cold (STB_LOCAL)
ffffffff816373d0-ffffffff81637a4a: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:762
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff821cef80-ffffffff821cf0f5: fat_trim_fs.cold (STB_LOCAL)
ffffffff816708c0-ffffffff81670f3a: fat_trim_fs (STB_GLOBAL)
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
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffff8000104e9e30)
Location: fs/fat/fatent.c:704
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffff8000104e9e30-ffff8000104ea210: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (c06a7c14)
Location: fs/fat/fatent.c:704
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
c06a7c14-c06a8198: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (c000000000627ca0)
Location: fs/fat/fatent.c:704
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
c000000000627ca0-c0000000006281f8: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffe00035ae02)
Location: fs/fat/fatent.c:704
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffe00035ae02-ffffffe00035b154: fat_trim_fs (STB_GLOBAL)
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
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81401f20)
Location: fs/fat/fatent.c:704
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff81401f20-ffffffff814023d2: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff813f29a0)
Location: fs/fat/fatent.c:704
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff813f29a0-ffffffff813f2e52: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff813ff2a0)
Location: fs/fat/fatent.c:704
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff813ff2a0-ffffffff813ff752: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fat_trim_fs(struct inode *inode, struct fstrim_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81414ed0)
Location: fs/fat/fatent.c:704
Inline: False
Direct callers:
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff81414ed0-ffffffff8141537d: fat_trim_fs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
