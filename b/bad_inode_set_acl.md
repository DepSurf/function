# Function: <code>bad_inode_set_acl</code>

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
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812653a0)
Location: fs/bad_inode.c:147
Inline: True
```
**Symbols:**

```
ffffffff812653a0-ffffffff812653b0: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:147
Inline: False
```
**Symbols:**

```
ffffffff81272cd0-ffffffff81272ce0: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
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
ffffffff81295600-ffffffff81295610: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
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
ffffffff812bb800-ffffffff812bb810: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
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
ffffffff812d09f0-ffffffff812d0a00: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812ed980)
Location: fs/bad_inode.c:148
Inline: False
```
**Symbols:**

```
ffffffff812ed980-ffffffff812ed990: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812ff440)
Location: fs/bad_inode.c:148
Inline: False
```
**Symbols:**

```
ffffffff812ff440-ffffffff812ff450: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
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
ffffffff813385e0-ffffffff813385f0: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
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
ffffffff81343f70-ffffffff81343f80: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bad_inode_set_acl(struct user_namespace *mnt_userns, struct inode *inode, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8134a200)
Location: fs/bad_inode.c:156
Inline: False
```
**Symbols:**

```
ffffffff8134a200-ffffffff8134a210: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bad_inode_set_acl(struct user_namespace *mnt_userns, struct inode *inode, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81397f60)
Location: fs/bad_inode.c:156
Inline: False
```
**Symbols:**

```
ffffffff81397f60-ffffffff81397f70: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bad_inode_set_acl(struct user_namespace *mnt_userns, struct inode *inode, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8141a4f0)
Location: fs/bad_inode.c:156
Inline: False
```
**Symbols:**

```
ffffffff8141a4f0-ffffffff8141a504: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bad_inode_set_acl(struct user_namespace *mnt_userns, struct dentry *dentry, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff814a6340)
Location: fs/bad_inode.c:156
Inline: False
```
**Symbols:**

```
ffffffff814a6340-ffffffff814a6354: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bad_inode_set_acl(struct mnt_idmap *idmap, struct dentry *dentry, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff814db300)
Location: fs/bad_inode.c:156
Inline: False
```
**Symbols:**

```
ffffffff814db300-ffffffff814db314: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bad_inode_set_acl(struct mnt_idmap *idmap, struct dentry *dentry, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8150d8f0)
Location: fs/bad_inode.c:155
Inline: False
```
**Symbols:**

```
ffffffff8150d8f0-ffffffff8150d904: bad_inode_set_acl (STB_LOCAL)
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
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
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
ffff8000103b0a28-ffff8000103b0a44: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
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
c0590334-c0590350: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (c0000000004ac240)
Location: fs/bad_inode.c:148
Inline: False
```
**Symbols:**

```
c0000000004ac240-c0000000004ac250: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
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
ffffffe000274d62-ffffffe000274d7e: bad_inode_set_acl (STB_LOCAL)
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
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812f7a20)
Location: fs/bad_inode.c:148
Inline: False
```
**Symbols:**

```
ffffffff812f7a20-ffffffff812f7a30: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812e8640)
Location: fs/bad_inode.c:148
Inline: False
```
**Symbols:**

```
ffffffff812e8640-ffffffff812e8650: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812f5830)
Location: fs/bad_inode.c:148
Inline: False
```
**Symbols:**

```
ffffffff812f5830-ffffffff812f5840: bad_inode_set_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bad_inode_set_acl(struct inode *inode, struct posix_acl *acl, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff813069c0)
Location: fs/bad_inode.c:148
Inline: False
```
**Symbols:**

```
ffffffff813069c0-ffffffff813069d0: bad_inode_set_acl (STB_LOCAL)
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
<code>inode, acl, type</code> ➡️ <code>mnt_userns, inode, acl, type</code>
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
<code>struct dentry *dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *inode</code>
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
