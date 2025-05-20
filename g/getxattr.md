# Function: <code>getxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812325a0)
Location: fs/xattr.c:431
Inline: False
Direct callers:
  - fs/xattr.c:path_getxattr
  - fs/xattr.c:SyS_fgetxattr
```
**Symbols:**

```
ffffffff812325a0-ffffffff812327e7: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125ab50)
Location: fs/xattr.c:434
Inline: False
Direct callers:
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff8125ab50-ffffffff8125ad1d: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126e110)
Location: fs/xattr.c:539
Inline: False
Direct callers:
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff8126e110-ffffffff8126e2dd: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127b740)
Location: fs/xattr.c:542
Inline: False
Direct callers:
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff8127b740-ffffffff8127b8f8: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129e1e0)
Location: fs/xattr.c:543
Inline: False
Direct callers:
  - fs/xattr.c:SyS_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff8129e1e0-ffffffff8129e398: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c4930)
Location: fs/xattr.c:541
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff812c4930-ffffffff812c4aef: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812d9b30)
Location: fs/xattr.c:540
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff812d9b30-ffffffff812d9cef: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f80a0)
Location: fs/xattr.c:541
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff812f80a0-ffffffff812f82d4: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81309cc0)
Location: fs/xattr.c:541
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff81309cc0-ffffffff81309f0f: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81343e50)
Location: fs/xattr.c:611
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff81343e50-ffffffff8134409f: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813501c0)
Location: fs/xattr.c:643
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff813501c0-ffffffff8135040f: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t getxattr(struct user_namespace *mnt_userns, struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81356d10)
Location: fs/xattr.c:669
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff81356d10-ffffffff81356f6d: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t getxattr(struct user_namespace *mnt_userns, struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a57d0)
Location: fs/xattr.c:670
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff813a57d0-ffffffff813a5a2d: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t getxattr(struct user_namespace *mnt_userns, struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81429c10)
Location: fs/xattr.c:736
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff81429c10-ffffffff81429cf9: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t getxattr(struct mnt_idmap *idmap, struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b6c60)
Location: fs/xattr.c:756
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff814b6c60-ffffffff814b6d49: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t getxattr(struct mnt_idmap *idmap, struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814eb970)
Location: fs/xattr.c:753
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff814eb970-ffffffff814eba59: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t getxattr(struct mnt_idmap *idmap, struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151f810)
Location: fs/xattr.c:753
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff8151f810-ffffffff8151f8f9: getxattr (STB_LOCAL)
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
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103be3e0)
Location: fs/xattr.c:541
Inline: False
Direct callers:
  - fs/xattr.c:__arm64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffff8000103be3e0-ffff8000103be69c: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059b154)
Location: fs/xattr.c:541
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
c059b154-c059b31c: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bbfd0)
Location: fs/xattr.c:541
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
c0000000004bbfd0-c0000000004bc2a8: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027efea)
Location: fs/xattr.c:541
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffe00027efea-ffffffe00027f146: getxattr (STB_LOCAL)
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
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813022a0)
Location: fs/xattr.c:541
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff813022a0-ffffffff813024ef: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f2ec0)
Location: fs/xattr.c:541
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff812f2ec0-ffffffff812f310f: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81300090)
Location: fs/xattr.c:541
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff81300090-ffffffff813002df: getxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t getxattr(struct dentry *d, const char *name, void *value, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813113d0)
Location: fs/xattr.c:541
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fgetxattr
  - fs/xattr.c:__x64_sys_fgetxattr
  - fs/xattr.c:path_getxattr
```
**Symbols:**

```
ffffffff813113d0-ffffffff8131161f: getxattr (STB_LOCAL)
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
<code>d, name, value, size</code> ➡️ <code>mnt_userns, d, name, value, size</code>
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
