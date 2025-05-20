# Function: <code>filename_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121c5d0)
Location: fs/namei.c:3404
Inline: False
Direct callers:
  - fs/namei.c:kern_path_create
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_link
```
**Symbols:**

```
ffffffff8121c5d0-ffffffff8121c72c: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81243a50)
Location: fs/namei.c:3570
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff81243a50-ffffffff81243ba3: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812569d0)
Location: fs/namei.c:3527
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff812569d0-ffffffff81256b23: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81262b70)
Location: fs/namei.c:3592
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff81262b70-ffffffff81262cc4: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812853c0)
Location: fs/namei.c:3590
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff812853c0-ffffffff81285514: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ac4e0)
Location: fs/namei.c:3612
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff812ac4e0-ffffffff812ac656: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c15e0)
Location: fs/namei.c:3602
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff812c15e0-ffffffff812c1756: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ddb80)
Location: fs/namei.c:3601
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff812ddb80-ffffffff812ddcd8: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ef6a0)
Location: fs/namei.c:3596
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff812ef6a0-ffffffff812ef7f8: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81327560)
Location: fs/namei.c:3425
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff81327560-ffffffff813276b8: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81332970)
Location: fs/namei.c:3427
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff81332970-ffffffff81332ac8: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813389d0)
Location: fs/namei.c:3559
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff813389d0-ffffffff81338b28: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81382d90)
Location: fs/namei.c:3623
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff81382d90-ffffffff81382ed5: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81406280)
Location: fs/namei.c:3719
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff81406280-ffffffff8140642c: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814905e0)
Location: fs/namei.c:3776
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff814905e0-ffffffff8149078c: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c59e0)
Location: fs/namei.c:3855
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff814c59e0-ffffffff814c5b8f: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f82d0)
Location: fs/namei.c:3864
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mknodat
  - fs/namei.c:user_path_create
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff814f82d0-ffffffff814f847f: filename_create (STB_LOCAL)
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
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010398e40)
Location: fs/namei.c:3596
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffff800010398e40-ffff800010398fac: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057f4e4)
Location: fs/namei.c:3596
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
c057f4e4-c057f64c: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000493470)
Location: fs/namei.c:3596
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
c000000000493470-c000000000493678: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe00026697c)
Location: fs/namei.c:3596
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffe00026697c-ffffffe000266a9a: filename_create (STB_LOCAL)
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
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e7c80)
Location: fs/namei.c:3596
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff812e7c80-ffffffff812e7dd8: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d88c0)
Location: fs/namei.c:3596
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff812d88c0-ffffffff812d8a18: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5a90)
Location: fs/namei.c:3596
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff812e5a90-ffffffff812e5be8: filename_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *filename_create(int dfd, struct filename *name, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f6a10)
Location: fs/namei.c:3596
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
  - fs/namei.c:kern_path_create
```
**Symbols:**

```
ffffffff812f6a10-ffffffff812f6b68: filename_create (STB_LOCAL)
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
