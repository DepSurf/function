# Function: <code>may_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81218240)
Location: fs/namei.c:2553
Inline: False
Direct callers:
  - fs/namei.c:vfs_unlink
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff81218240-ffffffff81218380: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123f290)
Location: fs/namei.c:2768
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff8123f290-ffffffff8123f40c: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81252060)
Location: fs/namei.c:2732
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff81252060-ffffffff812521dc: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125e0a0)
Location: fs/namei.c:2777
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff8125e0a0-ffffffff8125e20e: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81280470)
Location: fs/namei.c:2775
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff81280470-ffffffff812805de: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a8ad0)
Location: fs/namei.c:2771
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff812a8ad0-ffffffff812a8c6a: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bda10)
Location: fs/namei.c:2790
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff812bda10-ffffffff812bdbaa: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812da460)
Location: fs/namei.c:2788
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff812da460-ffffffff812da5fc: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ebf70)
Location: fs/namei.c:2781
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff812ebf70-ffffffff812ec10c: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813240f0)
Location: fs/namei.c:2683
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
```
**Symbols:**

```
ffffffff813240f0-ffffffff813242e3: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132f6f0)
Location: fs/namei.c:2681
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
  - fs/namei.c:do_rmdir
```
**Symbols:**

```
ffffffff8132f6f0-ffffffff8132f8e3: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int may_delete(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81335370)
Location: fs/namei.c:2772
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff81335370-ffffffff8133550a: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int may_delete(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81383090)
Location: fs/namei.c:2841
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff81383090-ffffffff8138322a: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int may_delete(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81403400)
Location: fs/namei.c:2937
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff81403400-ffffffff814036b4: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int may_delete(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148d830)
Location: fs/namei.c:2916
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff8148d830-ffffffff8148dae4: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int may_delete(struct mnt_idmap *idmap, struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c18b0)
Location: fs/namei.c:2947
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff814c18b0-ffffffff814c1a99: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int may_delete(struct mnt_idmap *idmap, struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f3d70)
Location: fs/namei.c:2964
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff814f3d70-ffffffff814f3f59: may_delete (STB_LOCAL)
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
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff8000103956c8)
Location: fs/namei.c:2781
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffff8000103956c8-ffff800010395878: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057ab18)
Location: fs/namei.c:2781
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
c057ab18-c057ac94: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048d010)
Location: fs/namei.c:2781
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
c00000000048d010-c00000000048d240: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000263eb8)
Location: fs/namei.c:2781
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffe000263eb8-ffffffe000263fe8: may_delete (STB_LOCAL)
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
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e4550)
Location: fs/namei.c:2781
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff812e4550-ffffffff812e46ec: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d5190)
Location: fs/namei.c:2781
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff812d5190-ffffffff812d532c: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e2360)
Location: fs/namei.c:2781
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff812e2360-ffffffff812e24fc: may_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int may_delete(struct inode *dir, struct dentry *victim, bool isdir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f1ef0)
Location: fs/namei.c:2781
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_unlink
```
**Symbols:**

```
ffffffff812f1ef0-ffffffff812f208c: may_delete (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>dir, victim, isdir</code> ➡️ <code>mnt_userns, dir, victim, isdir</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
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
