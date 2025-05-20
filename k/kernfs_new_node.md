# Function: <code>kernfs_new_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128a810)
Location: fs/kernfs/dir.c:703
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff8128a810-ffffffff8128a853: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b7c50)
Location: fs/kernfs/dir.c:695
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff812b7c50-ffffffff812b7c93: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cd3f0)
Location: fs/kernfs/dir.c:645
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff812cd3f0-ffffffff812cd433: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812da9b0)
Location: fs/kernfs/dir.c:655
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff812da9b0-ffffffff812da9f8: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812ff240)
Location: fs/kernfs/dir.c:673
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff812ff240-ffffffff812ff288: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132cf00)
Location: fs/kernfs/dir.c:688
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff8132cf00-ffffffff8132cf43: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813442a0)
Location: fs/kernfs/dir.c:688
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff813442a0-ffffffff813442e3: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136c4b0)
Location: fs/kernfs/dir.c:690
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff8136c4b0-ffffffff8136c509: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384660)
Location: fs/kernfs/dir.c:690
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff81384660-ffffffff813846b9: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813cf595)
Location: fs/kernfs/dir.c:682
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
Direct callers:
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff813cf110-ffffffff813cf169: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e11c9)
Location: fs/kernfs/dir.c:681
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
Direct callers:
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff813e0d40-ffffffff813e0d99: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e7df9)
Location: fs/kernfs/dir.c:681
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
Direct callers:
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff813e7870-ffffffff813e78c9: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81439b29)
Location: fs/kernfs/dir.c:640
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
Direct callers:
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff81439580-ffffffff814395d7: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b4ba9)
Location: fs/kernfs/dir.c:648
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
Direct callers:
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff814b45f0-ffffffff814b465c: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154bac9)
Location: fs/kernfs/dir.c:669
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
Direct callers:
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff8154b4e0-ffffffff8154b54c: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81583759)
Location: fs/kernfs/dir.c:668
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
Direct callers:
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff81583130-ffffffff8158319c: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815bbd60)
Location: fs/kernfs/dir.c:672
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff815bbd60-ffffffff815bbdea: kernfs_new_node (STB_GLOBAL)
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
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff8000104533e8)
Location: fs/kernfs/dir.c:690
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffff8000104533e8-ffff800010453474: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0615fbc)
Location: fs/kernfs/dir.c:690
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
c0615fbc-c0616034: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056c740)
Location: fs/kernfs/dir.c:690
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
c00000000056c740-c00000000056c7d8: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e5a76)
Location: fs/kernfs/dir.c:690
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffe0002e5a76-ffffffe0002e5ae8: kernfs_new_node (STB_GLOBAL)
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
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137cc40)
Location: fs/kernfs/dir.c:690
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff8137cc40-ffffffff8137cc99: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136d710)
Location: fs/kernfs/dir.c:690
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff8136d710-ffffffff8136d769: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137a710)
Location: fs/kernfs/dir.c:690
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff8137a710-ffffffff8137a769: kernfs_new_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kernfs_node *kernfs_new_node(struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138e200)
Location: fs/kernfs/dir.c:690
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/file.c:__kernfs_create_file
  - fs/kernfs/symlink.c:kernfs_create_link
```
**Symbols:**

```
ffffffff8138e200-ffffffff8138e259: kernfs_new_node (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>kuid_t uid</code>
</li>
<li>
<b>Param added. </b>
<code>kgid_t gid</code>
</li>
<li>
<b>Param reordered. </b>
<code>parent, name, mode, flags</code> ➡️ <code>parent, name, mode, uid, gid, flags</code>
</li>
</ul>
</details>
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
