# Function: <code>vfs_listxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81232350)
Location: fs/xattr.c:268
Inline: True
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff81232350-ffffffff812323b4: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t vfs_listxattr(struct dentry *d, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125a930)
Location: fs/xattr.c:257
Inline: True
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff8125a930-ffffffff8125a995: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126dd00)
Location: fs/xattr.c:349
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff8126dd00-ffffffff8126dd77: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127b520)
Location: fs/xattr.c:349
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff8127b520-ffffffff8127b590: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129dfb0)
Location: fs/xattr.c:350
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff8129dfb0-ffffffff8129e023: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c4670)
Location: fs/xattr.c:349
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff812c4670-ffffffff812c46ea: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812d9870)
Location: fs/xattr.c:348
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff812d9870-ffffffff812d98ea: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f7df0)
Location: fs/xattr.c:349
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff812f7df0-ffffffff812f7e6d: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813099f0)
Location: fs/xattr.c:349
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff813099f0-ffffffff81309a6d: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81342dc0)
Location: fs/xattr.c:386
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff81342dc0-ffffffff81342e3d: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8134f270)
Location: fs/xattr.c:424
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff8134f270-ffffffff8134f2ed: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81355d60)
Location: fs/xattr.c:438
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff81355d60-ffffffff81355ddd: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a42a0)
Location: fs/xattr.c:439
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff813a42a0-ffffffff813a431d: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814280e0)
Location: fs/xattr.c:440
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff814280e0-ffffffff8142816e: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b46a0)
Location: fs/xattr.c:464
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff814b46a0-ffffffff814b472e: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814e96c0)
Location: fs/xattr.c:484
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff814e96c0-ffffffff814e9736: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151d5a0)
Location: fs/xattr.c:484
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff8151d5a0-ffffffff8151d616: vfs_listxattr (STB_GLOBAL)
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
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103bdbe0)
Location: fs/xattr.c:349
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffff8000103bdbe0-ffff8000103bdc84: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059b0d4)
Location: fs/xattr.c:349
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
c059b0d4-c059b154: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bbbc0)
Location: fs/xattr.c:349
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
c0000000004bbbc0-c0000000004bbc9c: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027ed7a)
Location: fs/xattr.c:349
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffe00027ed7a-ffffffe00027edea: vfs_listxattr (STB_GLOBAL)
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
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81301fd0)
Location: fs/xattr.c:349
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff81301fd0-ffffffff8130204d: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f2bf0)
Location: fs/xattr.c:349
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff812f2bf0-ffffffff812f2c6d: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812ffdc0)
Location: fs/xattr.c:349
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff812ffdc0-ffffffff812ffe3d: vfs_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t vfs_listxattr(struct dentry *dentry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81311100)
Location: fs/xattr.c:349
Inline: False
Direct callers:
  - fs/xattr.c:listxattr
  - fs/xattr.c:listxattr
```
**Symbols:**

```
ffffffff81311100-ffffffff8131117d: vfs_listxattr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dentry *dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *d</code>
</li>
</ul>
</details>
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
