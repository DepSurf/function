# Function: <code>vfs_dup_fs_context</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8130a5f0)
Location: fs/fs_context.c:344
Inline: False
```
**Symbols:**

```
ffffffff8130a5f0-ffffffff8130a724: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8131d5b0)
Location: fs/fs_context.c:342
Inline: False
```
**Symbols:**

```
ffffffff8131d5b0-ffffffff8131d6e4: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81357660)
Location: fs/fs_context.c:316
Inline: False
```
**Symbols:**

```
ffffffff81357660-ffffffff81357805: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81364040)
Location: fs/fs_context.c:316
Inline: False
```
**Symbols:**

```
ffffffff81364040-ffffffff8136422d: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8136aac0)
Location: fs/fs_context.c:316
Inline: False
```
**Symbols:**

```
ffffffff8136aac0-ffffffff8136ac99: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813b9780)
Location: fs/fs_context.c:339
Inline: False
```
**Symbols:**

```
ffffffff813b9780-ffffffff813b9959: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8143f1f0)
Location: fs/fs_context.c:339
Inline: False
```
**Symbols:**

```
ffffffff8143f1f0-ffffffff8143f3ed: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff814cde80)
Location: fs/fs_context.c:339
Inline: True
```
**Symbols:**

```
ffffffff814cde80-ffffffff814ce07d: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81504080)
Location: fs/fs_context.c:360
Inline: True
```
**Symbols:**

```
ffffffff81504080-ffffffff8150427d: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81538d40)
Location: fs/fs_context.c:388
Inline: True
```
**Symbols:**

```
ffffffff81538d40-ffffffff81538f3f: vfs_dup_fs_context (STB_GLOBAL)
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
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffff8000103d59f0)
Location: fs/fs_context.c:342
Inline: False
```
**Symbols:**

```
ffff8000103d59f0-ffff8000103d5b50: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c05af3a0)
Location: fs/fs_context.c:342
Inline: False
```
**Symbols:**

```
c05af3a0-c05af4d4: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c0000000004d8280)
Location: fs/fs_context.c:342
Inline: False
```
**Symbols:**

```
c0000000004d8280-c0000000004d8454: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffe00028fb88)
Location: fs/fs_context.c:342
Inline: True
```
**Symbols:**

```
ffffffe00028fb88-ffffffe00028fc88: vfs_dup_fs_context (STB_GLOBAL)
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
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81315b90)
Location: fs/fs_context.c:342
Inline: False
```
**Symbols:**

```
ffffffff81315b90-ffffffff81315cc4: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81306780)
Location: fs/fs_context.c:342
Inline: False
```
**Symbols:**

```
ffffffff81306780-ffffffff813068b4: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81313980)
Location: fs/fs_context.c:342
Inline: False
```
**Symbols:**

```
ffffffff81313980-ffffffff81313ab4: vfs_dup_fs_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fs_context *vfs_dup_fs_context(struct fs_context *src_fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813251d0)
Location: fs/fs_context.c:342
Inline: False
```
**Symbols:**

```
ffffffff813251d0-ffffffff81325304: vfs_dup_fs_context (STB_GLOBAL)
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
