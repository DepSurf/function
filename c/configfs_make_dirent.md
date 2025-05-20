# Function: <code>configfs_make_dirent</code>

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
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812e0270)
Location: fs/configfs/dir.c:225
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff812e0270-ffffffff812e02c5: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81304bf0)
Location: fs/configfs/dir.c:225
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81304bf0-ffffffff81304c45: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81332d80)
Location: fs/configfs/dir.c:225
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81332d80-ffffffff81332dd5: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8134a170)
Location: fs/configfs/dir.c:225
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff8134a170-ffffffff8134a1c5: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:238
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff8137365d-ffffffff81373670: configfs_make_dirent.cold (STB_LOCAL)
ffffffff81372900-ffffffff8137295d: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8138ad40)
Location: fs/configfs/dir.c:236
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff8138ad40-ffffffff8138ad9d: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813d5e10)
Location: fs/configfs/dir.c:236
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff813d5e10-ffffffff813d5e6d: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813e7ae0)
Location: fs/configfs/dir.c:236
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff813e7ae0-ffffffff813e7b3d: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813ee700)
Location: fs/configfs/dir.c:234
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff813ee700-ffffffff813ee75d: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81440630)
Location: fs/configfs/dir.c:242
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81440630-ffffffff8144068d: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff814bc160)
Location: fs/configfs/dir.c:242
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff814bc160-ffffffff814bc1c5: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81553c30)
Location: fs/configfs/dir.c:242
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81553c30-ffffffff81553c95: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8158b9c0)
Location: fs/configfs/dir.c:242
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff8158b9c0-ffffffff8158ba25: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815c46f0)
Location: fs/configfs/dir.c:242
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff815c46f0-ffffffff815c4758: configfs_make_dirent (STB_GLOBAL)
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
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffff80001045bce0)
Location: fs/configfs/dir.c:236
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffff80001045bce0-ffff80001045bd98: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061cfc8)
Location: fs/configfs/dir.c:236
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
c061cfc8-c061d05c: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c0000000005771b0)
Location: fs/configfs/dir.c:236
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
c0000000005771b0-c00000000057727c: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002ec1c6)
Location: fs/configfs/dir.c:236
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffe0002ec1c6-ffffffe0002ec23e: configfs_make_dirent (STB_GLOBAL)
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
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81383320)
Location: fs/configfs/dir.c:236
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81383320-ffffffff8138337d: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81373db0)
Location: fs/configfs/dir.c:236
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81373db0-ffffffff81373e0d: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81380df0)
Location: fs/configfs/dir.c:236
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81380df0-ffffffff81380e4d: configfs_make_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int configfs_make_dirent(struct configfs_dirent *parent_sd, struct dentry *dentry, void *element, umode_t mode, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813948b0)
Location: fs/configfs/dir.c:236
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_create_bin_file
  - fs/configfs/file.c:configfs_create_file
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff813948b0-ffffffff8139490d: configfs_make_dirent (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct configfs_fragment *frag</code>
</li>
</ul>
</details>
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
