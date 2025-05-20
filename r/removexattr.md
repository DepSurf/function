# Function: <code>removexattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81232200)
Location: fs/xattr.c:611
Inline: False
Direct callers:
  - fs/xattr.c:path_removexattr
  - fs/xattr.c:SyS_fremovexattr
```
**Symbols:**

```
ffffffff81232200-ffffffff81232279: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125af10)
Location: fs/xattr.c:603
Inline: False
Direct callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff8125af10-ffffffff8125af89: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126e4b0)
Location: fs/xattr.c:708
Inline: False
Direct callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff8126e4b0-ffffffff8126e529: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127bcb0)
Location: fs/xattr.c:705
Inline: False
Direct callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff8127bcb0-ffffffff8127bd29: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129e750)
Location: fs/xattr.c:706
Inline: False
Direct callers:
  - fs/xattr.c:SyS_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff8129e750-ffffffff8129e7c9: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c5200)
Location: fs/xattr.c:704
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff812c5200-ffffffff812c5279: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812da400)
Location: fs/xattr.c:703
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff812da400-ffffffff812da479: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f89e0)
Location: fs/xattr.c:704
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff812f89e0-ffffffff812f8a5b: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8130a610)
Location: fs/xattr.c:704
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff8130a610-ffffffff8130a68b: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81343610)
Location: fs/xattr.c:774
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff81343610-ffffffff81343686: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8134f7a0)
Location: fs/xattr.c:806
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff8134f7a0-ffffffff8134f816: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int removexattr(struct user_namespace *mnt_userns, struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813562b0)
Location: fs/xattr.c:833
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff813562b0-ffffffff81356338: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int removexattr(struct user_namespace *mnt_userns, struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a47e0)
Location: fs/xattr.c:834
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff813a47e0-ffffffff813a4868: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int removexattr(struct user_namespace *mnt_userns, struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81428810)
Location: fs/xattr.c:886
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff81428810-ffffffff814288b0: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int removexattr(struct mnt_idmap *idmap, struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b5d50)
Location: fs/xattr.c:906
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff814b5d50-ffffffff814b5ea7: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int removexattr(struct mnt_idmap *idmap, struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814ea5a0)
Location: fs/xattr.c:903
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff814ea5a0-ffffffff814ea6db: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int removexattr(struct mnt_idmap *idmap, struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151e440)
Location: fs/xattr.c:903
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff8151e440-ffffffff8151e57b: removexattr (STB_LOCAL)
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
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103be060)
Location: fs/xattr.c:704
Inline: False
Direct callers:
  - fs/xattr.c:__arm64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffff8000103be060-ffff8000103be0f0: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059b8a4)
Location: fs/xattr.c:704
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
c059b8a4-c059b924: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bcb40)
Location: fs/xattr.c:704
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
c0000000004bcb40-c0000000004bcbe0: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027f494)
Location: fs/xattr.c:704
Inline: False
Direct callers:
  - fs/xattr.c:__se_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffe00027f494-ffffffe00027f4ee: removexattr (STB_LOCAL)
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
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81302bf0)
Location: fs/xattr.c:704
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff81302bf0-ffffffff81302c6b: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f3810)
Location: fs/xattr.c:704
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff812f3810-ffffffff812f388b: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813009e0)
Location: fs/xattr.c:704
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff813009e0-ffffffff81300a5b: removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int removexattr(struct dentry *d, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81311d20)
Location: fs/xattr.c:704
Inline: False
Direct callers:
  - fs/xattr.c:__ia32_sys_fremovexattr
  - fs/xattr.c:__x64_sys_fremovexattr
  - fs/xattr.c:path_removexattr
```
**Symbols:**

```
ffffffff81311d20-ffffffff81311d9b: removexattr (STB_LOCAL)
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
<code>d, name</code> ➡️ <code>mnt_userns, d, name</code>
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
