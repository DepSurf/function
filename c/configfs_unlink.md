# Function: <code>configfs_unlink</code>

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
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff812e16a0)
Location: fs/configfs/symlink.c:184
Inline: False
```
**Symbols:**

```
ffffffff812e16a0-ffffffff812e182f: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81305fe0)
Location: fs/configfs/symlink.c:184
Inline: False
```
**Symbols:**

```
ffffffff81305fe0-ffffffff81306172: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81333fe0)
Location: fs/configfs/symlink.c:184
Inline: False
```
**Symbols:**

```
ffffffff81333fe0-ffffffff81334189: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff8134b350)
Location: fs/configfs/symlink.c:184
Inline: False
```
**Symbols:**

```
ffffffff8134b350-ffffffff8134b4f7: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/symlink.c (0)
Location: fs/configfs/symlink.c:170
Inline: False
```
**Symbols:**

```
ffffffff81373eb5-ffffffff81373ed0: configfs_unlink.cold (STB_LOCAL)
ffffffff81373d00-ffffffff81373eb5: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff8138bf50)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffffffff8138bf50-ffffffff8138c10d: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813d7290)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffffffff813d7290-ffffffff813d744d: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813e8f30)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffffffff813e8f30-ffffffff813e90ed: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813efaa0)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffffffff813efaa0-ffffffff813efc5d: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81441990)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffffffff81441990-ffffffff81441b4d: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff814bd590)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffffffff814bd590-ffffffff814bd739: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81555210)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffffffff81555210-ffffffff815553b9: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff8158cfb0)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffffffff8158cfb0-ffffffff8158d159: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff815c5cf0)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffffffff815c5cf0-ffffffff815c5e9f: configfs_unlink (STB_GLOBAL)
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
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffff80001045d6c0)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffff80001045d6c0-ffff80001045d964: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (c061e460)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
c061e460-c061e69c: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (c000000000579370)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
c000000000579370-c000000000579668: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffe0002ed6dc)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffffffe0002ed6dc-ffffffe0002ed90c: configfs_unlink (STB_GLOBAL)
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
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81384530)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffffffff81384530-ffffffff813846ed: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81374fc0)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffffffff81374fc0-ffffffff8137517d: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81382000)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffffffff81382000-ffffffff813821bd: configfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int configfs_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81395b30)
Location: fs/configfs/symlink.c:220
Inline: False
```
**Symbols:**

```
ffffffff81395b30-ffffffff81395cd9: configfs_unlink (STB_GLOBAL)
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
