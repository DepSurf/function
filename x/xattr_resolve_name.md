# Function: <code>xattr_resolve_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(const struct xattr_handler **handlers, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81231ae0)
Location: fs/xattr.c:705
Inline: False
Direct callers:
  - fs/xattr.c:generic_getxattr
  - fs/xattr.c:generic_setxattr
  - fs/xattr.c:generic_removexattr
```
**Symbols:**

```
ffffffff81231ae0-ffffffff81231b46: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(const struct xattr_handler **handlers, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125a1d0)
Location: fs/xattr.c:698
Inline: False
Direct callers:
  - fs/xattr.c:generic_removexattr
  - fs/xattr.c:generic_setxattr
  - fs/xattr.c:generic_getxattr
```
**Symbols:**

```
ffffffff8125a1d0-ffffffff8125a27b: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126d740)
Location: fs/xattr.c:53
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff8126d740-ffffffff8126d805: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127af70)
Location: fs/xattr.c:53
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff8127af70-ffffffff8127b035: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129d9e0)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff8129d9e0-ffffffff8129daa5: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c4090)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff812c4090-ffffffff812c4155: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812d9290)
Location: fs/xattr.c:53
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff812d9290-ffffffff812d9355: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f7820)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff812f7820-ffffffff812f78e2: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81309420)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff81309420-ffffffff813094e2: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81342930)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff81342930-ffffffff813429f8: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8134eb60)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff8134eb60-ffffffff8134ec28: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81355750)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff81355750-ffffffff81355815: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a3b70)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff813a3b70-ffffffff813a3c35: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81427950)
Location: fs/xattr.c:56
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff81427950-ffffffff81427a5e: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b4460)
Location: fs/xattr.c:56
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff814b4460-ffffffff814b456e: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814e9500)
Location: fs/xattr.c:57
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff814e9500-ffffffff814e960e: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151d3e0)
Location: fs/xattr.c:57
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff8151d3e0-ffffffff8151d4ee: xattr_resolve_name (STB_LOCAL)
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
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103bd598)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffff8000103bd598-ffff8000103bd674: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059aabc)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
c059aabc-c059aba4: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bb0b0)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
c0000000004bb0b0-c0000000004bb1e0: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027e868)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffe00027e868-ffffffe00027e918: xattr_resolve_name (STB_LOCAL)
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
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81301a00)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff81301a00-ffffffff81301ac2: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f2620)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff812f2620-ffffffff812f26e2: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812ff7f0)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff812ff7f0-ffffffff812ff8b2: xattr_resolve_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct xattr_handler *xattr_resolve_name(struct inode *inode, const char **name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81310b30)
Location: fs/xattr.c:54
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr
  - fs/xattr.c:__vfs_getxattr
  - fs/xattr.c:vfs_getxattr_alloc
  - fs/xattr.c:__vfs_setxattr
```
**Symbols:**

```
ffffffff81310b30-ffffffff81310bf2: xattr_resolve_name (STB_LOCAL)
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
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct xattr_handler **handlers</code>
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
