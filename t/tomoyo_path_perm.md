# Function: <code>tomoyo_path_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8136f640)
Location: security/tomoyo/file.c:785
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
```
**Symbols:**

```
ffffffff8136f640-ffffffff8136f808: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813a5960)
Location: security/tomoyo/file.c:785
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff813a5960-ffffffff813a5b44: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813bc4e0)
Location: security/tomoyo/file.c:785
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff813bc4e0-ffffffff813bc6c4: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813d2e10)
Location: security/tomoyo/file.c:785
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff813d2e10-ffffffff813d3007: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff813f9320)
Location: security/tomoyo/file.c:786
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff813f9320-ffffffff813f9517: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8142a300)
Location: security/tomoyo/file.c:786
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff8142a300-ffffffff8142a4f3: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81446bd0)
Location: security/tomoyo/file.c:786
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff81446bd0-ffffffff81446dc3: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff814747f0)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff814747f0-ffffffff814749e4: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8148e590)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff8148e590-ffffffff8148e784: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff814e5820)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff814e5820-ffffffff814e5a14: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81502c20)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff81502c20-ffffffff81502e14: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff815097f0)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff815097f0-ffffffff815099e4: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81566be0)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff81566be0-ffffffff81566ddd: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816026b0)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff816026b0-ffffffff816028f8: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816b3810)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_file_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff816b3810-ffffffff816b3a58: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff816ec1d0)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_file_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff816ec1d0-ffffffff816ec411: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81728fa0)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_file_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff81728fa0-ffffffff817291e1: tomoyo_path_perm (STB_GLOBAL)
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
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffff800010581f30)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffff800010581f30-ffff8000105820fc: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (c0733e6c)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
c0733e6c-c0734048: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (c0000000006f0700)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
c0000000006f0700-c0000000006f0948: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffe0003d2562)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffe0003d2562-ffffffe0003d26cc: tomoyo_path_perm (STB_GLOBAL)
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
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81486b70)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff81486b70-ffffffff81486d64: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81477590)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff81477590-ffffffff81477784: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff81482c10)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff81482c10-ffffffff81482e04: tomoyo_path_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tomoyo_path_perm(const u8 operation, const struct path *path, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/file.c (ffffffff8149a7a0)
Location: security/tomoyo/file.c:803
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_sb_umount
  - security/tomoyo/tomoyo.c:tomoyo_path_chroot
  - security/tomoyo/tomoyo.c:tomoyo_path_symlink
  - security/tomoyo/tomoyo.c:tomoyo_path_rmdir
  - security/tomoyo/tomoyo.c:tomoyo_path_unlink
  - security/tomoyo/tomoyo.c:tomoyo_path_truncate
  - security/tomoyo/tomoyo.c:tomoyo_inode_getattr
```
**Symbols:**

```
ffffffff8149a7a0-ffffffff8149a994: tomoyo_path_perm (STB_GLOBAL)
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
