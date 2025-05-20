# Function: <code>common_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int common_perm(const char *op, struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813853b0)
Location: security/apparmor/lsm.c:189
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
```
**Symbols:**

```
ffffffff813853b0-ffffffff8138557c: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813bfac0)
Location: security/apparmor/lsm.c:189
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff813bfac0-ffffffff813bfccc: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813d6e60)
Location: security/apparmor/lsm.c:189
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff813d6e60-ffffffff813d706c: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813e84c0)
Location: security/apparmor/lsm.c:171
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff813e84c0-ffffffff813e85b9: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8140f8e0)
Location: security/apparmor/lsm.c:171
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff8140f8e0-ffffffff8140fa05: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814417c0)
Location: security/apparmor/lsm.c:200
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff814417c0-ffffffff814418d2: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8145e850)
Location: security/apparmor/lsm.c:195
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff8145e850-ffffffff8145e978: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148bd50)
Location: security/apparmor/lsm.c:191
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff8148bd50-ffffffff8148be59: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814a5c10)
Location: security/apparmor/lsm.c:191
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff814a5c10-ffffffff814a5d19: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81502c5c)
Location: security/apparmor/lsm.c:204
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8151f81c)
Location: security/apparmor/lsm.c:204
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81525e69)
Location: security/apparmor/lsm.c:204
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81584299)
Location: security/apparmor/lsm.c:204
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81624fbd)
Location: security/apparmor/lsm.c:215
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816d903d)
Location: security/apparmor/lsm.c:233
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff817127d9)
Location: security/apparmor/lsm.c:233
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8175087c)
Location: security/apparmor/lsm.c:230
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_path_symlink
  - security/apparmor/lsm.c:apparmor_path_mknod
  - security/apparmor/lsm.c:apparmor_path_rmdir
  - security/apparmor/lsm.c:apparmor_path_mkdir
  - security/apparmor/lsm.c:apparmor_path_unlink
  - security/apparmor/lsm.c:common_perm_cond
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
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffff80001059c0a0)
Location: security/apparmor/lsm.c:191
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffff80001059c0a0-ffff80001059c1dc: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c074d5f4)
Location: security/apparmor/lsm.c:191
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
c074d5f4-c074d734: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c000000000714020)
Location: security/apparmor/lsm.c:191
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
c000000000714020-c0000000007141a0: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffe0003e7d24)
Location: security/apparmor/lsm.c:191
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffe0003e7d24-ffffffe0003e7dfa: common_perm (STB_LOCAL)
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
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149e1f0)
Location: security/apparmor/lsm.c:191
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff8149e1f0-ffffffff8149e2f9: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148ec10)
Location: security/apparmor/lsm.c:191
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff8148ec10-ffffffff8148ed19: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149a290)
Location: security/apparmor/lsm.c:191
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff8149a290-ffffffff8149a399: common_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int common_perm(const char *op, const struct path *path, u32 mask, struct path_cond *cond);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814b23c0)
Location: security/apparmor/lsm.c:191
Inline: False
Direct callers:
  - security/apparmor/lsm.c:common_perm_cond
```
**Symbols:**

```
ffffffff814b23c0-ffffffff814b2517: common_perm (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
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
