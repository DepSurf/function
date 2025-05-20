# Function: <code>__vfs_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120bf20)
Location: fs/read_write.c:485
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:vfs_write
```
**Symbols:**

```
ffffffff8120bf20-ffffffff8120bf51: __vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812325a0)
Location: fs/read_write.c:506
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
ffffffff812325a0-ffffffff812325d1: __vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81244f10)
Location: fs/read_write.c:506
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
ffffffff81244f10-ffffffff81244f41: __vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8124ff80)
Location: fs/read_write.c:464
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
ffffffff8124ff80-ffffffff8124ffb1: __vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81273db0)
Location: fs/read_write.c:477
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
ffffffff81273db0-ffffffff81273de4: __vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129ab00)
Location: fs/read_write.c:482
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
ffffffff8129ab00-ffffffff8129ab34: __vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812afa00)
Location: fs/read_write.c:482
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
ffffffff812afa00-ffffffff812afa34: __vfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c9560)
Location: fs/read_write.c:491
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
ffffffff812c9560-ffffffff812c9594: __vfs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812daf70)
Location: fs/read_write.c:491
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
ffffffff812daf70-ffffffff812dafa4: __vfs_write (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010380368)
Location: fs/read_write.c:491
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
ffff800010380368-ffff8000103803f4: __vfs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056a8d0)
Location: fs/read_write.c:491
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
c056a8d0-c056a918: __vfs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000476640)
Location: fs/read_write.c:491
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
c000000000476640-c0000000004766a8: __vfs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe0002560c4)
Location: fs/read_write.c:491
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
ffffffe0002560c4-ffffffe00025612e: __vfs_write (STB_LOCAL)
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
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d3550)
Location: fs/read_write.c:491
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
ffffffff812d3550-ffffffff812d3584: __vfs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c41d0)
Location: fs/read_write.c:491
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
ffffffff812c41d0-ffffffff812c4204: __vfs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d1360)
Location: fs/read_write.c:491
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
ffffffff812d1360-ffffffff812d1394: __vfs_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t __vfs_write(struct file *file, const char *p, size_t count, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e2190)
Location: fs/read_write.c:491
Inline: False
Direct callers:
  - fs/read_write.c:__kernel_write
```
**Symbols:**

```
ffffffff812e2190-ffffffff812e21c4: __vfs_write (STB_LOCAL)
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
