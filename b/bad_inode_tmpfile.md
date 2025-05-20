# Function: <code>bad_inode_tmpfile</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81265390)
Location: fs/bad_inode.c:141
Inline: True
```
**Symbols:**

```
ffffffff81265390-ffffffff812653a0: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:141
Inline: False
```
**Symbols:**

```
ffffffff81272ca0-ffffffff81272cb0: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:142
Inline: False
```
**Symbols:**

```
ffffffff812955d0-ffffffff812955e0: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:142
Inline: False
```
**Symbols:**

```
ffffffff812bb7d0-ffffffff812bb7e0: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:142
Inline: False
```
**Symbols:**

```
ffffffff812d09c0-ffffffff812d09d0: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812ed970)
Location: fs/bad_inode.c:142
Inline: False
```
**Symbols:**

```
ffffffff812ed970-ffffffff812ed980: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812ff430)
Location: fs/bad_inode.c:142
Inline: False
```
**Symbols:**

```
ffffffff812ff430-ffffffff812ff440: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:143
Inline: False
```
**Symbols:**

```
ffffffff813385b0-ffffffff813385c0: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:143
Inline: False
```
**Symbols:**

```
ffffffff81343f40-ffffffff81343f50: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct user_namespace *mnt_userns, struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:149
Inline: False
```
**Symbols:**

```
ffffffff8134a2f0-ffffffff8134a300: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct user_namespace *mnt_userns, struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:149
Inline: False
```
**Symbols:**

```
ffffffff81398050-ffffffff81398060: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct user_namespace *mnt_userns, struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:149
Inline: False
```
**Symbols:**

```
ffffffff8141a600-ffffffff8141a614: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct user_namespace *mnt_userns, struct inode *inode, struct file *file, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:149
Inline: False
```
**Symbols:**

```
ffffffff814a64a0-ffffffff814a64b4: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct mnt_idmap *idmap, struct inode *inode, struct file *file, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:149
Inline: False
```
**Symbols:**

```
ffffffff814db460-ffffffff814db474: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct mnt_idmap *idmap, struct inode *inode, struct file *file, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:148
Inline: False
```
**Symbols:**

```
ffffffff8150da00-ffffffff8150da14: bad_inode_tmpfile (STB_LOCAL)
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
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:142
Inline: False
```
**Symbols:**

```
ffff8000103b09c8-ffff8000103b09e4: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:142
Inline: False
```
**Symbols:**

```
c05902e0-c05902fc: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (c0000000004ac230)
Location: fs/bad_inode.c:142
Inline: False
```
**Symbols:**

```
c0000000004ac230-c0000000004ac240: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:142
Inline: False
```
**Symbols:**

```
ffffffe000274d0e-ffffffe000274d2a: bad_inode_tmpfile (STB_LOCAL)
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
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812f7a10)
Location: fs/bad_inode.c:142
Inline: False
```
**Symbols:**

```
ffffffff812f7a10-ffffffff812f7a20: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812e8630)
Location: fs/bad_inode.c:142
Inline: False
```
**Symbols:**

```
ffffffff812e8630-ffffffff812e8640: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812f5820)
Location: fs/bad_inode.c:142
Inline: False
```
**Symbols:**

```
ffffffff812f5820-ffffffff812f5830: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bad_inode_tmpfile(struct inode *inode, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff813069b0)
Location: fs/bad_inode.c:142
Inline: False
```
**Symbols:**

```
ffffffff813069b0-ffffffff813069c0: bad_inode_tmpfile (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>inode, dentry, mode</code> ➡️ <code>mnt_userns, inode, dentry, mode</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *dentry</code>
</li>
</ul>
</details>
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
