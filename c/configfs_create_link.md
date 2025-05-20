# Function: <code>configfs_create_link</code>

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
int configfs_create_link(struct configfs_symlink *sl, struct dentry *parent, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812e0f30)
Location: fs/configfs/dir.c:350
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff812e0f30-ffffffff812e1000: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_symlink *sl, struct dentry *parent, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813058c0)
Location: fs/configfs/dir.c:350
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff813058c0-ffffffff81305990: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_symlink *sl, struct dentry *parent, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81333880)
Location: fs/configfs/dir.c:350
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff81333880-ffffffff81333950: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_symlink *sl, struct dentry *parent, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8134ac10)
Location: fs/configfs/dir.c:350
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff8134ac10-ffffffff8134ace0: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int configfs_create_link(struct configfs_symlink *sl, struct dentry *parent, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:365
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff81373683-ffffffff81373696: configfs_create_link.cold (STB_LOCAL)
ffffffff81373500-ffffffff813735dc: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8138b8e0)
Location: fs/configfs/dir.c:354
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff8138b8e0-ffffffff8138b98f: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813d6ba0)
Location: fs/configfs/dir.c:354
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff813d6ba0-ffffffff813d6c4f: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813e8870)
Location: fs/configfs/dir.c:355
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff813e8870-ffffffff813e891f: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813ef430)
Location: fs/configfs/dir.c:353
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff813ef430-ffffffff813ef4df: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81441320)
Location: fs/configfs/dir.c:361
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81441320-ffffffff814413cf: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff814bced0)
Location: fs/configfs/dir.c:361
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff814bced0-ffffffff814bcfa6: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81554a80)
Location: fs/configfs/dir.c:362
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81554a80-ffffffff81554b9b: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8158c800)
Location: fs/configfs/dir.c:362
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff8158c800-ffffffff8158c91b: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815c5500)
Location: fs/configfs/dir.c:362
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff815c5500-ffffffff815c5624: configfs_create_link (STB_GLOBAL)
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
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffff80001045cad8)
Location: fs/configfs/dir.c:354
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffff80001045cad8-ffff80001045cb98: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061dd54)
Location: fs/configfs/dir.c:354
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
c061dd54-c061de0c: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c0000000005789c0)
Location: fs/configfs/dir.c:354
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
c0000000005789c0-c000000000578ad0: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002ed058)
Location: fs/configfs/dir.c:354
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffe0002ed058-ffffffe0002ed102: configfs_create_link (STB_GLOBAL)
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
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81383ec0)
Location: fs/configfs/dir.c:354
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81383ec0-ffffffff81383f6f: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81374950)
Location: fs/configfs/dir.c:354
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81374950-ffffffff813749ff: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81381990)
Location: fs/configfs/dir.c:354
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81381990-ffffffff81381a3f: configfs_create_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int configfs_create_link(struct configfs_dirent *target, struct dentry *parent, struct dentry *dentry, char *body);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813954c0)
Location: fs/configfs/dir.c:354
Inline: False
Direct callers:
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff813954c0-ffffffff8139556f: configfs_create_link (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct configfs_dirent *target</code>
</li>
<li>
<b>Param added. </b>
<code>char *body</code>
</li>
<li>
<b>Param removed. </b>
<code>struct configfs_symlink *sl</code>
</li>
</ul>
</details>
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
