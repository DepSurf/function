# Function: <code>parse_dirplusfile</code>

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
In fs/fuse/dir.c (ffffffff8131365d)
Location: fs/fuse/dir.c:1268
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81347bd5)
Location: fs/fuse/dir.c:1269
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135d51b)
Location: fs/fuse/dir.c:1285
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81371f2c)
Location: fs/fuse/dir.c:1285
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81396c32)
Location: fs/fuse/dir.c:1281
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c5edf)
Location: fs/fuse/dir.c:1290
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff813ea490)
Location: fs/fuse/readdir.c:252
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
In fs/fuse/readdir.c (ffffffff814165aa)
Location: fs/fuse/readdir.c:252
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
In fs/fuse/readdir.c (ffffffff814304bd)
Location: fs/fuse/readdir.c:273
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_dirplusfile(char *buf, size_t nbytes, struct file *file, struct dir_context *ctx, u64 attr_version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81480200)
Location: fs/fuse/readdir.c:273
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81480200-ffffffff81480330: parse_dirplusfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_dirplusfile(char *buf, size_t nbytes, struct file *file, struct dir_context *ctx, u64 attr_version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8149b8e0)
Location: fs/fuse/readdir.c:273
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8149b8e0-ffffffff8149ba10: parse_dirplusfile (STB_LOCAL)
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
In fs/fuse/readdir.c (ffffffff814a11ca)
Location: fs/fuse/readdir.c:276
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
In fs/fuse/readdir.c (ffffffff814f927a)
Location: fs/fuse/readdir.c:276
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
In fs/fuse/readdir.c (ffffffff81588d23)
Location: fs/fuse/readdir.c:276
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
In fs/fuse/readdir.c (ffffffff8162f220)
Location: fs/fuse/readdir.c:278
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
In fs/fuse/readdir.c (ffffffff81667483)
Location: fs/fuse/readdir.c:278
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
In fs/fuse/readdir.c (ffffffff816a17d3)
Location: fs/fuse/readdir.c:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
int parse_dirplusfile(char *buf, size_t nbytes, struct file *file, struct dir_context *ctx, u64 attr_version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffff8000105149b8)
Location: fs/fuse/readdir.c:273
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffff8000105149b8-ffff800010514e0c: parse_dirplusfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int parse_dirplusfile(char *buf, size_t nbytes, struct file *file, struct dir_context *ctx, u64 attr_version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (c06cf6e8)
Location: fs/fuse/readdir.c:273
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
c06cf6e8-c06cfb50: parse_dirplusfile (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int parse_dirplusfile(char *buf, size_t nbytes, struct file *file, struct dir_context *ctx, u64 attr_version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (c00000000065cf40)
Location: fs/fuse/readdir.c:273
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
c00000000065cf40-c00000000065d4dc: parse_dirplusfile (STB_LOCAL)
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
In fs/fuse/readdir.c (ffffffe00037e6c0)
Location: fs/fuse/readdir.c:273
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
In fs/fuse/readdir.c (ffffffff81428a9d)
Location: fs/fuse/readdir.c:273
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
In fs/fuse/readdir.c (ffffffff8141951d)
Location: fs/fuse/readdir.c:273
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
In fs/fuse/readdir.c (ffffffff81424c3d)
Location: fs/fuse/readdir.c:273
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
In fs/fuse/readdir.c (ffffffff8143bacd)
Location: fs/fuse/readdir.c:273
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
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
</ul>
<b>Arch</b>
<ul>
</ul>
