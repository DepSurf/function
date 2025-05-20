# Function: <code>fuse_readdir_cached</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff813e9f89)
Location: fs/fuse/readdir.c:415
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8141682f)
Location: fs/fuse/readdir.c:415
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8143074f)
Location: fs/fuse/readdir.c:431
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_readdir_cached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81480330)
Location: fs/fuse/readdir.c:431
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81480330-ffffffff81480774: fuse_readdir_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_readdir_cached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8149ba10)
Location: fs/fuse/readdir.c:431
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff8149ba10-ffffffff8149be51: fuse_readdir_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_readdir_cached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff814a0b30)
Location: fs/fuse/readdir.c:434
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff814a0b30-ffffffff814a0f6b: fuse_readdir_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fuse_readdir_cached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/readdir.c (0)
Location: fs/fuse/readdir.c:434
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff814f8a00-ffffffff814f9019: fuse_readdir_cached (STB_LOCAL)
ffffffff81cd2365-ffffffff81cd237a: fuse_readdir_cached.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fuse_readdir_cached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/readdir.c (0)
Location: fs/fuse/readdir.c:434
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81588fe0-ffffffff81589736: fuse_readdir_cached (STB_LOCAL)
ffffffff81e85499-ffffffff81e854ad: fuse_readdir_cached.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fuse_readdir_cached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/readdir.c (0)
Location: fs/fuse/readdir.c:436
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff8162f4f0-ffffffff8162fd2a: fuse_readdir_cached (STB_LOCAL)
ffffffff82072943-ffffffff82072957: fuse_readdir_cached.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fuse_readdir_cached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/readdir.c (0)
Location: fs/fuse/readdir.c:436
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81667760-ffffffff81667f24: fuse_readdir_cached (STB_LOCAL)
ffffffff820f25a7-ffffffff820f25bb: fuse_readdir_cached.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fuse_readdir_cached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/readdir.c (0)
Location: fs/fuse/readdir.c:444
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff816a1ab0-ffffffff816a2221: fuse_readdir_cached (STB_LOCAL)
ffffffff821cf842-ffffffff821cf856: fuse_readdir_cached.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffff800010515278)
Location: fs/fuse/readdir.c:431
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_readdir_cached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (c06cfee0)
Location: fs/fuse/readdir.c:431
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
c06cfee0-c06d0674: fuse_readdir_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_readdir_cached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (c00000000065d9c0)
Location: fs/fuse/readdir.c:431
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
c00000000065d9c0-c00000000065e144: fuse_readdir_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffe00037ebfa)
Location: fs/fuse/readdir.c:431
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81428d2f)
Location: fs/fuse/readdir.c:431
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff814197af)
Location: fs/fuse/readdir.c:431
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81424ecf)
Location: fs/fuse/readdir.c:431
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8143bd64)
Location: fs/fuse/readdir.c:431
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
