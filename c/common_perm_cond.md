# Function: <code>common_perm_cond</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813855b5)
Location: security/apparmor/lsm.c:203
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_truncate
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813bfcd0)
Location: security/apparmor/lsm.c:203
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff813bfcd0-ffffffff813bfd32: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813d7070)
Location: security/apparmor/lsm.c:203
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff813d7070-ffffffff813d70d2: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813e85c0)
Location: security/apparmor/lsm.c:193
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff813e85c0-ffffffff813e8622: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8140fa10)
Location: security/apparmor/lsm.c:193
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff8140fa10-ffffffff8140fa72: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814418e0)
Location: security/apparmor/lsm.c:222
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff814418e0-ffffffff81441942: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8145e980)
Location: security/apparmor/lsm.c:217
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff8145e980-ffffffff8145e9e2: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148be60)
Location: security/apparmor/lsm.c:213
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff8148be60-ffffffff8148bec2: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814a5d20)
Location: security/apparmor/lsm.c:213
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff814a5d20-ffffffff814a5d82: common_perm_cond (STB_LOCAL)
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
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:226
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
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
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:226
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81526490)
Location: security/apparmor/lsm.c:226
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff81526490-ffffffff81526643: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81584720)
Location: security/apparmor/lsm.c:226
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff81584720-ffffffff815848d3: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816257a0)
Location: security/apparmor/lsm.c:237
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff816257a0-ffffffff816259ac: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816d99c0)
Location: security/apparmor/lsm.c:256
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_file_truncate
```
**Symbols:**

```
ffffffff816d99c0-ffffffff816d9be6: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81712cf0)
Location: security/apparmor/lsm.c:256
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_file_truncate
```
**Symbols:**

```
ffffffff81712cf0-ffffffff81712edf: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff817509d0)
Location: security/apparmor/lsm.c:253
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_file_truncate
```
**Symbols:**

```
ffffffff817509d0-ffffffff81750bc4: common_perm_cond (STB_LOCAL)
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
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffff80001059c1e0)
Location: security/apparmor/lsm.c:213
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffff80001059c1e0-ffff80001059c27c: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c074d734)
Location: security/apparmor/lsm.c:213
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
c074d734-c074d7b8: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (c0000000007141a0)
Location: security/apparmor/lsm.c:213
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
c0000000007141a0-c000000000714240: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffe0003e7dfa)
Location: security/apparmor/lsm.c:213
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffe0003e7dfa-ffffffe0003e7e58: common_perm_cond (STB_LOCAL)
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
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149e300)
Location: security/apparmor/lsm.c:213
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff8149e300-ffffffff8149e362: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148ed20)
Location: security/apparmor/lsm.c:213
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff8148ed20-ffffffff8148ed82: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149a3a0)
Location: security/apparmor/lsm.c:213
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff8149a3a0-ffffffff8149a402: common_perm_cond (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int common_perm_cond(const char *op, const struct path *path, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814b2520)
Location: security/apparmor/lsm.c:213
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_inode_getattr
  - security/apparmor/lsm.c:apparmor_path_chown
  - security/apparmor/lsm.c:apparmor_path_chmod
  - security/apparmor/lsm.c:apparmor_path_truncate
```
**Symbols:**

```
ffffffff814b2520-ffffffff814b2582: common_perm_cond (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
