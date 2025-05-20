# Function: <code>user_path_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121c770)
Location: fs/namei.c:3492
Inline: True
Inline callers:
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_link
```
**Symbols:**

```
ffffffff8121c770-ffffffff8121c7a4: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812451f5)
Location: fs/namei.c:3658
Inline: True
Inline callers:
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
```
**Symbols:**

```
ffffffff81243bf0-ffffffff81243c24: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81258165)
Location: fs/namei.c:3615
Inline: True
Inline callers:
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
```
**Symbols:**

```
ffffffff81256b70-ffffffff81256ba4: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812642f5)
Location: fs/namei.c:3680
Inline: True
Inline callers:
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
```
**Symbols:**

```
ffffffff81262d10-ffffffff81262d44: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81286b85)
Location: fs/namei.c:3678
Inline: True
Inline callers:
  - fs/namei.c:SyS_link
  - fs/namei.c:SyS_symlink
  - fs/namei.c:SyS_mkdir
  - fs/namei.c:SyS_mknod
```
**Symbols:**

```
ffffffff81285560-ffffffff81285594: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812adef0)
Location: fs/namei.c:3700
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff812ac6a0-ffffffff812ac6d4: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c3000)
Location: fs/namei.c:3690
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff812c17a0-ffffffff812c17d4: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812df746)
Location: fs/namei.c:3689
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff812ddd20-ffffffff812ddd58: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f1256)
Location: fs/namei.c:3684
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff812ef840-ffffffff812ef878: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81329562)
Location: fs/namei.c:3513
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
```
**Symbols:**

```
ffffffff81327700-ffffffff81327772: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813337e2)
Location: fs/namei.c:3515
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
```
**Symbols:**

```
ffffffff81332b10-ffffffff81332b82: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8133989f)
Location: fs/namei.c:3647
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
```
**Symbols:**

```
ffffffff81338b70-ffffffff81338be2: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813865a0)
Location: fs/namei.c:3712
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
```
**Symbols:**

```
ffffffff813865a0-ffffffff813865ed: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81407200)
Location: fs/namei.c:3806
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
```
**Symbols:**

```
ffffffff81407200-ffffffff81407257: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814915d0)
Location: fs/namei.c:3863
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
```
**Symbols:**

```
ffffffff814915d0-ffffffff81491627: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c68f0)
Location: fs/namei.c:3943
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
```
**Symbols:**

```
ffffffff814c68f0-ffffffff814c6947: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f9240)
Location: fs/namei.c:3952
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
```
**Symbols:**

```
ffffffff814f9240-ffffffff814f9297: user_path_create (STB_GLOBAL)
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
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff80001039a9a8)
Location: fs/namei.c:3684
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffff800010399008-ffff800010399058: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0580e38)
Location: fs/namei.c:3684
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
c057f68c-c057f6cc: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0000000004957e4)
Location: fs/namei.c:3684
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
c0000000004936e0-c000000000493740: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000268026)
Location: fs/namei.c:3684
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffe000266ae6-ffffffe000266b26: user_path_create (STB_GLOBAL)
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
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9836)
Location: fs/namei.c:3684
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff812e7e20-ffffffff812e7e58: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812da476)
Location: fs/namei.c:3684
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff812d8a60-ffffffff812d8a98: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e7646)
Location: fs/namei.c:3684
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff812e5c30-ffffffff812e5c68: user_path_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dentry *user_path_create(int dfd, const char *pathname, struct path *path, unsigned int lookup_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f85c6)
Location: fs/namei.c:3684
Inline: True
Inline callers:
  - fs/namei.c:do_linkat
  - fs/namei.c:do_symlinkat
  - fs/namei.c:do_mkdirat
```
**Symbols:**

```
ffffffff812f6bb0-ffffffff812f6be8: user_path_create (STB_GLOBAL)
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
