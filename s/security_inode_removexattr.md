# Function: <code>security_inode_removexattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133db20)
Location: security/security.c:677
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff8133db20-ffffffff8133dba8: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81373160)
Location: security/security.c:678
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff81373160-ffffffff813731e8: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81389a90)
Location: security/security.c:687
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff81389a90-ffffffff81389b18: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139ee60)
Location: security/security.c:1292
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff8139ee60-ffffffff8139eee8: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c4910)
Location: security/security.c:1241
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff813c4910-ffffffff813c499e: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f4ce0)
Location: security/security.c:783
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff813f4ce0-ffffffff813f4d64: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814100b0)
Location: security/security.c:1304
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff814100b0-ffffffff81410134: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143d770)
Location: security/security.c:1317
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff8143d770-ffffffff8143d7f6: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814571e0)
Location: security/security.c:1357
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff814571e0-ffffffff81457264: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a9ff0)
Location: security/security.c:1505
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff814a9ff0-ffffffff814aa074: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c7600)
Location: security/security.c:1507
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff814c7600-ffffffff814c7684: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_inode_removexattr(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cdaa0)
Location: security/security.c:1554
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff814cdaa0-ffffffff814cdb37: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_inode_removexattr(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815269b0)
Location: security/security.c:1561
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff815269b0-ffffffff81526a4a: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_inode_removexattr(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bb3c0)
Location: security/security.c:1567
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff815bb3c0-ffffffff815bb47a: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_inode_removexattr(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81667130)
Location: security/security.c:1608
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff81667130-ffffffff816671ea: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_inode_removexattr(struct mnt_idmap *idmap, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169f720)
Location: security/security.c:2447
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff8169f720-ffffffff8169f7da: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_inode_removexattr(struct mnt_idmap *idmap, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dc080)
Location: security/security.c:2521
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
```
**Symbols:**

```
ffffffff816dc080-ffffffff816dc13a: security_inode_removexattr (STB_GLOBAL)
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
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010542cf0)
Location: security/security.c:1357
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffff800010542cf0-ffff800010542dac: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f8cb8)
Location: security/security.c:1357
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
c06f8cb8-c06f8d68: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000696670)
Location: security/security.c:1357
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
c000000000696670-c0000000006967a8: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039f42c)
Location: security/security.c:1357
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffe00039f42c-ffffffe00039f4c6: security_inode_removexattr (STB_GLOBAL)
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
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144f7c0)
Location: security/security.c:1357
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff8144f7c0-ffffffff8144f844: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81440210)
Location: security/security.c:1357
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff81440210-ffffffff81440294: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144b860)
Location: security/security.c:1357
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff8144b860-ffffffff8144b8e4: security_inode_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81462c30)
Location: security/security.c:1357
Inline: False
Direct callers:
  - fs/xattr.c:vfs_removexattr
```
**Symbols:**

```
ffffffff81462c30-ffffffff81462cb4: security_inode_removexattr (STB_GLOBAL)
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
<code>dentry, name</code> ➡️ <code>mnt_userns, dentry, name</code>
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
