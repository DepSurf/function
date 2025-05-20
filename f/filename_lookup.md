# Function: <code>filename_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121c1e0)
Location: fs/namei.c:2153
Inline: False
Direct callers:
  - fs/namei.c:kern_path
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:user_path_at_empty
```
**Symbols:**

```
ffffffff8121c1e0-ffffffff8121c360: filename_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81243660)
Location: fs/namei.c:2290
Inline: False
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
```
**Symbols:**

```
ffffffff81243660-ffffffff812437e0: filename_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812565e0)
Location: fs/namei.c:2279
Inline: False
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
```
**Symbols:**

```
ffffffff812565e0-ffffffff81256760: filename_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81262770)
Location: fs/namei.c:2324
Inline: False
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
```
**Symbols:**

```
ffffffff81262770-ffffffff812628f5: filename_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81284fc0)
Location: fs/namei.c:2322
Inline: False
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
```
**Symbols:**

```
ffffffff81284fc0-ffffffff81285145: filename_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812ac343)
Location: fs/namei.c:2309
Inline: True
Inline callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
```
**Symbols:**

```
ffffffff812ac100-ffffffff812ac268: filename_lookup.part.59 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812c1443)
Location: fs/namei.c:2336
Inline: True
Inline callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
```
**Symbols:**

```
ffffffff812c1200-ffffffff812c1368: filename_lookup.part.60 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812de450)
Location: fs/namei.c:2334
Inline: False
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
```
**Symbols:**

```
ffffffff812de450-ffffffff812de5c5: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812eff70)
Location: fs/namei.c:2327
Inline: False
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
```
**Symbols:**

```
ffffffff812eff70-ffffffff812f00df: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81328290)
Location: fs/namei.c:2354
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
```
**Symbols:**

```
ffffffff81328290-ffffffff8132843a: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81333450)
Location: fs/namei.c:2352
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
```
**Symbols:**

```
ffffffff81333450-ffffffff813335fa: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81339500)
Location: fs/namei.c:2442
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
```
**Symbols:**

```
ffffffff81339500-ffffffff813396bc: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81386b60)
Location: fs/namei.c:2470
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
```
**Symbols:**

```
ffffffff81386b60-ffffffff81386d29: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81407880)
Location: fs/namei.c:2516
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
  - io_uring/io_uring.c:io_setxattr
  - io_uring/io_uring.c:io_getxattr
```
**Symbols:**

```
ffffffff81407880-ffffffff81407a76: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81491cf0)
Location: fs/namei.c:2495
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_getxattr
```
**Symbols:**

```
ffffffff81491cf0-ffffffff81491ee6: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c6d30)
Location: fs/namei.c:2500
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_getxattr
```
**Symbols:**

```
ffffffff814c6d30-ffffffff814c6f26: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f9680)
Location: fs/namei.c:2507
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/namei.c:do_linkat
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_getxattr
```
**Symbols:**

```
ffffffff814f9680-ffffffff814f9876: filename_lookup (STB_GLOBAL)
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
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010399650)
Location: fs/namei.c:2327
Inline: False
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
```
**Symbols:**

```
ffff800010399650-ffff8000103997b4: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057fc00)
Location: fs/namei.c:2327
Inline: False
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
```
**Symbols:**

```
c057fc00-c057fd70: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000493f80)
Location: fs/namei.c:2327
Inline: False
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
  - fs/fs_parser.c:fs_lookup_param
```
**Symbols:**

```
c000000000493f80-c000000000494154: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000267002)
Location: fs/namei.c:2327
Inline: False
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
```
**Symbols:**

```
ffffffe000267002-ffffffe0002670fe: filename_lookup (STB_GLOBAL)
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
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e8550)
Location: fs/namei.c:2327
Inline: False
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
```
**Symbols:**

```
ffffffff812e8550-ffffffff812e86bf: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d9190)
Location: fs/namei.c:2327
Inline: False
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
```
**Symbols:**

```
ffffffff812d9190-ffffffff812d92ff: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e6360)
Location: fs/namei.c:2327
Inline: False
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
```
**Symbols:**

```
ffffffff812e6360-ffffffff812e64cf: filename_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int filename_lookup(int dfd, struct filename *name, unsigned int flags, struct path *path, struct path *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f72e0)
Location: fs/namei.c:2327
Inline: False
Direct callers:
  - fs/namei.c:user_path_at_empty
  - fs/namei.c:vfs_path_lookup
  - fs/namei.c:kern_path
  - fs/fs_parser.c:fs_lookup_param
```
**Symbols:**

```
ffffffff812f72e0-ffffffff812f744f: filename_lookup (STB_GLOBAL)
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
