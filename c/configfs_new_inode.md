# Function: <code>configfs_new_inode</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff812de070)
Location: fs/configfs/inode.c:129
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
```
**Symbols:**

```
ffffffff812de070-ffffffff812de144: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813029b0)
Location: fs/configfs/inode.c:129
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
```
**Symbols:**

```
ffffffff813029b0-ffffffff81302a84: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81330910)
Location: fs/configfs/inode.c:129
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff81330910-ffffffff813309d6: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81347d00)
Location: fs/configfs/inode.c:129
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff81347d00-ffffffff81347dc6: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81370180)
Location: fs/configfs/inode.c:115
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff81370180-ffffffff8137025a: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813886b0)
Location: fs/configfs/inode.c:112
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff813886b0-ffffffff8138878a: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813d33f0)
Location: fs/configfs/inode.c:112
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff813d33f0-ffffffff813d34ca: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813e5130)
Location: fs/configfs/inode.c:112
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff813e5130-ffffffff813e520a: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813ebd40)
Location: fs/configfs/inode.c:111
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff813ebd40-ffffffff813ebe1a: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff8143dad0)
Location: fs/configfs/inode.c:105
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff8143dad0-ffffffff8143dbb1: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff814b93a0)
Location: fs/configfs/inode.c:105
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff814b93a0-ffffffff814b9472: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81550af0)
Location: fs/configfs/inode.c:105
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff81550af0-ffffffff81550bc2: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff815887e0)
Location: fs/configfs/inode.c:105
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff815887e0-ffffffff815888af: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff815c13d0)
Location: fs/configfs/inode.c:104
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff815c13d0-ffffffff815c1486: configfs_new_inode (STB_GLOBAL)
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
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffff800010458940)
Location: fs/configfs/inode.c:112
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffff800010458940-ffff800010458a00: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (c061a694)
Location: fs/configfs/inode.c:112
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
```
**Symbols:**

```
c061a694-c061a7a8: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (c000000000573380)
Location: fs/configfs/inode.c:112
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
c000000000573380-c00000000057348c: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffe0002e9998)
Location: fs/configfs/inode.c:112
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
```
**Symbols:**

```
ffffffe0002e9998-ffffffe0002e9a44: configfs_new_inode (STB_GLOBAL)
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
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81380c90)
Location: fs/configfs/inode.c:112
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff81380c90-ffffffff81380d6a: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81371720)
Location: fs/configfs/inode.c:112
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff81371720-ffffffff813717fa: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff8137e760)
Location: fs/configfs/inode.c:112
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff8137e760-ffffffff8137e83a: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *configfs_new_inode(umode_t mode, struct configfs_dirent *sd, struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81392270)
Location: fs/configfs/inode.c:112
Inline: False
Direct callers:
  - fs/configfs/inode.c:configfs_create
  - fs/configfs/mount.c:configfs_fill_super
```
**Symbols:**

```
ffffffff81392270-ffffffff8139234a: configfs_new_inode (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
