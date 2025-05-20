# Function: <code>d_instantiate_new</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b4ec0)
Location: fs/dcache.c:1885
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812b4ec0-ffffffff812b4f48: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ca320)
Location: fs/dcache.c:1893
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812ca320-ffffffff812ca3aa: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:1967
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812e9d67-ffffffff812e9d81: d_instantiate_new.cold (STB_LOCAL)
ffffffff812e6d90-ffffffff812e6e1c: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f8840)
Location: fs/dcache.c:1967
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812f8840-ffffffff812f88ca: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81331460)
Location: fs/dcache.c:1988
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff81331460-ffffffff813314ea: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133cdf0)
Location: fs/dcache.c:1995
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff8133cdf0-ffffffff8133ce7a: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81343270)
Location: fs/dcache.c:2022
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff81343270-ffffffff813432fa: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81390af0)
Location: fs/dcache.c:2023
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff81390af0-ffffffff81390b7a: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81412840)
Location: fs/dcache.c:2048
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff81412840-ffffffff814128d2: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149da90)
Location: fs/dcache.c:2048
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff8149da90-ffffffff8149db22: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d2ed0)
Location: fs/dcache.c:2048
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff814d2ed0-ffffffff814d2f62: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff815056c0)
Location: fs/dcache.c:1892
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_nondir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff815056c0-ffffffff81505752: d_instantiate_new (STB_GLOBAL)
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
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a6c98)
Location: fs/dcache.c:1967
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffff8000103a6c98-ffff8000103a6d74: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0588680)
Location: fs/dcache.c:1967
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
c0588680-c0588730: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a1670)
Location: fs/dcache.c:1967
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
c0000000004a1670-c0000000004a1760: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026d02a)
Location: fs/dcache.c:1967
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffe00026d02a-ffffffe00026d0e6: d_instantiate_new (STB_GLOBAL)
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
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0e20)
Location: fs/dcache.c:1967
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812f0e20-ffffffff812f0eaa: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e1a50)
Location: fs/dcache.c:1967
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812e1a50-ffffffff812e1ada: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812eec30)
Location: fs/dcache.c:1967
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812eec30-ffffffff812eecba: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void d_instantiate_new(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ffed0)
Location: fs/dcache.c:1967
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812ffed0-ffffffff812fff58: d_instantiate_new (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
