# Function: <code>vfs_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfs_open(const struct path *path, struct file *file, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8120b3d0)
Location: fs/open.c:845
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8120b3d0-ffffffff8120b42b: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_open(const struct path *path, struct file *file, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812310a0)
Location: fs/open.c:845
Inline: False
Direct callers:
  - fs/open.c:filp_clone_open
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812310a0-ffffffff8123110f: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_open(const struct path *path, struct file *file, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81243650)
Location: fs/open.c:862
Inline: False
Direct callers:
  - fs/open.c:filp_clone_open
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81243650-ffffffff812436bf: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_open(const struct path *path, struct file *file, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124eda0)
Location: fs/open.c:862
Inline: False
Direct callers:
  - fs/open.c:filp_clone_open
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8124eda0-ffffffff8124ee13: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_open(const struct path *path, struct file *file, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81270d20)
Location: fs/open.c:862
Inline: False
Direct callers:
  - fs/open.c:filp_clone_open
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81270d20-ffffffff81270d91: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_open(const struct path *path, struct file *file, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812969e0)
Location: fs/open.c:904
Inline: False
Direct callers:
  - fs/open.c:filp_clone_open
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812969e0-ffffffff81296a4d: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812aa1e4)
Location: fs/open.c:887
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812ab7d0-ffffffff812ab7ff: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c698a)
Location: fs/open.c:907
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff812c7fd0-ffffffff812c7fff: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d839a)
Location: fs/open.c:912
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff812d99e0-ffffffff812d9a0f: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130e43a)
Location: fs/open.c:940
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff8130f7a0-ffffffff8130f7cf: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131a50a)
Location: fs/open.c:929
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff8131ba50-ffffffff8131ba7f: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813205ea)
Location: fs/open.c:937
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff81321ba0-ffffffff81321bcf: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136dbaa)
Location: fs/open.c:955
Inline: True
Inline callers:
  - fs/open.c:dentry_open
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff8136f080-ffffffff8136f0af: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813ebfb2)
Location: fs/open.c:978
Inline: True
Inline callers:
  - fs/open.c:dentry_create
  - fs/open.c:dentry_open
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff813eda30-ffffffff813eda6f: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81474494)
Location: fs/open.c:1010
Inline: True
Inline callers:
  - fs/open.c:dentry_create
  - fs/open.c:dentry_open
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff81476180-ffffffff814761bf: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a8e32)
Location: fs/open.c:1045
Inline: True
Inline callers:
  - fs/open.c:dentry_create
  - fs/open.c:dentry_open
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff814aaaa0-ffffffff814aaae5: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814d9e92)
Location: fs/open.c:1084
Inline: True
Inline callers:
  - fs/open.c:dentry_create
  - fs/open.c:dentry_open
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/backing-file.c:backing_file_open
```
**Symbols:**

```
ffffffff814dbf40-ffffffff814dbf85: vfs_open (STB_GLOBAL)
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
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037df94)
Location: fs/open.c:912
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
```
**Symbols:**

```
ffff80001037ed28-ffff80001037ed6c: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (c0567ccc)
Location: fs/open.c:912
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
```
**Symbols:**

```
c0569640-c0569680: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000472ec8)
Location: fs/open.c:912
Inline: True
Inline callers:
  - fs/open.c:dentry_open
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
```
**Symbols:**

```
c000000000474ab0-c000000000474ae8: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000253afc)
Location: fs/open.c:912
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffe000254968-ffffffe0002549aa: vfs_open (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d097a)
Location: fs/open.c:912
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff812d1fc0-ffffffff812d1fef: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c15fa)
Location: fs/open.c:912
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff812c2c40-ffffffff812c2c6f: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ce78a)
Location: fs/open.c:912
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff812cfdd0-ffffffff812cfdff: vfs_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfs_open(const struct path *path, struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812df59a)
Location: fs/open.c:912
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
```
**Symbols:**

```
ffffffff812e0be0-ffffffff812e0c0f: vfs_open (STB_GLOBAL)
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
<b>Param removed. </b>
<code>const struct cred *cred</code>
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
