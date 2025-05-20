# Function: <code>alloc_empty_file</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/file_table.c (ffffffff812b0bc3)
Location: fs/file_table.c:133
Inline: True
Direct callers:
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812b0f3f-ffffffff812b0f73: alloc_empty_file.cold.9 (STB_LOCAL)
ffffffff812b0b20-ffffffff812b0be7: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/file_table.c (ffffffff812cd8d5)
Location: fs/file_table.c:134
Inline: True
Direct callers:
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812cd8d5-ffffffff812cd909: alloc_empty_file.cold (STB_LOCAL)
ffffffff812cd4b0-ffffffff812cd562: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/file_table.c (ffffffff812df2f5)
Location: fs/file_table.c:134
Inline: True
Direct callers:
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812df2f5-ffffffff812df329: alloc_empty_file.cold (STB_LOCAL)
ffffffff812deed0-ffffffff812def82: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file_table.c (0)
Location: fs/file_table.c:134
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81316155-ffffffff81316182: alloc_empty_file.cold (STB_LOCAL)
ffffffff81315a50-ffffffff81315b05: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file_table.c (0)
Location: fs/file_table.c:133
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81bea4fa-ffffffff81bea527: alloc_empty_file.cold (STB_LOCAL)
ffffffff81320f80-ffffffff81321035: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file_table.c (0)
Location: fs/file_table.c:133
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81bdc534-ffffffff81bdc563: alloc_empty_file.cold (STB_LOCAL)
ffffffff81327370-ffffffff81327425: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file_table.c (0)
Location: fs/file_table.c:133
Inline: False
Direct callers:
  - fs/open.c:dentry_open
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81cc382c-ffffffff81cc385b: alloc_empty_file.cold (STB_LOCAL)
ffffffff81374640-ffffffff813746f5: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/file_table.c (0)
Location: fs/file_table.c:170
Inline: False
Direct callers:
  - fs/open.c:dentry_create
  - fs/open.c:dentry_open
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81e75f80-ffffffff81e75fa8: alloc_empty_file.cold (STB_LOCAL)
ffffffff813f3a50-ffffffff813f3b0b: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff8147c870)
Location: fs/file_table.c:170
Inline: False
Direct callers:
  - fs/open.c:dentry_create
  - fs/open.c:dentry_open
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8147c870-ffffffff8147c94c: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff814b14b0)
Location: fs/file_table.c:188
Inline: False
Direct callers:
  - fs/open.c:dentry_create
  - fs/open.c:dentry_open
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff814b14b0-ffffffff814b15d4: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff814e2c80)
Location: fs/file_table.c:185
Inline: False
Direct callers:
  - fs/open.c:dentry_create
  - fs/open.c:dentry_open
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff814e2c80-ffffffff814e2da4: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffff800010385318)
Location: fs/file_table.c:134
Inline: True
Direct callers:
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffff800010385318-ffff800010385418: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c056e43c)
Location: fs/file_table.c:134
Inline: True
Direct callers:
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
c056e43c-c056e57c: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c00000000047b6f0)
Location: fs/file_table.c:134
Inline: True
Direct callers:
  - fs/open.c:dentry_open
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
c00000000047b6f0-c00000000047b858: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffe000258378)
Location: fs/file_table.c:134
Inline: True
Direct callers:
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffe000258378-ffffffe000258466: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/file_table.c (ffffffff812d78d5)
Location: fs/file_table.c:134
Inline: True
Direct callers:
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812d78d5-ffffffff812d7909: alloc_empty_file.cold (STB_LOCAL)
ffffffff812d74b0-ffffffff812d7562: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/file_table.c (ffffffff812c8555)
Location: fs/file_table.c:134
Inline: True
Direct callers:
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812c8555-ffffffff812c8589: alloc_empty_file.cold (STB_LOCAL)
ffffffff812c8130-ffffffff812c81e2: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/file_table.c (ffffffff812d56e5)
Location: fs/file_table.c:134
Inline: True
Direct callers:
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812d56e5-ffffffff812d5719: alloc_empty_file.cold (STB_LOCAL)
ffffffff812d52c0-ffffffff812d5372: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct file *alloc_empty_file(int flags, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/file_table.c (ffffffff812e6535)
Location: fs/file_table.c:134
Inline: True
Direct callers:
  - fs/file_table.c:alloc_file
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812e6535-ffffffff812e6569: alloc_empty_file.cold (STB_LOCAL)
ffffffff812e6110-ffffffff812e61c2: alloc_empty_file (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
