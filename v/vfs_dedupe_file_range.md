# Function: <code>vfs_dedupe_file_range</code>

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
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81231f90)
Location: fs/read_write.c:1699
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff81231f90-ffffffff812321f1: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812442f0)
Location: fs/read_write.c:1947
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812442f0-ffffffff8124455e: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8124fa80)
Location: fs/read_write.c:1963
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8124fa80-ffffffff8124fcdf: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812719d0)
Location: fs/read_write.c:1966
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812719d0-ffffffff81271c36: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81297840)
Location: fs/read_write.c:1993
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff81297840-ffffffff81297aa6: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ac660)
Location: fs/read_write.c:2100
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812ac660-ffffffff812ac82a: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c8dd0)
Location: fs/read_write.c:2173
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812c8dd0-ffffffff812c8fa4: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812da7e0)
Location: fs/read_write.c:2171
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812da7e0-ffffffff812da9b4: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81310d20)
Location: fs/read_write.c:2255
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_dedupe_range
```
**Symbols:**

```
ffffffff81310d20-ffffffff81310f2c: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81366200)
Location: fs/remap_range.c:501
Inline: False
Direct callers:
  - fs/ioctl.c:ioctl_file_dedupe_range
```
**Symbols:**

```
ffffffff81366200-ffffffff813663d6: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff8136cbf0)
Location: fs/remap_range.c:504
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8136cbf0-ffffffff8136cdea: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff813bb8b0)
Location: fs/remap_range.c:492
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff813bb8b0-ffffffff813bbaaa: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81441b00)
Location: fs/remap_range.c:482
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff81441b00-ffffffff81441d37: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff814d0de0)
Location: fs/remap_range.c:491
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff814d0de0-ffffffff814d1017: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81507910)
Location: fs/remap_range.c:494
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff81507910-ffffffff81507b3f: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff8153c0a0)
Location: fs/remap_range.c:492
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff8153c0a0-ffffffff8153c2ab: vfs_dedupe_file_range (STB_GLOBAL)
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
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff80001037fe30)
Location: fs/read_write.c:2171
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffff80001037fe30-ffff80001038001c: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056aa58)
Location: fs/read_write.c:2171
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
c056aa58-c056acf8: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000475df0)
Location: fs/read_write.c:2171
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
c000000000475df0-c0000000004760b8: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000255756)
Location: fs/read_write.c:2171
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffe000255756-ffffffe0002558ec: vfs_dedupe_file_range (STB_GLOBAL)
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
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2dc0)
Location: fs/read_write.c:2171
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812d2dc0-ffffffff812d2f94: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c3a40)
Location: fs/read_write.c:2171
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812c3a40-ffffffff812c3c14: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d0bd0)
Location: fs/read_write.c:2171
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812d0bd0-ffffffff812d0da4: vfs_dedupe_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_dedupe_file_range(struct file *file, struct file_dedupe_range *same);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e1a00)
Location: fs/read_write.c:2171
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff812e1a00-ffffffff812e1bd4: vfs_dedupe_file_range (STB_GLOBAL)
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
