# Function: <code>setxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81232af0)
Location: fs/xattr.c:323
Inline: False
Direct callers:
  - fs/xattr.c:path_setxattr
  - fs/xattr.c:SyS_fsetxattr
```
**Symbols:**

```
ffffffff81232af0-ffffffff81232cfd: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125b2b0)
Location: fs/xattr.c:334
Inline: False
Direct callers:
  - fs/xattr.c:SyS_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff8125b2b0-ffffffff8125b430: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126e860)
Location: fs/xattr.c:439
Inline: False
Direct callers:
  - fs/xattr.c:SyS_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff8126e860-ffffffff8126e9e0: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127c040)
Location: fs/xattr.c:439
Inline: False
Direct callers:
  - fs/xattr.c:SyS_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff8127c040-ffffffff8127c1fc: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129eae0)
Location: fs/xattr.c:440
Inline: False
Direct callers:
  - fs/xattr.c:SyS_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff8129eae0-ffffffff8129ec9c: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c5760)
Location: fs/xattr.c:438
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff812c5760-ffffffff812c5948: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812da960)
Location: fs/xattr.c:437
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff812da960-ffffffff812dab48: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f8f60)
Location: fs/xattr.c:438
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff812f8f60-ffffffff812f91cb: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8130ab90)
Location: fs/xattr.c:438
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff8130ab90-ffffffff8130adfb: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81344360)
Location: fs/xattr.c:508
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff81344360-ffffffff813445cb: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813506d0)
Location: fs/xattr.c:546
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff813506d0-ffffffff813508bf: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int setxattr(struct user_namespace *mnt_userns, struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81357250)
Location: fs/xattr.c:567
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff81357250-ffffffff8135745d: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int setxattr(struct user_namespace *mnt_userns, struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a4e40)
Location: fs/xattr.c:568
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff813a4e40-ffffffff813a504d: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int setxattr(struct user_namespace *mnt_userns, struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81429590)
Location: fs/xattr.c:617
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff81429590-ffffffff8142966d: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int setxattr(struct mnt_idmap *idmap, struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b6550)
Location: fs/xattr.c:637
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff814b6550-ffffffff814b662d: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int setxattr(struct mnt_idmap *idmap, struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814eb260)
Location: fs/xattr.c:635
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff814eb260-ffffffff814eb33d: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int setxattr(struct mnt_idmap *idmap, struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151f100)
Location: fs/xattr.c:635
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff8151f100-ffffffff8151f1dd: setxattr (STB_LOCAL)
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
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103beea0)
Location: fs/xattr.c:438
Inline: False
Direct callers:
  - fs/xattr.c:__arm64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffff8000103beea0-ffff8000103bf22c: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059bc58)
Location: fs/xattr.c:438
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
c059bc58-c059be5c: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bd310)
Location: fs/xattr.c:438
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
c0000000004bd310-c0000000004bd690: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027f78e)
Location: fs/xattr.c:438
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffe00027f78e-ffffffe00027f93e: setxattr (STB_LOCAL)
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
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81303170)
Location: fs/xattr.c:438
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff81303170-ffffffff813033db: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f3d90)
Location: fs/xattr.c:438
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff812f3d90-ffffffff812f3ffb: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81300f60)
Location: fs/xattr.c:438
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff81300f60-ffffffff813011cb: setxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int setxattr(struct dentry *d, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813122a0)
Location: fs/xattr.c:438
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fsetxattr
  - fs/xattr.c:__x64_sys_fsetxattr
  - fs/xattr.c:path_setxattr
```
**Symbols:**

```
ffffffff813122a0-ffffffff8131250b: setxattr (STB_LOCAL)
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
<code>d, name, value, size, flags</code> ➡️ <code>mnt_userns, d, name, value, size, flags</code>
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
