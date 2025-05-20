# Function: <code>fuse_readdir_uncached</code>

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
In fs/fuse/readdir.c (ffffffff813ea06d)
Location: fs/fuse/readdir.c:296
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81416380)
Location: fs/fuse/readdir.c:296
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81416380-ffffffff814167de: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81430260)
Location: fs/fuse/readdir.c:317
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81430260-ffffffff814306fc: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81480780)
Location: fs/fuse/readdir.c:317
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81480780-ffffffff81480af4: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8149be60)
Location: fs/fuse/readdir.c:317
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff8149be60-ffffffff8149c1da: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff814a0f70)
Location: fs/fuse/readdir.c:320
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff814a0f70-ffffffff814a1481: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff814f9020)
Location: fs/fuse/readdir.c:320
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff814f9020-ffffffff814f9531: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81588ab0)
Location: fs/fuse/readdir.c:320
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81588ab0-ffffffff81588fe0: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8162efa0)
Location: fs/fuse/readdir.c:322
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff8162efa0-ffffffff8162f4da: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81667200)
Location: fs/fuse/readdir.c:322
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81667200-ffffffff81667741: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff816a1550)
Location: fs/fuse/readdir.c:330
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff816a1550-ffffffff816a1a91: fuse_readdir_uncached (STB_LOCAL)
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
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffff800010514e10)
Location: fs/fuse/readdir.c:317
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffff800010514e10-ffff8000105151f4: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (c06cfb50)
Location: fs/fuse/readdir.c:317
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
c06cfb50-c06cfee0: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (c00000000065d4e0)
Location: fs/fuse/readdir.c:317
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
c00000000065d4e0-c00000000065d9b4: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffe00037e4cc)
Location: fs/fuse/readdir.c:317
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffe00037e4cc-ffffffe00037eb6e: fuse_readdir_uncached (STB_LOCAL)
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
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81428840)
Location: fs/fuse/readdir.c:317
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff81428840-ffffffff81428cdc: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff814192c0)
Location: fs/fuse/readdir.c:317
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff814192c0-ffffffff8141975c: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff814249e0)
Location: fs/fuse/readdir.c:317
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff814249e0-ffffffff81424e7c: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fuse_readdir_uncached(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8143b870)
Location: fs/fuse/readdir.c:317
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff8143b870-ffffffff8143bd0b: fuse_readdir_uncached (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
