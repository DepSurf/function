# Function: <code>fuse_readdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81313430)
Location: fs/fuse/dir.c:1312
Inline: False
```
**Symbols:**

```
ffffffff81313430-ffffffff81313b09: fuse_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813479b0)
Location: fs/fuse/dir.c:1313
Inline: False
```
**Symbols:**

```
ffffffff813479b0-ffffffff81348172: fuse_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135d300)
Location: fs/fuse/dir.c:1329
Inline: False
```
**Symbols:**

```
ffffffff8135d300-ffffffff8135dad2: fuse_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81371ce0)
Location: fs/fuse/dir.c:1329
Inline: False
```
**Symbols:**

```
ffffffff81371ce0-ffffffff813725b4: fuse_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813969e0)
Location: fs/fuse/dir.c:1326
Inline: False
```
**Symbols:**

```
ffffffff813969e0-ffffffff813972c2: fuse_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c5b90)
Location: fs/fuse/dir.c:1335
Inline: False
```
**Symbols:**

```
ffffffff813c5b90-ffffffff813c6474: fuse_readdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff813e9f20)
Location: fs/fuse/readdir.c:549
Inline: False
```
**Symbols:**

```
ffffffff813e9f20-ffffffff813ead89: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/readdir.c (0)
Location: fs/fuse/readdir.c:549
Inline: False
```
**Symbols:**

```
ffffffff81416df5-ffffffff81416e8f: fuse_readdir.cold (STB_LOCAL)
ffffffff814167e0-ffffffff81416dda: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81430700)
Location: fs/fuse/readdir.c:565
Inline: False
```
**Symbols:**

```
ffffffff81430700-ffffffff81430d67: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81480b00)
Location: fs/fuse/readdir.c:565
Inline: False
```
**Symbols:**

```
ffffffff81480b00-ffffffff81480b7e: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8149c1e0)
Location: fs/fuse/readdir.c:565
Inline: False
```
**Symbols:**

```
ffffffff8149c1e0-ffffffff8149c26b: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff814a1490)
Location: fs/fuse/readdir.c:568
Inline: False
```
**Symbols:**

```
ffffffff814a1490-ffffffff814a151b: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff814f9540)
Location: fs/fuse/readdir.c:568
Inline: False
```
**Symbols:**

```
ffffffff814f9540-ffffffff814f95cb: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81589740)
Location: fs/fuse/readdir.c:568
Inline: False
```
**Symbols:**

```
ffffffff81589740-ffffffff815897da: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8162fd40)
Location: fs/fuse/readdir.c:576
Inline: False
```
**Symbols:**

```
ffffffff8162fd40-ffffffff8162fdda: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81667f40)
Location: fs/fuse/readdir.c:576
Inline: False
```
**Symbols:**

```
ffffffff81667f40-ffffffff81667fdd: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff816a2240)
Location: fs/fuse/readdir.c:586
Inline: False
```
**Symbols:**

```
ffffffff816a2240-ffffffff816a22dd: fuse_readdir (STB_GLOBAL)
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
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffff8000105151f8)
Location: fs/fuse/readdir.c:565
Inline: False
```
**Symbols:**

```
ffff8000105151f8-ffff8000105157a4: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (c06d0674)
Location: fs/fuse/readdir.c:565
Inline: False
```
**Symbols:**

```
c06d0674-c06d0700: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (c00000000065e150)
Location: fs/fuse/readdir.c:565
Inline: False
```
**Symbols:**

```
c00000000065e150-c00000000065e228: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffe00037eb6e)
Location: fs/fuse/readdir.c:565
Inline: False
```
**Symbols:**

```
ffffffe00037eb6e-ffffffe00037f134: fuse_readdir (STB_GLOBAL)
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
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81428ce0)
Location: fs/fuse/readdir.c:565
Inline: False
```
**Symbols:**

```
ffffffff81428ce0-ffffffff81429347: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81419760)
Location: fs/fuse/readdir.c:565
Inline: False
```
**Symbols:**

```
ffffffff81419760-ffffffff81419dc7: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81424e80)
Location: fs/fuse/readdir.c:565
Inline: False
```
**Symbols:**

```
ffffffff81424e80-ffffffff814254e7: fuse_readdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fuse_readdir(struct file *file, struct dir_context *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8143bd10)
Location: fs/fuse/readdir.c:565
Inline: False
```
**Symbols:**

```
ffffffff8143bd10-ffffffff8143c3ad: fuse_readdir (STB_GLOBAL)
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
