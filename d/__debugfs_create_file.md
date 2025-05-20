# Function: <code>__debugfs_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81352950)
Location: fs/debugfs/inode.c:303
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff81352950-ffffffff81352a5b: __debugfs_create_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81368c00)
Location: fs/debugfs/inode.c:303
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff81368c00-ffffffff81368d0b: __debugfs_create_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8137d290)
Location: fs/debugfs/inode.c:337
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff8137d290-ffffffff8137d39b: __debugfs_create_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813a21a0)
Location: fs/debugfs/inode.c:339
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff813a21a0-ffffffff813a22af: __debugfs_create_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813d13e0)
Location: fs/debugfs/inode.c:361
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff813d13e0-ffffffff813d1503: __debugfs_create_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813ebc90)
Location: fs/debugfs/inode.c:361
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff813ebc90-ffffffff813ebda8: __debugfs_create_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:371
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff81417d80-ffffffff81417e9b: __debugfs_create_file (STB_LOCAL)
ffffffff81418042-ffffffff81418061: __debugfs_create_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:373
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff81431c40-ffffffff81431d5b: __debugfs_create_file (STB_LOCAL)
ffffffff81431f02-ffffffff81431f21: __debugfs_create_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:372
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff81481540-ffffffff81481677: __debugfs_create_file (STB_LOCAL)
ffffffff81481b3a-ffffffff81481b59: __debugfs_create_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:382
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff8149f030-ffffffff8149f1c5: __debugfs_create_file (STB_LOCAL)
ffffffff81bef8ad-ffffffff81bef8cc: __debugfs_create_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:386
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff814a5010-ffffffff814a51a9: __debugfs_create_file (STB_LOCAL)
ffffffff81be1956-ffffffff81be1975: __debugfs_create_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:386
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff814fd140-ffffffff814fd2f0: __debugfs_create_file (STB_LOCAL)
ffffffff81cd2570-ffffffff81cd25b2: __debugfs_create_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:386
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff8158d980-ffffffff8158db32: __debugfs_create_file (STB_LOCAL)
ffffffff81e856b6-ffffffff81e856f9: __debugfs_create_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:409
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff81634070-ffffffff8163426d: __debugfs_create_file (STB_LOCAL)
ffffffff82072a1e-ffffffff82072a41: __debugfs_create_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:409
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff8166c380-ffffffff8166c57d: __debugfs_create_file (STB_LOCAL)
ffffffff820f2682-ffffffff820f26a5: __debugfs_create_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:416
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff816a6bd0-ffffffff816a6df6: __debugfs_create_file (STB_LOCAL)
ffffffff821cf947-ffffffff821cf964: __debugfs_create_file.cold (STB_LOCAL)
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
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffff8000105169a8)
Location: fs/debugfs/inode.c:373
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffff8000105169a8-ffff800010516ae0: __debugfs_create_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c06d1774)
Location: fs/debugfs/inode.c:373
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
c06d1774-c06d18ac: __debugfs_create_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c00000000065f9c0)
Location: fs/debugfs/inode.c:373
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
c00000000065f9c0-c00000000065fb6c: __debugfs_create_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffe0003800a2)
Location: fs/debugfs/inode.c:373
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffe0003800a2-ffffffe0003801ac: __debugfs_create_file (STB_LOCAL)
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
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:373
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff8142a220-ffffffff8142a33b: __debugfs_create_file (STB_LOCAL)
ffffffff8142a4e2-ffffffff8142a501: __debugfs_create_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:373
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff8141aca0-ffffffff8141adbb: __debugfs_create_file (STB_LOCAL)
ffffffff8141af62-ffffffff8141af81: __debugfs_create_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:373
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff814263c0-ffffffff814264db: __debugfs_create_file (STB_LOCAL)
ffffffff81426682-ffffffff814266a1: __debugfs_create_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dentry *__debugfs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *proxy_fops, const struct file_operations *real_fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:373
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_file_size
  - fs/debugfs/inode.c:debugfs_create_file_unsafe
```
**Symbols:**

```
ffffffff8143d280-ffffffff8143d39b: __debugfs_create_file (STB_LOCAL)
ffffffff8143d542-ffffffff8143d561: __debugfs_create_file.cold (STB_LOCAL)
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
