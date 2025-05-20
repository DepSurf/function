# Function: <code>ramfs_get_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff812f3220)
Location: fs/ramfs/inode.c:53
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_mknod
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_fill_super
```
**Symbols:**

```
ffffffff812f3220-ffffffff812f335b: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff813269a0)
Location: fs/ramfs/inode.c:53
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff813269a0-ffffffff81326ae3: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff8133c750)
Location: fs/ramfs/inode.c:53
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff8133c750-ffffffff8133c87e: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff81351280)
Location: fs/ramfs/inode.c:61
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff81351280-ffffffff813513b8: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff81375d80)
Location: fs/ramfs/inode.c:61
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff81375d80-ffffffff81375ebb: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff813a47a0)
Location: fs/ramfs/inode.c:61
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff813a47a0-ffffffff813a48d0: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff813bd5a0)
Location: fs/ramfs/inode.c:61
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff813bd5a0-ffffffff813bd6cd: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff813e7e60)
Location: fs/ramfs/inode.c:61
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff813e7e60-ffffffff813e7f9a: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff81401fd0)
Location: fs/ramfs/inode.c:63
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff81401fd0-ffffffff8140210a: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff8144fbe0)
Location: fs/ramfs/inode.c:63
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff8144fbe0-ffffffff8144fd1a: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff8146c0f0)
Location: fs/ramfs/inode.c:63
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff8146c0f0-ffffffff8146c22a: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff81471770)
Location: fs/ramfs/inode.c:63
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_tmpfile
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff81471770-ffffffff814718b0: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff814c8200)
Location: fs/ramfs/inode.c:56
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_tmpfile
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff814c8200-ffffffff814c8345: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff81553730)
Location: fs/ramfs/inode.c:57
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_tmpfile
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff81553730-ffffffff8155389c: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff815f4f20)
Location: fs/ramfs/inode.c:57
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_tmpfile
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff815f4f20-ffffffff815f508c: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff8162cfa0)
Location: fs/ramfs/inode.c:57
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_tmpfile
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff8162cfa0-ffffffff8162d10c: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff816664c0)
Location: fs/ramfs/inode.c:57
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_tmpfile
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff816664c0-ffffffff8166660d: ramfs_get_inode (STB_GLOBAL)
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
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffff8000104e0328)
Location: fs/ramfs/inode.c:63
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffff8000104e0328-ffff8000104e04b8: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (c06a1bb4)
Location: fs/ramfs/inode.c:63
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
c06a1bb4-c06a1d14: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (c00000000061cad0)
Location: fs/ramfs/inode.c:63
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
c00000000061cad0-c00000000061cccc: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffe0003545d0)
Location: fs/ramfs/inode.c:63
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffe0003545d0-ffffffe0003546de: ramfs_get_inode (STB_GLOBAL)
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
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff813fa5b0)
Location: fs/ramfs/inode.c:63
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff813fa5b0-ffffffff813fa6ea: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff813eb030)
Location: fs/ramfs/inode.c:63
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff813eb030-ffffffff813eb16a: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff813f7930)
Location: fs/ramfs/inode.c:63
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff813f7930-ffffffff813f7a6a: ramfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *ramfs_get_inode(struct super_block *sb, const struct inode *dir, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ramfs/inode.c (ffffffff8140d5c0)
Location: fs/ramfs/inode.c:63
Inline: False
Direct callers:
  - fs/ramfs/inode.c:ramfs_fill_super
  - fs/ramfs/inode.c:ramfs_symlink
  - fs/ramfs/inode.c:ramfs_mknod
```
**Symbols:**

```
ffffffff8140d5c0-ffffffff8140d6fa: ramfs_get_inode (STB_GLOBAL)
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
