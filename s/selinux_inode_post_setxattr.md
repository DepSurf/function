# Function: <code>selinux_inode_post_setxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813448c0)
Location: security/selinux/hooks.c:3078
Inline: False
```
**Symbols:**

```
ffffffff813448c0-ffffffff813449cc: selinux_inode_post_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81379e60)
Location: security/selinux/hooks.c:3158
Inline: False
```
**Symbols:**

```
ffffffff81379e60-ffffffff81379f8a: selinux_inode_post_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81390560)
Location: security/selinux/hooks.c:3191
Inline: False
```
**Symbols:**

```
ffffffff81390560-ffffffff813906ab: selinux_inode_post_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a69a0)
Location: security/selinux/hooks.c:3178
Inline: False
```
**Symbols:**

```
ffffffff813a69a0-ffffffff813a6ae3: selinux_inode_post_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cc3f0)
Location: security/selinux/hooks.c:3186
Inline: False
```
**Symbols:**

```
ffffffff813cc3f0-ffffffff813cc533: selinux_inode_post_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3343
Inline: False
```
**Symbols:**

```
ffffffff81400570-ffffffff8140069b: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff81402c5c-ffffffff81402c80: selinux_inode_post_setxattr.cold.82 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3091
Inline: False
```
**Symbols:**

```
ffffffff8141c5f0-ffffffff8141c723: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff8141e7c9-ffffffff8141e7ed: selinux_inode_post_setxattr.cold.77 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3214
Inline: False
```
**Symbols:**

```
ffffffff81449fe0-ffffffff8144a11e: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff8144c41b-ffffffff8144c43f: selinux_inode_post_setxattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3228
Inline: False
```
**Symbols:**

```
ffffffff81463cf0-ffffffff81463e2e: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff8146620b-ffffffff8146622f: selinux_inode_post_setxattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3206
Inline: False
```
**Symbols:**

```
ffffffff814b7df0-ffffffff814b7f1b: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff814b9e05-ffffffff814b9e29: selinux_inode_post_setxattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3214
Inline: False
```
**Symbols:**

```
ffffffff814d5b00-ffffffff814d5c2b: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff81bf02af-ffffffff81bf02d3: selinux_inode_post_setxattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3369
Inline: False
```
**Symbols:**

```
ffffffff814dc960-ffffffff814dca88: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff81be24c2-ffffffff81be24e6: selinux_inode_post_setxattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3354
Inline: False
```
**Symbols:**

```
ffffffff81535e20-ffffffff81535f59: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff81cd3dd6-ffffffff81cd3e0f: selinux_inode_post_setxattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3246
Inline: False
```
**Symbols:**

```
ffffffff815cc8a0-ffffffff815cc9ee: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff81e86de9-ffffffff81e86e22: selinux_inode_post_setxattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3264
Inline: False
```
**Symbols:**

```
ffffffff81679b30-ffffffff81679ca0: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff820737af-ffffffff820737c4: selinux_inode_post_setxattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3257
Inline: False
```
**Symbols:**

```
ffffffff816b1c80-ffffffff816b1de2: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff820f33a9-ffffffff820f33be: selinux_inode_post_setxattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3314
Inline: False
```
**Symbols:**

```
ffffffff816eed10-ffffffff816eee72: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff821d0520-ffffffff821d0535: selinux_inode_post_setxattr.cold (STB_LOCAL)
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
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010551cf8)
Location: security/selinux/hooks.c:3228
Inline: False
```
**Symbols:**

```
ffff800010551cf8-ffff800010551eac: selinux_inode_post_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0704030)
Location: security/selinux/hooks.c:3228
Inline: False
```
**Symbols:**

```
c0704030-c07041a8: selinux_inode_post_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a8300)
Location: security/selinux/hooks.c:3228
Inline: False
```
**Symbols:**

```
c0000000006a8300-c0000000006a8678: selinux_inode_post_setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003aadca)
Location: security/selinux/hooks.c:3228
Inline: False
```
**Symbols:**

```
ffffffe0003aadca-ffffffe0003aaf26: selinux_inode_post_setxattr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3228
Inline: False
```
**Symbols:**

```
ffffffff8145c2d0-ffffffff8145c40e: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff8145e7eb-ffffffff8145e80f: selinux_inode_post_setxattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3228
Inline: False
```
**Symbols:**

```
ffffffff8144cd00-ffffffff8144ce3e: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff8144f21b-ffffffff8144f23f: selinux_inode_post_setxattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3228
Inline: False
```
**Symbols:**

```
ffffffff81458370-ffffffff814584ae: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff8145a88b-ffffffff8145a8af: selinux_inode_post_setxattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void selinux_inode_post_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3228
Inline: False
```
**Symbols:**

```
ffffffff8146de70-ffffffff8146dfac: selinux_inode_post_setxattr (STB_LOCAL)
ffffffff8147206d-ffffffff81472091: selinux_inode_post_setxattr.cold (STB_LOCAL)
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
