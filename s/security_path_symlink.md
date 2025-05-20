# Function: <code>security_path_symlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_path_symlink(struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133c0f0)
Location: security/security.c:446
Inline: False
Direct callers:
  - fs/namei.c:SyS_symlink
```
**Symbols:**

```
ffffffff8133c0f0-ffffffff8133c15c: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813716c0)
Location: security/security.c:447
Inline: False
Direct callers:
  - fs/namei.c:SyS_symlink
```
**Symbols:**

```
ffffffff813716c0-ffffffff8137172c: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81387ff0)
Location: security/security.c:456
Inline: False
Direct callers:
  - fs/namei.c:SyS_symlink
```
**Symbols:**

```
ffffffff81387ff0-ffffffff8138805c: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139cf20)
Location: security/security.c:1061
Inline: False
Direct callers:
  - fs/namei.c:SyS_symlink
```
**Symbols:**

```
ffffffff8139cf20-ffffffff8139cf8c: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c2790)
Location: security/security.c:1010
Inline: False
Direct callers:
  - fs/namei.c:SyS_symlink
```
**Symbols:**

```
ffffffff813c2790-ffffffff813c2802: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2890)
Location: security/security.c:552
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
```
**Symbols:**

```
ffffffff813f2890-ffffffff813f28ef: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140dd30)
Location: security/security.c:1073
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
```
**Symbols:**

```
ffffffff8140dd30-ffffffff8140dd8f: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143bbf0)
Location: security/security.c:1087
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
```
**Symbols:**

```
ffffffff8143bbf0-ffffffff8143bc5a: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455930)
Location: security/security.c:1127
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
```
**Symbols:**

```
ffffffff81455930-ffffffff8145598f: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8160)
Location: security/security.c:1275
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
```
**Symbols:**

```
ffffffff814a8160-ffffffff814a81bf: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c56e0)
Location: security/security.c:1277
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/init.c:init_symlink
```
**Symbols:**

```
ffffffff814c56e0-ffffffff814c573f: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cd290)
Location: security/security.c:1329
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/init.c:init_symlink
```
**Symbols:**

```
ffffffff814cd290-ffffffff814cd2ef: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815248d0)
Location: security/security.c:1330
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/init.c:init_symlink
```
**Symbols:**

```
ffffffff815248d0-ffffffff8152492f: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815ba8c0)
Location: security/security.c:1349
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/init.c:init_symlink
```
**Symbols:**

```
ffffffff815ba8c0-ffffffff815ba948: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816662c0)
Location: security/security.c:1347
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/init.c:init_symlink
```
**Symbols:**

```
ffffffff816662c0-ffffffff81666348: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169e8b0)
Location: security/security.c:1895
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/init.c:init_symlink
```
**Symbols:**

```
ffffffff8169e8b0-ffffffff8169e938: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816db200)
Location: security/security.c:1968
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/init.c:init_symlink
```
**Symbols:**

```
ffffffff816db200-ffffffff816db288: security_path_symlink (STB_GLOBAL)
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
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010540eb0)
Location: security/security.c:1127
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
```
**Symbols:**

```
ffff800010540eb0-ffff800010540f24: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f6ef0)
Location: security/security.c:1127
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
```
**Symbols:**

```
c06f6ef0-c06f6f68: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000693150)
Location: security/security.c:1127
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
```
**Symbols:**

```
c000000000693150-c000000000693218: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039dd44)
Location: security/security.c:1127
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
```
**Symbols:**

```
ffffffe00039dd44-ffffffe00039dd9e: security_path_symlink (STB_GLOBAL)
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
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144df10)
Location: security/security.c:1127
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
```
**Symbols:**

```
ffffffff8144df10-ffffffff8144df6f: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e960)
Location: security/security.c:1127
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
```
**Symbols:**

```
ffffffff8143e960-ffffffff8143e9bf: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81449fb0)
Location: security/security.c:1127
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
```
**Symbols:**

```
ffffffff81449fb0-ffffffff8144a00f: security_path_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_path_symlink(const struct path *dir, struct dentry *dentry, const char *old_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461380)
Location: security/security.c:1127
Inline: False
Direct callers:
  - fs/namei.c:do_symlinkat
```
**Symbols:**

```
ffffffff81461380-ffffffff814613df: security_path_symlink (STB_GLOBAL)
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
<code>struct path *dir</code> ➡️ <code>const struct path *dir</code>
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
