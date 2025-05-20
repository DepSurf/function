# Function: <code>fput_many</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fput_many(struct file *file, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812cd830)
Location: fs/file_table.c:335
Inline: True
Direct callers:
  - fs/file_table.c:fput
  - fs/io_uring.c:io_file_put
```
**Symbols:**

```
ffffffff812cd830-ffffffff812cd8ba: fput_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fput_many(struct file *file, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812df250)
Location: fs/file_table.c:335
Inline: True
Direct callers:
  - fs/file_table.c:fput
  - fs/io_uring.c:io_file_put
```
**Symbols:**

```
ffffffff812df250-ffffffff812df2da: fput_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fput_many(struct file *file, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff813160b0)
Location: fs/file_table.c:336
Inline: True
Direct callers:
  - fs/file_table.c:fput
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_file_get
```
**Symbols:**

```
ffffffff813160b0-ffffffff8131613e: fput_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fput_many(struct file *file, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/file_table.c (ffffffff813215d5)
Location: fs/file_table.c:335
Inline: True
Inline callers:
  - fs/file_table.c:fput
Direct callers:
  - fs/file_table.c:fput
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_file_get
```
**Symbols:**

```
ffffffff81321250-ffffffff813212d4: fput_many.part.0 (STB_LOCAL)
ffffffff81321690-ffffffff813216aa: fput_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fput_many(struct file *file, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff813276b0)
Location: fs/file_table.c:334
Inline: True
Direct callers:
  - fs/file_table.c:fput
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_file_get
```
**Symbols:**

```
ffffffff813276b0-ffffffff8132773e: fput_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fput_many(struct file *file, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff81374cb0)
Location: fs/file_table.c:335
Inline: True
Direct callers:
  - fs/file_table.c:fput
  - fs/file.c:__fget_files
```
**Symbols:**

```
ffffffff81374cb0-ffffffff81374d3e: fput_many (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void fput_many(struct file *file, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffff800010385ad0)
Location: fs/file_table.c:335
Inline: True
Direct callers:
  - fs/file_table.c:fput
  - fs/io_uring.c:io_file_put
```
**Symbols:**

```
ffff800010385ad0-ffff800010385ba8: fput_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fput_many(struct file *file, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c056e958)
Location: fs/file_table.c:335
Inline: True
Direct callers:
  - fs/file_table.c:fput
  - fs/io_uring.c:io_file_put
```
**Symbols:**

```
c056e958-c056ea30: fput_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fput_many(struct file *file, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (c00000000047bca0)
Location: fs/file_table.c:335
Inline: True
Direct callers:
  - fs/file_table.c:fput
  - fs/io_uring.c:io_file_put
```
**Symbols:**

```
c00000000047bca0-c00000000047bd98: fput_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fput_many(struct file *file, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffe000258754)
Location: fs/file_table.c:335
Inline: True
Direct callers:
  - fs/file_table.c:fput
  - fs/io_uring.c:io_file_put
```
**Symbols:**

```
ffffffe000258754-ffffffe0002587fe: fput_many (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void fput_many(struct file *file, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812d7830)
Location: fs/file_table.c:335
Inline: True
Direct callers:
  - fs/file_table.c:fput
  - fs/io_uring.c:io_file_put
```
**Symbols:**

```
ffffffff812d7830-ffffffff812d78ba: fput_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fput_many(struct file *file, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812c84b0)
Location: fs/file_table.c:335
Inline: True
Direct callers:
  - fs/file_table.c:fput
  - fs/io_uring.c:io_file_put
```
**Symbols:**

```
ffffffff812c84b0-ffffffff812c853a: fput_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fput_many(struct file *file, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812d5640)
Location: fs/file_table.c:335
Inline: True
Direct callers:
  - fs/file_table.c:fput
  - fs/io_uring.c:io_file_put
```
**Symbols:**

```
ffffffff812d5640-ffffffff812d56ca: fput_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fput_many(struct file *file, unsigned int refs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/file_table.c (ffffffff812e6490)
Location: fs/file_table.c:335
Inline: True
Direct callers:
  - fs/file_table.c:fput
  - fs/io_uring.c:io_file_put
```
**Symbols:**

```
ffffffff812e6490-ffffffff812e651a: fput_many (STB_GLOBAL)
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
